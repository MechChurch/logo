# logo
MechChurch logo 

File name format:
```
^(?:MC)?  # Cross is on the picture
 \w       # First letter of color
 \w?      # First letter of background color. Omit if bg is transparent
 \w{0,2}  # Text style. None if there is no text. C -- column, L -- line, CL -- line of text in column with logo
 (_\w+?)? # Comment
 \.\w+$   # Extension
 ```

![logo](png/MCBL.png)
