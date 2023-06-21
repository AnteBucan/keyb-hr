# Description
The file KEYBOARD.SYS contains:
- hr keyboard layouts:
  - Croatian in CP852 (852)
  - Croatian in CROSCII (999)
  - Croatian in ISO8859-2 (912)
  - Croatian in CP1250 (1250)
- hx keyboard layouts:
  - Croatian in CP852 and CROSCII (10852)
  - Croatian in ISO8859-2 and CP1250 (10912)
  - Croatian in CP1250, ISO8859-2 and CROSCII (11250)
  - Croatian without diacritics (czs) (437) 

# Creating custom keyboard layouts
## Prerequisites:
- kc200x.zip from FreeDOS

## Usage
Unzip kc200x.zip in DOSBox directory and copy .KEY files to BIN subdirectory.

Start DOSBox and change directory to BIN subdirectory where the KC.EXE and KLIB.EXE files are located.

Edit .KEY files.

Run:
```
KC HR HR
KC HX HX
```
to compile .KL files from .KEY files.

If there are no errors, you successfully created .KL files that you can use in DOSBox.

To combine .KL files in a single .SYS file run:
```
KLIB KEYBOARD.SYS
KLIB KEYBOARD.SYS +HR.KL
KLIB KEYBOARD.SYS +HX.KL
KLIB KEYBOARD.SYS /Z
```

If there are no errors, you successfully created KEYBOARD.SYS that you can use in DOSBox.
