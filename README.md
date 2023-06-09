# Dipole-RF-Arrays-for-cardiac-MRI

Dipole RF Arrays for cardiac MRI at 7.0T (297.2MHz) and 14.0T (600MHz). RF arrays using self-grounded bow-tie (SGBT) antenna building blocks [1], bow-tie (BT) antenna building blocks [2], and fractionated dipole (FD) antennas [3] placed on the human voxel model Duke and Ella [4]. The SGBT has a size of 24.3x48.0x89.3 mm³ at 7.0 T and 12.2x24.0x44.7 mm³ at 14.0 T. For each SGBT a parallel capacitor and a serial inductor were used for tuning and matching. The BT uses a size of 53.0x76.0x156.0 mm³ at 7.0 T and 26.5x38.0x78.0 mm³ at 14.0 T. The tuning and matching circuit consist of a serial and a parallel capacitor. The FD consists of a dipole antenna (7.0 T: 304.0x10.0x1.6 mm³, 14.0 T: 152.0x5.0x0.8 mm³), where low loss optimized meander elements are modeled as lumped elements (7.0 T: L = 33.5 nH, Q = 258.2 at 7.0 T, 14.0 T: L = 17.9 nH, Q = 88.0) between the three segments of the antenna legs.

For the 7.0 T baseline setup a 32-channel parallel transmission (pTx)/Rx SGBT array, a 16-channel pTx/Rx BT array, and a 8-channel pTx/Rx FD array was used. At 14.0 T, the same channel count setup used the same center position for each building block as implemented at 7.0 T. For the double channel count setup at 14.0 T, a 64-channel pTx/Rx SGBT array, 32-channel pTx/Rx BT array, and a 16-channel pTx/Rx FD array was used

Numerical EMF simulations of the RF arrays were performed using the finite difference time domain solver of CST Studio Suite 2020 (CST Studio Suite 2020, Dassault Systèmes, Vélizy-Villacoublay Cedex, France). Broad-band excitation (bandwidth: fex=± 50.0 MHz) was applied for a center frequency of fex =297.2 MHz and fex=600 MHz. The human voxel models Duke (body mass index [BMI]=23.1 kg/m2) and Ella (BMI=22.7 kg/m2) of the Virtual Family (resolution: 1.0x1.0x1.0 mm³) were used [4]. Duke and Ella were truncated at the neck and the hips and placed at the isocenter of an RF shield model of the 7.0 T and 14.0 T MRI bore. For the EMF simulations, the electrical material parameters of the antennas and the tissue parameters provided by the IT‘IS Foundation [5] were adapted to 297.2 MHz and 600 MHz conditions. 


REFERENCES

[1] Eigentler TW, Kuehne A, Boehmert L, Dietrich S, Els A, Waiczies H, Niendorf T (2021) 32-Channel self-grounded bow-tie transceiver array for cardiac MR at 7.0T. Magn Reson Med 86 (5):2862-2879.

[2] Oezerdem C, Winter L, Graessl A, Paul K, Els A, Weinberger O, Rieger J, Kuehne A, Dieringer M, Hezel F, Voit D, Frahm J, Niendorf T (2016) 16-channel bow tie antenna transceiver array for cardiac MR at 7.0 tesla. Magn Reson Med 75 (6):2553-2565.

[3] Raaijmakers AJE, Italiaander M, Voogt IJ, Luijten PR, Hoogduin JM, Klomp DWJ, Van Den Berg CAT (2016) The fractionated dipole antenna: A new antenna for body imaging at 7 Tesla. Magn Reson Med 75 (3):1366-1374.

[4] Christ A, Kainz W, Hahn EG, Honegger K, Zefferer M, Neufeld E, Rascher W, Janka R, Bautz W, Chen J, Kiefer B, Schmitt P, Hollenbach HP, Shen J, Oberle M, Szczerba D, Kam A, Guag JW, Kuster N (2010) The Virtual Family--development of surface-based anatomical models of two adults and two children for dosimetric simulations. Physics in medicine and biology 55 (2).

[5] Foundation II (2018) Tissue Properties Database V4.0. IT'IS Foundation,  doi:10.13099/VIP21000-04-0.
