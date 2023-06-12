# keyb-hr
Adding only Croatian diacritics (čćžšđČĆŽŠĐ) to CP437 codepage in CP852, CROSCII, ISO8859-2 and CP1250 standards. This preserves most of the box-drawing characters in DOSBox.

## Usage
Download the latest release and unpack it in DOSBox folder.

Use .BAT files to load the desired font and keyboard:

- ### HR.BAT
     - EGA.CPX font with Croatian diacritics in CP852 standard
     - hr keyboard in CP852 standard
- ### CRO.BAT
     - EGA.CPX font with Croatian diacritics in CROSCII standard
     - hr keyboard in CROSCII standard
- ### ISO.BAT
     - EGA.CPX font with Croatian diacritics in ISO8859-2 standard
     - hr keyboard in ISO8859-2 standard
- ### WIN1250.BAT
     - EGA.CPX font with Croatian diacritics in CP1250 standard
     - hr keyboard in CP1250 standard
- ### HRC.BAT
     - EGA2.CPX font with Croatian diacritics in CP852 and CROSCII standard
     - hx keyboard in CP852 and CROSCII standard
     - Switch between keyboards with Alt-LShift (CP852) and Alt-RShift (CROSCII)
- ### ISOWIN.BAT
     - EGA2.CPX font with Croatian diacritics in ISO8859-2 and CP1250 standard
     - hx keyboard in ISO8859-2 and CP1250 standard
     - Switch between keyboards with Alt-LShift (ISO8859-2) and Alt-RShift (CP1250)
- ### WIC.BAT
     - EGA2.CPX font with Croatian diacritics in CP1250, ISO8859-2 and CROSCII standard
     - hx keyboard in CP1250, ISO8859-2 and CROSCII standard
     - Switch between keyboards with Alt-LShift (CP1250), Alt-RShift (ISO8859-2) and Alt-RCtrl (CROSCII)
- ### US.BAT
     - EGA2.CPX font in CP437 standard
     - hx keyboard in CP852 standard without Croatian diacritics (czs)
