---
external help file: PSFreshservice-help.xml
Module Name: PSFreshservice
online version:
schema: 2.0.0
---

# Remove-FreshServiceRelease

## SYNOPSIS
Delete a Freshservice Release.

## SYNTAX

```
Remove-FreshServiceRelease [-id] <Int64> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Delete a Freshservice Release via REST API.

https://api.freshservice.com/#delete_a_release

## EXAMPLES

### EXAMPLE 1
```
Remove-FreshServiceRelease -id 3
```

id status
-- ------
3 success 204

Delete a Freshservice Release.
Default API has no response, artificial response with id and
status containing status code is returned for tracking.

## PARAMETERS

### -id
Unique id of the Freshservice Release.

```yaml
Type: Int64
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: 0
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES
This module was developed and tested with Freshservice REST API v2.

## RELATED LINKS