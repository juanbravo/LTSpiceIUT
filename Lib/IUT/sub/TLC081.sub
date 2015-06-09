
*   DEVICE = TLC081
*
*   Rev. A     	TLC081 operational amplifier "macromodel" subcircuit
* 			created using Parts release 8.0 on 12/17/99 at 15:28
* 			Parts is a MicroSim product.
*
*   Rev. B    	22 August 2003 By Neil Albaugh: ADDED HEADER TEXT & EDITED MODEL 
*			FROM TLC081_12V_CMOS.lib
*
* connections: non-inverting input
*              | inverting input
*              | | positive power supply
*              | | | negative power supply
*              | | | | output
*              | | | | |
.subckt TLC081 1 2 3 4 5
*
  c1   11 12 4.2895E-12
  c2    6  7 8.0000E-12
  css  10 99 635.76E-15
  dc    5 53 dy
  de   54  5 dy
  dlp  90 91 dx
  dln  92 90 dx
  dp    4  3 dx
  egnd 99  0 poly(2) (3,0) (4,0) 0 .5 .5
  fb    7 99 poly(5) vb vc ve vlp vln 0 23.969E6 -1E3 1E3 24E6 -24E6
  ga    6  0 11 12 417.20E-6
  gcm   0  6 10 99 499.29E-9
  iss   3 10 dc 130.40E-6
  hlim 90  0 vlim 1K
  j1   11  2 10 jx1
  j2   12  1 10 jx2
  r2    6  9 100.00E3
  rd1   4 11 2.3969E3
  rd2   4 12 2.3969E3
  ro1   8  5 10
  ro2   7 99 10
  rp    3  4 6.0581E3
  rss  10 99 1.5337E6
  vb    9  0 dc 0
  vc    3 53 dc 1.4999
  ve   54  4 dc .85993
  vlim  7  8 dc 0
  vlp  91  0 dc 220
  vln   0 92 dc 220
.model dx D(Is=800.00E-18)
.model dy D(Is=800.00E-18 Rs=1m Cjo=10p)
.model jx1 PJF(Is=5.0000E-15 Beta=1.3348E-3 Vto=-1)
.model jx2 PJF(Is=5.0000E-15 Beta=1.3348E-3 Vto=-1)
.ends
* END MODEL TLC081

