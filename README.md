# vscode_settings

My custom [VS Code](https://code.visualstudio.com/) settings. For reference my OS is Windows 10 but I develop mostly on Ubuntu via [WSL](https://docs.microsoft.com/en-us/windows/wsl/faq).

:warning: **This might become obsolete when [this](https://code.visualstudio.com/docs/editor/settings-sync) goes stable.

## Why not using the Settings Sync [extension](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)?

I have tried it (see gist [here](https://gist.github.com/fnery/0b46b91f7daf8c7e7fbcce8e09a031bf), and nice [blog post](https://itnext.io/settings-sync-with-vs-code-c3d4f126989) to set it up). However, extensions installed only on WSL are not backed up with this method. Issue [here](https://github.com/shanalikhan/code-settings-sync/issues/979). So for now** I'll maintain this repo.

## Extensions

Installed globally:

    >> powershell.exe code --list-extensions --show-versions
    bierner.markdown-emoji@0.0.9
    CoenraadS.bracket-pair-colorizer-2@0.0.29
    DavidAnson.vscode-markdownlint@0.35.1
    ms-vscode-remote.remote-ssh@0.51.0
    ms-vscode-remote.remote-ssh-edit@0.51.0
    ms-vscode-remote.remote-wsl@0.44.2
    nemesv.copy-file-name@1.2.0
    Shan.code-settings-sync@3.4.3
    shardulm94.trailing-spaces@0.3.1
    streetsidesoftware.code-spell-checker@1.8.0
    tomoki1207.vscode-input-sequence@0.2.0
    Tyriar.shell-launcher@0.4.1
    wmaurer.change-case@1.0.0
    wmaurer.vscode-jumpy@0.3.1
    yzhang.markdown-all-in-one@2.8.0

Only on WSL:

- [ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [kevinrose.vsc-python-indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)

(`code --list-extensions --show-versions` doesn't work on WSL? :unamused:)