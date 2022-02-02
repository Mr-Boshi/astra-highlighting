# ASTRA highlighting for VS Code

This extention adds the support for ASTRA (Automated System for TRansport Analysis) language in VS Code.


**Attention! This extention is not for the AgentSpeak(TR+ER) implementation.**

## Features
Supports common syntax features:
* Сomment lines.
* Comment blocks.
* Folding blocks. Start tag: "`!\`" or "`! \`". End tag: "`!/`" or "`! /`".

Highlitghts variables and functions of different types:
* Scalars: 
**AB**, **ABC**, **AIM1**, **AIM2**, **AIM3**, **AMAIN**, **AMJ**, **AWALL**, **BTOR**, **ELONG**, **ELONM**, **ENCL**, **ENWM**, **FECR**, **FFW**, **FICR**, **FLH**, **GN2E**, **GN2I**, **IPL**, **LEXT**, **NIZ1**, **NNCL**, **NNWM**, **QECR**, **QFW**, **QICR**, **QLH**, **QNBI**, **ROC**, **RTOR**, **SHIFT**, **TEND**, **TRIAN**, **TSTART**, **UEXT**, **UPDWN**, **VOLUME**, **VSB**, **VSC**, **WNE**, **WTE**, **WTI**, **ZIM1**, **ZMAIN**, **ZMJ**.

* Radial functions: 
**AMETR**, **CC**, **CD**, **CU**, **CUBS**, **ELON**, **F1**, **F2**, **F3**, **FP**, **FV**, **G11**, **G22**, **G33**, **IPOL**, **MU**, **MV**, **NDEUT**, **NE**, **NHYDR**, **NI**, **NN**, **QE**, **QI**, **QN**, **RHO**, **RHOW**, **SHIF**, **SHIV**, **SQEPS**, **TE**, **TI**, **TN**, **TRIA**, **ULON**, **VOLUM**, **VP**, **VPOL**, **VPOR**, **VR**, **VRO**, **VRS**, **VRX**, **ZEF**.

* Control parameters: 
  **DELVAR**, **DPOUT**, **DROUT**, **DTEQL**, **DTOUT**, **ITEREX**, **MEQUIL**, **NB1**, **NB2EQL**, **NBND**, **NEQUIL**, **NITREQ**, **NUF**, **TAUINC**, **TAUMAX**, **TAUMIN**, **TIME**, **TINIT**, **TSCALE**, **XFLAG**, **XINPUT**, **XOUT**.

* Variables: 
**CBND\***, **CCD\***, **CDBC\***, **CDHJ\***, **CDJM\***, **CDMJ\***, **CDVM\***, **CDWM\***, **CDYM\***, **CF\***, **CFUS\***, **CHE\***, **CHI\***, **CIMP\***, **CMHD\***, **CNB\***, **CNBI\***, **CNEUT\***, **CPEL\***, **CRAD\***, **CRF\***, **CSCL\***, **CSOL\***, **CV\***, **TPAUSE**, **ZRD\***.

* Build-in functions: 
**ABS**, **AFR**, **AFVAL**, **AFX**, **ALOG**, **ALOG10**, **ANINT**, **ASIN**, **ASTEP**, **ATAN**, **COS**, **CUT**, **EXP**, **FA**, **FIXVAL**, **FJUMP**, **FLIN**, **FPA**, **FPR**, **FR**, **FRAMP**, **FRMAX**, **FRMIN**, **FRS**, **FTAV**, **FTMAX**, **FTMIN**, **FX**, **GAUSS**, **GRAD**, **IINT**, **MAX**, **MIN**, **NEAV**, **REAL**, **RFA**, **RFAN**, **RFMAX**, **RFMIN**, **RFVAL**, **RSTEP**, **SIGN**,  **SIN**, **SQRT**, **STEP**, **TAN**, **TIMDER**, **TIMINT**, **VINT**, **WTOT**, **XFA**, **XFAN**, **XSTEP**, .

* Subroutines from the sbr/:
  **a2g**, **abel_trans**, **addpel**, **ajs**, **amoeba**, **aprint**, **as_ogray**, **as_strahl**, **as_strahl_ne**, **assign**, **atci06**, **averfs**, **b2eit**, **balst**, **betagw**, **blas_zgeev**, **bln**, **bsal**, **callglf2d**, **chicr**, **chimod**, **config**, **conipl**, **coptan**, **corona**, **cpmu**, **cpmu1**, **cpmu2**, **d2arr**, **deviation**, **djump**, **dlsoda**, **dtmode**, **e3m**, **ei_heat_transf**, **eqpr1d**, **EXPray**, **feeden**, **feven**, **fgauss**, **four1**, **fourar**, **fourex**, **fourtr**, **fourv**, **fourvr**, **frabun_calc**, **ftanhf**, **get_Xei**, **glf161**, **glf161a**, **glf161d**, **glf23b**, **glf23c**, **glf23d**, **glf23f**, **glf23g**, **glf2d**, **gnex**, **gnxsrc**, **gnxsrc_z**, **grid_circular**, **gridstrahl**, **h98scaling**, **heat_transport**, **icray**, **ifsppl**, **igen**, **int_rdr**, **layer**, **lhcd**, **lhvmk**, **lsode**, **minmax**, **mix**, **mix1**, **mixext**, **mixint**, **mixq**, **mmm4a**, **mse**, **mse6**, **myconv**, **mydraw**, **mykey**, **myout**, **myprint**, **nbi**, **nclass**, **nctj2**, **neocl**, **neocls**, **neomean**, **NEUT**, **neut_z**, **NEUTAB**, **neuten**, **neutex**, **oldsbrread_dyn**, **onotusedread_dyn2**, **out2gyro**, **Pcx_Hn2**, **pelite**, **pelitefsetfd**, **pfalp**, **plim**, **plim1**, **powell**, **printtout**, **pzrad**, **Qcx_CVI**, **Qlpf**, **Qpost_fe**, **quadro_deviation**, **quafit**, **r4sbrspline1**, **r8tomsqz**, **rad_get**, **rad_losses**. **read_dyn**, **read_input_constant_file**, **setfa**, **setfc**, **setfus**, **setnav**, **setneavr**, **setnep**, **setpel**, **setplh**, **setq**, **setran**, **shcor**, **shcor1**, **simson**, **smash**, **smear1**, **smearr**, **smofml**, **smooth2**, **smoothfac**, **sneav**, **sqrmod**, **starr**, **staterr**, **stvar**, **toeqdsk**, **tostop**, **tsctrl**, **tunen**, **twave**, **write_spider_to_dat**, **wrsudg**, **zalfl**, **zeff2b**, **zgeev**.

* Special types: 
  **AS**, **EQ**, **WORK()**.

Color grouping is based on ASTRA manual section 4.10.1.

## Release Notes

This is a work in progress extention but most of the needed stuff is already working.
Extention's repo: __https://github.com/Mr-Boshi/astra-highlighting__

## Changelog

See  the changes in the [**Changelog**](CHANGELOG.html).

