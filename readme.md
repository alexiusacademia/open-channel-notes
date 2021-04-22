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

7. **Basic Fluid Mechanics**

   - The application of fluid mechanics involves thorough understanding of the following:
     - Physical properties of fluids
     - Conservation of mass (continuity principle)
     - Conservation of energy
     - Utilization of momentum fluxes as vector quantities

8. **Physical Properties of Fluids**

   - Density $\rho = \frac{mass}{volume}$

   - Specific weight $\gamma = \rho g$, where $g$ is the acceleration due to gravity.

     - related to density through Newton's second law of motion,

       $Force = Mass \times Acceleration$

     - Weight is a force due to resisting gravity

     - More precision for gravity, $g = 9.80685 \space m/s^2$

   - The weight of a fluid causes pressure to increase with depth
     $$
     \frac{dp}{dz} = -\gamma = -\rho g
     $$
     assuming there is no motion in the fluid.

   - If the fluid is incompressible, equation (5) integrates to:
     $$
     p_2 - p_1 = \gamma (z_2 - z_1) = \rho g (z_2 - z_1)
     $$
     

9. **Conservation of Mass / Continuity Equation**

   Simplified, quantity of fluid passing through point 1 equals quantity of fluid passing through point 2;
   $$
   A_1 V_1 = A_2 V_2
   $$
   or if there is an inflow in between,
   $$
   (\rho VA)_2 = (\rho VA)_1 + (\rho VA)_1-_2
   $$

   $$
   (VA)_2 = (VA)_1 + \int q(x) dx
   $$

   where:

   ​	$q(x)$ - is the lateral inflow (negative for lateral outflow)

   

   When dealing with two or three dimensional flow, the continuity equation becomes partial differential equation:
   $$
   \frac{\part (\rho u)}{\part x} + \frac{\part (\rho v)}{\part y} + \frac{\part (\rho w)}{\part z} = -\frac{\part (\rho)}{\part t}
   $$
   where:

   ​	$u$, $v$ and $w$ are the velocity components in the x, y and z directions.

    For an incompressible fluids, equation (10) reduces to:
   $$
   \frac{\part u}{\part x} + \frac{\part v}{\part y} + \frac{\part w}{\part z} = 0
   $$
   