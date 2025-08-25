# Topic and Skill Service (Python Flask)

Wie startest du die App.

1. Virtuelle Umgebung: Aktiviere deine virtuelle Umgebung im Terminal:

Linux/macOS: 
```bash
python -m venv venv #Wenn noch nicht erstellt
source venv/bin/activate
```

Windows mit Git Bash: 
```bash
python -m venv venv #Wenn noch nicht erstellt
source venv/Scripts/activate
```

Windows (PowerShell): 
```bash
python -m venv venv #Wenn noch nicht erstellt
.\venv\Scripts\Activate.ps1
```

Windows (Cmd): 
```bash
python -m venv venv #Wenn noch nicht erstellt
venv\Scripts\activate.bat
```

2. Abhängigkeiten installieren:
```bash
pip install -r requirements.txt
```

3. Server starten: Führe die app.py-Datei aus:
```bash
python app.py
````

Dein Server sollte auf `http://127.0.0.1:5000/` laufen.