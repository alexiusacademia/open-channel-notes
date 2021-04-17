# Open Channel Flow



### I. Dimensions, Terminology and Review of Basic Fluid Mechanics

### A. Dimensions

1. **One-Dimensional Flow**

   > flow variables such as depth (Y) and velocity (V) are only a function of x.

2. **Two-Dimensional Flow**

   > flow variables such as depth (Y) and velocity (V) are functions of two directions (e.g. x & y or x & z).

3. **Three-Dimensional Flow**

   > flow variables are functions of axes x, y and z

### B. Fluid Flow

 1. **Steady Flow**

    > None of the flow variables can describe the flow change with respect to time.
    >
    > $$
    > \frac{\partial V}{\partial t} = 0 , \frac{\partial Y}{\partial t} = 0, \frac{\partial A}{\partial t} = 0
    > $$

    
    
 2. **Unsteady Flow**

    > If any variable that describes the flow changes with time.



3. **Uniform Flow**

   > When none of the flow variables changes with respect to `x`, direction of the channel flow.
   >
   > A flow is uniform if the depth, velocity and cross-sectional area are constant.

3. **Nonuniform Flow**

   > If any of the variables of the flow varies from position to position.

   3.1. ***Gradually Varied***

   - The pressure will increase in the vertical direction just as in uniform flow *(hydrostatic pressure)*.

   3.2. ***Rapidly Varied***

   - Change in depth is too rapid and the pressure distribution is not hydrostatic.

   3.3. ***Spatially Varied***

   - Those portions of the main channel flow wherein lateral inflow or outflow occurs.

4. **Flow Classification**

   > Flow in open channel is classified by comparing the average velocity (V) with the speed of a small amplitude gravity wave (c).

   $$
   c = \sqrt{\frac{g . A}{T}} = \sqrt{g . Y_d}
   $$

   ​	where:

   ​		g - acceleration due to gravity

   ​		A - cross section of the flow

   ​		T - top with of the flow

   ​		$Y_d$ - hydraulic depth $(\frac{A}{T})$
$$
   F (Froude-number) = \frac{V}{c} = \frac{V}{\sqrt{gA/T}}
$$
   

   
   
   4.1. ***SubCritical***
   
   - The effect of downstream changes are noted by the fluid and adjusts in anticipation of downstream occurrences.
   - $F < 1$
   
   4.2. ***Critical***
   
   - $F = 1$
   
   4.3. ***Supercritical***
   
   - The effect of change cannot travel upstream because the velocity exceeds `c`.
   - $F > 1$
   
6. **Reynolds Number ($R_e$)**

   - Ratio of inertia to viscous forces and is used to distinguish whether a flow is laminar or turbulent.

     
     $$
     R_e = \frac{VR_h}{v} = \frac{Q}{vP} = \frac{\rho V R_h}{\mu}
     $$
     where:

     ​	$R_h$ - hydraulic raidus

     ​	$V$ - average velocity of the flow

     ​	$Q$ - volumetric flow rate (discharge)

     ​	$\mu$ - absolute viscosity

     ​	$v$ - kinematic viscosity

   - If $R_e < 500$, the flow is laminar, otherwise, the flow is turbulent.