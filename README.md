# log-sys
Clear operating system logs

## Usage/Examples

```powershell
Clear-EventLog -LogName "Application"
Clear-EventLog -LogName "System"

```

```python
import subprocess

subprocess.call(["powershell.exe", "./clear_logs.ps1"])


```
```linux 
sudo rm /var/log/*
sudo rm /var/log/nam-e-log

```
