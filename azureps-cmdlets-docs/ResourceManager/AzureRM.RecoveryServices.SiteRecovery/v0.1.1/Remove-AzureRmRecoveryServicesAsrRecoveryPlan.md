---
external help file: Microsoft.Azure.Commands.RecoveryServices.SiteRecovery.dll-Help.xml
online version:
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/RecoveryServices.SiteRecovery/Commands.RecoveryServices.SiteRecovery/help/Remove-AzureRmRecoveryServicesAsrRecoveryPlan.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/RecoveryServices.SiteRecovery/Commands.RecoveryServices.SiteRecovery/help/Remove-AzureRmRecoveryServicesAsrRecoveryPlan.md
gitcommit: https://github.com/Azure/azure-powershell/blob/01991997d8025016140f94010af77fc3145fefff
---

# Remove-AzureRmRecoveryServicesAsrRecoveryPlan

## SYNOPSIS
Delets the specified ASR recovery plan from Recovery Services vault.

## SYNTAX

### ByObject (Default)
```
Remove-AzureRmRecoveryServicesAsrRecoveryPlan -InputObject <ASRRecoveryPlan> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### ByName
```
Remove-AzureRmRecoveryServicesAsrRecoveryPlan -Name <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmRecoveryServicesAsrRecoveryPlan** cmdlet deletes the specified recovery plan from the Recovery Services vault.

## EXAMPLES

### Example 1
```
PS C:\> $currentJob = Remove-AzureRmRecoveryServicesAsrRecoveryPlan -RecoveryPlan $RP
```

Starts the deletion of specified recovery plan and returns the ASR job used to track the operation.

## PARAMETERS

### -InputObject
The input object to the cmdlet: The ASR recovery plan object corresponding to the recovery plan to be deleted.

```yaml
Type: ASRRecoveryPlan
Parameter Sets: ByObject
Aliases: RecoveryPlan

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Name
Specifies the name of the recovery plan to be deleted.

```yaml
Type: String
Parameter Sets: ByName
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs. The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Azure.Commands.RecoveryServices.SiteRecovery.ASRRecoveryPlan

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS

[Get-AzureRmRecoveryServicesAsrRecoveryPlan](./Get-AzureRmRecoveryServicesAsrRecoveryPlan.md)

[New-AzureRmRecoveryServicesAsrRecoveryPlan](./New-AzureRmRecoveryServicesAsrRecoveryPlan.md)

[Update-AzureRmRecoveryServicesAsrRecoveryPlan](./Update-AzureRmRecoveryServicesAsrRecoveryPlan.md)


