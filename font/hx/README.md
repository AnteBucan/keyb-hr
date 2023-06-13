# Description
The file EGA2.CPX contains "non-standard" combined Croatian fonts:
- CP10852 (CP437 with Croatian diacritics in CP852 and CROSCII places)
- CP10912 (CP437 with Croatian diacritics in ISO8859-2 and CP1250 places)
- CP11250 (CP437 with Croatian diacritics in CP1250, ISO8859-2 and CROSCII places)
- CP437

# Creating custom fonts
## Prerequisites
- font editor for DOS
- cpi120.zip
- upx-X.X.X-dos.zip

## Usage
Edit a font with a font editor in three sizes:
```
CP10852.F08
CP10852.F14
CP10852.F16
```
Extract cpi120.zip in DOSBox directory and copy font files to BIN subdirectory.

Copy CPI\BLANKEGA.CPI to BIN\EGA2.CPI.

Run:
```
FNT2CP 10852
```
If there are no errors, you successfully created CP10852.CP file.

Run:
```
CPIADD EGA2.CPI 10852
```
If there are no errors, you successfully added CP10852 to EGA2.CPI file that you can use in DOSBox.

Create .CP files for other code pages and add them to EGA2.CPI.

If you want to compress .CPI file to .CPX, extract upx-X.X.X-dos.zip in DOSBox directory and copy EGA2.CPI to upx-X.X.X-dos subdirectory.

Rename EGA2.CPI to EGA2.COM.

Run:
```
UPX --8086 EGA2.COM
```
If there are no errors, rename EGA2.COM to EGA2.CPX that you can use in DOSBox.
