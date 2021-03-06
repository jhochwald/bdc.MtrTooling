﻿# Test-MtrWallpaper

## SYNOPSIS
Check if a given Wallpaperfile has the correct resolution

## SYNTAX

### Set 1
```
Test-MtrWallpaper [-Path] <String> [<CommonParameters>]
```

## DESCRIPTION
Check if a given Wallpaperfile has the correct resolution.
All Images must be exactly 3840×1080, for Single or dual screen!

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
PS C:\\\>
```powershell
Test-MtrWallpaper -Path 'Z:\Desktop\wallpaper\TheBeachView.jpg'
```

True

### -------------------------- EXAMPLE 2 --------------------------
PS C:\\\>
```powershell
Test-MtrWallpaper -Path 'Z:\Desktop\wallpaper\TheBeachView.jpg'
```

False

## PARAMETERS

### Path


```yaml
Type: String
Parameter Sets: Set 1
Aliases: Wallpaper , MTRWallpaper , Image

Required: true
Position: 0
Default Value: 
Pipeline Input: True (ByPropertyName, ByValue)
```

### \<CommonParameters\>
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### String


## OUTPUTS

### Bool


## NOTES

All Images must be exactly 3840×1080, for Single or dual screen!

## RELATED LINKS


*Generated by: PowerShell HelpWriter 2020 v2.3.46*
