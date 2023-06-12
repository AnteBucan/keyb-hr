# Description
In DOSBox there is already code page 852. This adds modified 852, CROSCII, ISO8859-2 and 1250 code pages.

Adding only Croatian diacritics (čćžšđČĆŽŠĐ) to CP437 font preserves most of the box-drawing characters in DOSBox.

## Usage
Download the latest release and unpack it in DOSBox folder.

Use .BAT files to load the desired font and keyboard:

- ### HR.BAT
     - EGA.CPX font with Croatian diacritics in CP852
     - hr keyboard in CP852
- ### CRO.BAT
     - EGA.CPX font with Croatian diacritics in CROSCII
     - hr keyboard in CROSCII
- ### ISO.BAT
     - EGA.CPX font with Croatian diacritics in ISO8859-2
     - hr keyboard in ISO8859-2
- ### WIN1250.BAT
     - EGA.CPX font with Croatian diacritics in CP1250
     - hr keyboard in CP1250
- ### HRC.BAT
     - EGA2.CPX font with Croatian diacritics in CP852 and CROSCII
     - hx keyboard in CP852 and CROSCII
     - Switch between keyboards with Alt-LShift (CP852) and Alt-RShift (CROSCII)
- ### ISOWIN.BAT
     - EGA2.CPX font with Croatian diacritics in ISO8859-2 and CP1250
     - hx keyboard in ISO8859-2 and CP1250
     - Switch between keyboards with Alt-LShift (ISO8859-2) and Alt-RShift (CP1250)
- ### WIC.BAT
     - EGA2.CPX font with Croatian diacritics in CP1250, ISO8859-2 and CROSCII
     - hx keyboard in CP1250, ISO8859-2 and CROSCII
     - Switch between keyboards with Alt-LShift (CP1250), Alt-RShift (ISO8859-2) and Alt-RCtrl (CROSCII)
- ### US.BAT
     - EGA2.CPX font in CP437
     - hx keyboard in CP852 without Croatian diacritics (czs)
