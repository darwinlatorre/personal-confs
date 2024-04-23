## 1. Theme are import from -> [JSON](themes.json)

## 2. Font chosen with the follow up command: GeistMono NFM

> `oh-my-posh font install`

After installing the font, you have to set it in your terminal.

## 3. To set the configuration of theme

Command to see the deault route of oh-my-posh.

> `oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\jandedobbeleer.omp.json"`

Command to set the theme.

> `` (@(& 'C:/Users/Darwi/AppData/Local/Programs/oh-my-posh/bin/oh-my-posh.exe' init pwsh --config='C:\Users\Darwi\AppData\Local\Programs\oh-my-posh\themes\pure.omp.json' --print) -join "`n") | Invoke-Expression ``

## 4. To set default configuration we use the follow up commands

> `notepad $PROFILE` OR `New-Item -Path $PROFILE - Type File -Force`

Then you copy the command to set the theme into the file, close and the you have your set up.

## 5. If you want the icons for terminal use the follow up command

> `Install-Module -Name Terminal-Icons -Repository PSGallery`

To activate the icos you have to copy the follow command into the before created file.

> `Import-Module Terminal-Icons`

## 6. If you want the command line PredictionViewStyle

Use this command

> `Set-PSReadLineOption -PredictionViewStyle ListView`

# [How should look your config file](Microsoft.PowerShell_profile)
