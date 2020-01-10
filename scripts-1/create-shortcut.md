# Create Shortcut

$WshShell = New-Object -comObject WScript.Shell $Shortcut = $WshShell.CreateShortcut\("C:\Users\Public\Desktop\'name of shortcut'.lnk"\) $Shortcut.TargetPath = "C:\Program Files\VideoLAN\VLC\vlc.exe" $Shortcut.Save\(\)

