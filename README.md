# Neovim Config

## First

Run in PowerShell
```
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim/site/autoload/plug.vim" -Force
```

## Then

Open neovim and ```:PlugInstall```

Done!
