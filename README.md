# keyb-hr
Adding only Croatian diacritics (čćžšđČĆŽŠĐ) to CP437 codepage in CP852, CROSCII, ISO8859-2 and CP1250 standard. This preserves most of the box-drawing characters in DOSBox.

## Usage
Download the latest release and unpack it in DOSBox folder.

Use .bat files to load the desired font and keyboard:

- ### HR.BAT
     - Use EGA.CPX font with Croatian diacritics in CP852 standard
     - Use hr keyboard in CP852 standard
- ### CRO.BAT
     - Use EGA.CPX font with Croatian diacritics in CROSCII standard
     - Use hr keyboard in CROSCII standard
- ### ISO.BAT
     - Use EGA.CPX font with Croatian diacritics in ISO8859-2 standard
     - Use hr keyboard in ISO8859-2 standard
- ### WIN1250.BAT
     - Use EGA.CPX font with Croatian diacritics in CP1250 standard
     - Use hr keyboard in CP1250 standard
- ### HRC.BAT
     - Use EGA2.CPX font with Croatian diacritics in CP852 and CROSCII standard
     - Use hx keyboard in CP852 and CROSCII standard
     - Switch between keyboards with Alt-LShift (CP852) and Alt-RShift (CROSCII)
- ### ISOWIN.BAT
     - Use EGA2.CPX font with Croatian diacritics in ISO8859-2 and CP1250 standard
     - Use hx keyboard in ISO8859-2 and CP1250 standard
     - Switch between keyboards with Alt-LShift (ISO8859-2) and Alt-RShift (CP1250)
- ### WIC.BAT
     - Use EGA2.CPX font with Croatian diacritics in CP1250, ISO8859-2 and CROSCII standard
     - Use hx keyboard in CP1250, ISO8859-2 and CROSCII standard
     - Switch between keyboards with Alt-LShift (CP1250), Alt-RShift (ISO8859-2) and Alt-RCtrl (CROSCII)
- ### US.BAT
     - Use EGA2.CPX font in CP437 standard
     - Use hx keyboard in CP852 standard without Croatian diacritics (czs)
