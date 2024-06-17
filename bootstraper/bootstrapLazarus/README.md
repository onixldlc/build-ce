# LAZARUS

download lazarus
```
version 2.2.2 x64
https://sourceforge.net/projects/lazarus/files/Lazarus%20Windows%2064%20bits/Lazarus%202.2.2/lazarus-2.2.2-fpc-3.2.2-win64.exe/download

version 2.2.2 x64 addons (cross compile to x86)
https://sourceforge.net/projects/lazarus/files/Lazarus%20Windows%2064%20bits/Lazarus%202.2.2/lazarus-2.2.2-fpc-3.2.2-cross-i386-win32-win64.exe/download
```

install lazarus
```
now i dont even know if this will works, but most docker script i saw uses these methods so...

Start-Process -NoNewWindow -Wait -PassThru  `
  -FilePath (".\\lazarus-2.2.2-fpc-3.2.2-win64.exe" -f "C:\\Windows\\TEMP")`
  -ArgumentList ('/VERYSILENT /NORESTART /LOG="C:\\Windows\\TEMP\\lazarus.log" /DIR="C:\\Lazarus"'); `
`
Start-Process -NoNewWindow -Wait -PassThru  `
  -FilePath (".\\lazarus-2.2.2-fpc-3.2.2-cross-i386-win32-win64.exe" -f "C:\\Windows\\TEMP")`
  -ArgumentList ('/VERYSILENT /NORESTART /LOG="C:\\Windows\\TEMP\\lazarus.log" /DIR="C:\\Lazarus"');

```
