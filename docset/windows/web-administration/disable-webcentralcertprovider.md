---
author: brianlic-msft
description: 
external help file: Microsoft.IIS.PowerShell.Provider.dll-Help.xml
keywords: powershell, cmdlet
manager: alanth
ms.date: 2016-12-27
ms.prod: powershell
ms.technology: powershell
ms.topic: reference
online version: 
schema: 2.0.0
title: Disable-WebCentralCertProvider
ms.assetid: 815BE835-30BE-4ABB-B518-FF2E47F35A94
---

# Disable-WebCentralCertProvider

## SYNOPSIS
Takes the central certificate provider offline.

## SYNTAX

```
Disable-WebCentralCertProvider [<CommonParameters>]
```

## DESCRIPTION
The **Disable-WebCentralCertProvider** cmdlet takes the central certificate provider offline.
Use the [Set-WebCentralCertProvider](./Set-WebCentralCertProvider.md) cmdlet to re-enable the provider.

## EXAMPLES

### Example 1: Disable the central certificate provider
```
PS C:\> Disable-WebCentralCertProvider
```

This command takes the central certificate provider offline.

## PARAMETERS

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Clear-WebCentralCertProvider](./Clear-WebCentralCertProvider.md)

[Enable-WebCentralCertProvider](./Enable-WebCentralCertProvider.md)

[Get-WebCentralCertProvider](./Get-WebCentralCertProvider.md)

[Set-WebCentralCertProvider](./Set-WebCentralCertProvider.md)