##### README.md
###### 15-Nov-2024

Code samples for StevePro Studios blog post [OpenAI Retro Cheat Sheet](https://steveproxna.blogspot.com/2024/11/openai-retro-cheat-sheet.html)

Launch PyCharm | New project | RetroCheatSheet
```
RetroCheatSheet
~/GitHub/SteveProXNA/OpenAItesting
source bin activate
```
IMPORTANT: if Python Interpreter not set and/or Virtual Environment not available then:
```
File | Settings... | Project: Python Interpreter | Add Interpreter | Add Local Interpreter
source bin activate
```
Setup ROMs
```
mkdir data
mkdir examples
cd examples
python copy_files.py
```
[Sega Master System](https://github.com/SteveProXNA/OpenAItesting/tree/main/RetroCheatSheet/examples/Sms)
```
pip install stable-retro
pip install --upgrade pip
```

[Sega Genesis](https://github.com/SteveProXNA/OpenAItesting/tree/main/RetroCheatSheet/examples/Genesis)
```
pip install stable-retro
pip install --upgrade pip
```
