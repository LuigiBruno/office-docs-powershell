---
external help file: Microsoft.Exchange.WebClient-Help.xml
applicable: Exchange Online
title: Remove-OMEConfiguration
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
monikerRange: "exchonline-ps"
---

# Remove-OMEConfiguration

## SYNOPSIS
This cmdlet is available only in the cloud-based service.

Use the Remove-OMEConfiguration cmdlet to remove custom Microsoft Office 365 Message Encryption (OME) configurations. You can't use this cmdlet to remove the default OME configuration.

For information about the parameter sets in the Syntax section below, see Exchange cmdlet syntax (https://technet.microsoft.com/library/bb123552.aspx).

## SYNTAX

```
Remove-OMEConfiguration [-Identity] <OMEConfigurationIdParameter>
 [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
You need to be assigned permissions before you can run this cmdlet. Although this topic lists all parameters for the cmdlet, you may not have access to some parameters if they're not included in the permissions assigned to you. To find the permissions required to run any cmdlet or parameter in your organization, see Find the permissions required to run any Exchange cmdlet (https://technet.microsoft.com/library/mt432940.aspx).

## EXAMPLES

### Example 1
```
Remove-OMEConfiguration -Identity "Contoso Marketing"
```

This example removes the custom OME configuration named Contoso Marketing.

## PARAMETERS

### -Identity
The Identity parameter specifies the custom OME configuration that you want to remove. You can use the Get-OMEConfiguration cmdlet to see the available values. If the value contains spaces, enclose the value in quotation marks

```yaml
Type: OMEConfigurationIdParameter
Parameter Sets: (All)
Aliases:
Applicable: Exchange Online
Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Confirm
The Confirm switch specifies whether to show or hide the confirmation prompt. How this switch affects the cmdlet depends on if the cmdlet requires confirmation before proceeding.

- Destructive cmdlets (for example, Remove-\* cmdlets) have a built-in pause that forces you to acknowledge the command before proceeding. For these cmdlets, you can skip the confirmation prompt by using this exact syntax: -Confirm:$false.

- Most other cmdlets (for example, New-\* and Set-\* cmdlets) don't have a built-in pause. For these cmdlets, specifying the Confirm switch without a value introduces a pause that forces you acknowledge the command before proceeding.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: Exchange Online
Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
The WhatIf switch simulates the actions of the command. You can use this switch to view the changes that would occur without actually applying those changes. You don't need to specify a value with this switch.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: Exchange Online
Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS

[Online Version](https://docs.microsoft.com/powershell/module/exchange/encryption-and-certificates/Remove-OMEConfiguration)
