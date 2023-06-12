# keyb
Creating keyboard layout

## Prerequisites:
- kc200x.zip from FreeDOS

## USAGE
Edit .KEY files.

Unzip kc200x.zip in DOSBox directory and copy .KEY files to that directory.

Start DOSBox and change directory to BIN subdirectory where the KC.EXE and KLIB.EXE files are located.

Run:
```
KC HR HR
KC HX HX
```
to compile .KL files from .KEY files.

If there are no errors, you successfully created .KL files that you can use in DOSBox, or you can combine them in single .SYS file.

Run:
```
KLIB KEYBOARD.SYS
KLIB KEYBOARD.SYS +HR.KL
KLIB KEYBOARD.SYS +HX.KL
KLIB KEYBOARD.SYS /Z
```

If there are no errors, you successfully created KEYBOARD.SYS that you can use in DOSBox.
