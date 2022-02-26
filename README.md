# MinecraftBlockColorCodes.txt
This repo has RGB Color Codes for Minecraft Blocks. (not all)

Color codes are calculated by averaging the color of a 50x50 area. The formula for averaging is:
```python
# r = list of red values of a 50x50 area values = (0, 255)
# g = list of green values of a 50x50 area values = (0, 255)
# b = list of blue values of a 50x50 area values = (0, 255)

avg = (int(sum(r) / len(r)), int(sum(g) / len(g)), int(sum(b) / len(b)))
```
