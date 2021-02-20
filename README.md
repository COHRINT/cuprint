# cuprint
Colored terminal printing for identifying node print statements in shared terminal setting

## Example Usage
```
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