# cuprint
Colored terminal printing for identifying node print statements in shared terminal setting

## Example Usage
```
cuprint = CUPrint("Test Print Node", ros=False)
cuprint("I love strawberries")
```
Output: "[Test Print Node] I love strawberries"

One can also change the print color to indicate warnings and errors:
```
cuprint("I love strawberries", warn=True)
cuprint("I love strawberries", err=True)
```
"warn" changes the color to orange. "err" changes the color to red.

## Testing
```
python cuprint.py
```