# cuprint
Colored terminal printing. Prepends node name so you can determine which node is printing when multiple nodes share same stdout (e.g. roslaunch).

## Example Usage
```
from cuprint.cuprint import CUPrint

cuprint = CUPrint("Test Print Node", ros=False)
cuprint("I love strawberries")
cuprint("I love strawberries", warn=True)
cuprint("I love strawberries", err=True)
```
![Example](cuprint_example.png)

## Testing
```
python cuprint.py
```