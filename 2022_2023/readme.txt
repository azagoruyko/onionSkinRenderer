import sys
path = r"C:\onionSkinRenderer\2022_2023"  # change path here
if path not in sys.path:
    sys.path.append(path)
    
import onionSkinRenderer.controller as ctl
ctl.show()