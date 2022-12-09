# wsl-on-windows
Step by step for wsl installing on windows 11.

## Pre-requirement
- Host OS - Windows 10, Windows 11
- Target OS - Ubuntu-20.04 +

## Step-by-step
Run PowerShell as administrator then input following commands.

(** Maybe you need to download and install <a href="https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi" target="_blank">wsl_update_x64.msi manually.</a> **)

```code
  C:\Windows\system32> wsl --shutdown
  C:\Windows\system32> netsh winsock reset
```

Then, you should reboot the computer then it works properly

Finally, input following command line.

```code
  C:\Windows\system32> wsl --install -d Ubuntu-20.04
```


***** end *****

Good Luck!⚡
