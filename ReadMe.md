
# Hydrodynamic Data

Data set containing hydrodynamic coefficients for:

* Single Wave Energy Converter (WEC) devices with varying radius and slenderness ratio (radius/draft)
* Pairs of WEC devices with varying radius and slenderness ratio (radius/draft) and locations, with the first WEC always at the center of the coordinate center and the second WEC positioned at randomly selected locations 

The Single WEC data set contains samples selected from
 * 0.5 $\leq$ Radius $\leq$ 10,
 * 0.2 $\leq$ Slenderness ratio $\leq$ 10,
 * 0.5 $\leq$ Draft $\leq$ 20, 
 
with some samples strategically located on the boundary. The WEC pair data set entails samples that in addition to the plant design space described for single WEC data set, includes the distance and angle between the first and second WECs.
 * Radius $\leq$ Distance $\leq$ 1000 meters,
 * 0 $\leq$ Angle $\leq$ $\pi$  
 
Since the dataset is developed through an active leaning strategy called query by committee, there is a variable number of samples in each quantity of interest. For single WEC data set the number of samples are:
* A (Added Mass): 510
* B (Damping coefficient): 310
* real(Fe) (Real part of excitation force): 260   
* imag(Fe) (Imaginary part of excitation force): 860   

For WEC pair data set, the number of samples are:
* $A_{11}$: 8981
* $A_{12}$: 6731
* $B_{11}$: 1781
* $B_{12}$: 10481
* real(Fe): 10481
* imag(Fe): 10481

Finally, note that the hydrodynamic coefficients are frequency-dependent and for each sample point, entail 100 frequency components defined as:
* $\omega$ = linspace(0.3,2,100)
 


## Citation
Please cite the following articles if you use the data set: 

* S Azad, DR Herber. **Concurrent Probabilistic Control Co-Design and Layout Optimization of Wave Energy Converter Farms Using Surrogate Modeling**. In ASME 2023 International Design Engineering Technical Conferences, DETC2023-116896, Aug. 2023. [[DOI]](https://doi.org/10.1115/detc2023-116896) [[PDF]](https://arxiv.org/pdf/2308.06418.pdf)
 