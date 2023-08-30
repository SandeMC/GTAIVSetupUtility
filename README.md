# Gillian's GTA IV Setup Utility
Semi-automatically installs DXVK and launch options for your GTA IV installation. It automatically checks your hardware and what options to use, aswell as accounting for installed mods.

## Building
This is a basic Python script, but some people might want to build the .exe out of it on their own. 

```py
pip install -r requirements.txt
pip install nuitka
nuitka GTAIVSetupUtility.py --onefile --include-plugin=pyside6
```