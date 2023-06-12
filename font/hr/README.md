# Description
The file EGA.CPX contains "standard" Croatian fonts:
- CP852 (CP437 with Croatian diacritics in CP852)
- CP912 (CP437 with Croatian diacritics in ISO8859-2)
- CP999 (CP437 with Croatian diacritics in CROSCII)
- CP1250 (CP437 with Croatian diacritics in CP1250)

# Creating custom fonts
## Prerequisites
- font editor for DOS
- cpi120.zip
- upx-X.X.X-dos.zip

## Usage
Edit a font with a font editor in three sizes:
```
CP852.F08
CP852.F14
CP852.F16
```
Extract cpi120.zip in DOSBox directory and copy font files to BIN subdirectory.

Copy CPI\BLANKEGA.CPI to BIN\EGA.CPI.

Run:
```
FNT2CP 852
```
If there are no errors, you successfully created CP852.CP file.

Run:
```
CPIADD EGA.CPI 852
```
If there are no errors, you successfully added CP852 to EGA.CPI file that you can use in DOSBox.

Create .CP files for other codepages and add them to EGA.CPI.

If you want to compress .CPI file to .CPX, extract upx-X.X.X-dos.zip in DOSBox directory and copy EGA.CPI to upx-X.X.X-dos subdirectory.

Rename EGA.CPI to EGA.COM.

Run:
```
UPX --8086 EGA.COM
```
If there are no errors, rename EGA.COM to EGA.CPX that you can use in DOSBox.
