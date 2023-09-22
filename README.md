# Flask_commands

<img src="https://github.com/rodrigosistemas/flask_commands/blob/main/images/flask-logo.png?raw=true" alt="Flask logo" width="220" height="250">

## Powershell

### Create virtual environment
```PowerShell
python -m venv venv
```

### Activate virtual environment
```PowerShell
venv/Scripts/activate
```

### Deactivate virtual environment
```PowerShell
deactivate
```

### Change Flask variables
```PowerShell
$env:FLASK_APP = "app.py"
```

```PowerShell
$env:FLASK_DEBUG = "1"
```

### Read Flask variables
```PowerShell
$env:FLASK_APP
```

```PowerShell
$env:FLASK_DEBUG
```

### Run Flask
```PowerShell
flask run
```
