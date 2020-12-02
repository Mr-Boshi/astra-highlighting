# ASTRA highlighting for VS Code

This extention adds the support for ASTRA (Automated System for TRansport Analysis) language in VS Code.


**Attention! This extention is not for the AgentSpeak(TR+ER) implementation.**

## Features
Highlitghts variables and functions such as
* Сomment lines.
* Configuration: **RTOR**, **AB** (or **ABC**), **AMETR**, **SHIF**, **ELON**, **TRIA**, **RHO**, **RTOR**, **AWALL**, **NNCL**, **NNWM**, **ENCL**, **ENWM**, **LEXT** **UEXT**, **VOLUME**, **VSB**, **VSC**, **RHOW**, **ROC**, **QECR**, **QFW**, **QICR**, **QLH**, **QNBI**, **NB1**, **TSTART**, **TEND**.
* Plasma parameters: **AMJ** (or **AMAIN**), **ZEF**, **ZMJ** (or **ZMAIN**, **ZIM\***), **NE**, **NI**, **NHYDR**, **NDEUT**, **NIZ\***, **TE**, **TI**, **TN**, **NN**.
* Current and magnetic field: **IPL**, **BTOR**, **MU**, **CU**.
* Variables: **CF\***, **CV\***, **CHE\***, **CHI\***, **CNB\***, **CNBI\***, **CCD\***, **CRF\***, **CNEUT\***, **CPEL\***, **CBND\***, **CFUS\***, **CIMP\***, **CMHD\***, **CRAD\***, **CSOL\***, **AIM\***, **GN2E**, **GN2I**, **WNE**, **WTE**, **WTI**.
* Build-in functions: **WTOT**, **TIMDER**, **TIMINT**, **FJUMP**, **FRAMP**, **FIXVAL**, **FTAV**, **FTMIN**, **FTMAX**, **FA**, **FX**, **FLIN**, **FR**, **FRS**, **FPR**, **FPA**, **GAUSS**, **FRMIN**, **FRMAX**, **RFMIN**, **RFMAX**, **RFVAL**, **AFVAL**, **GRAD**, **VINT**, **IINT**, **VOLUM**, **NEAV**, **ASTEP**, **RSTEP**, **XSTEP**, **STEP**, **CUT**, **RFA**, **XFA**, **AFR**, **AFX**, **RFAN**, **XFAN**, **SIN**, **COS**, **TAN**, **ASIN**, **ATAN**, **EXP**, **ABS**, **MIN**, **MAX**, **SQRT**, **ALOG**, **ALOG10**, **ANINT**, **REAL**, **SIGN**.
* Some subroutines: **FGAUSS**, **gridstrahl**, **grid_circular**, **as_strahl**, **NEUT**, **NEUTAB**.
* **WORK()** array.

Color grouping is based on ASTRA manual section 4.10.1.

## Release Notes

This is a work in progress extention but most of the needed stuff is already working.
Extention's repo: __https://github.com/Mr-Boshi/astra-highlighting__


### 0.0.1

Initial release

### 0.1

* Coloring is more like you would expect from a syntax highlighting
* More variables are supported
* Math symbols are highlighted

