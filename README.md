# OnionSkinRenderer

Forked from: https://github.com/Viele/onionSkinRenderer

I've added support of Maya 2022, 2023

Run the script with the following:
```python
import sys
path = r"C:\onionSkinRenderer\2022_2023"  # change path here
if path not in sys.path:
    sys.path.append(path)
    
import onionSkinRenderer.controller as ctl
ctl.show()
```
