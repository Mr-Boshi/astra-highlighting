# Change Log

All notable changes to the "ASTRA" extension will be documented in this file.

### 0.0.1

Initial release

### 0.1

* Coloring is more like you would expect from a syntax highlighting
* More variables are supported
* Math symbols are highlighted

### 0.1.1

* **As_strahl** added
* **abel_trans** added

### 0.1.5
* Inline comment dimming is fixed
* Numbers are colored
* **Qlpf**, **read_dyn**, **rad_losses**, **time** added

### 0.2.0
* Gramar optimisation (~200 lines removed)
*  **Qe_\***, **heat_transport**, **neocl**, **printtout**, **ei\_heat\_transf**, **as\_ogray\_\*** added
*  Numbers at the end of some custom subroutines are supported

### 0.2.2
* Coloring fixed
* **neomean** and **tostop** added

### 0.2.5
* Coloring of single digit numbers fixed
* **CSCL**, **CDWM**, **CDYM**, **CDVM**, **CDBC**, **CDJM**, **CDMJ**, **CDHJ**, **CNHR**, **AS**, **EQ**,  **CC** added

### 0.3.0
* Language renamed to **ASTRA model**, the highlighting for ASTRA exp-files will be added later on
* VS Code recognizes ASTRA model syntaxis in **\*.astm-files**

## 0.4.0
* Added **ASTRA exp** file support
* Auto-recognition now works for files ending with **\*.asml** or **\*-asml** (ASTRA model) and **\*.asex** or **\*-asex** (ASTRA exp).

## 0.5.0
* Folding markers are added:
  any text between "`!\`" (or "`! \`") and "`!/`" (or "`! /`") is foldable. Folding block can have a title. Example:

  ```
  ! \ Folding block title
  Foldable text
  ! /
  ```
  For this to work the *Folding Strategy* in the *Settings* must be set to *auto*.
* Comment block highlighting is added. Default hotkey to comment a block of code is `shift+alt+a`. Note that uncommenting a comment block with this hotkey is currently not supported in this extention.
* **TAUMIN**, **TAUMAX**, **DPOUT**, **DROUT**, **DTOUT**, **TPAUSE**, **NEQUIL**, **ZRD0...ZRD100** added.
* Separate **WORK** highlighting was added.
  
## 0.5.1
* License added (GNU General Public License 3).

## 0.6.0
* 2 more data types added.
* Reorganised the variables by types.
* Readme now shows all supported highlights.
* All subroutines (from sbr/) are added (~140 subroutines).
