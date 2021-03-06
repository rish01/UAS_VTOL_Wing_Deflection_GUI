# Unmanned Aircraft Systems - VTOL Wing Deflection GUI

The purpose of this GUI is to determine the maximum deflection of the carbon fiber boom, which is present inside the wing of UAS VTOL aircraft, during flight. In addition, it allows the user to quickly visualize the deflection of the boom along its length given fixed inputs. I created this GUI using MATLAB's App Designer.


## Computation of Deflection

I created a FBD of the carbon fiber boom (assuming one of the ends is fixed) and used Castigliano's theorem to determine the deflection along the length of the boom. Following are the inputs into the model:
1. Total mass of airframe [kg]
2. Total mass of components mounted on wings [kg]
3. Distance of center of mass of components from fuselage's center [m]
4. Total length of wing's carbon fiber (CF) boom [m]
5. Wing's CF Boom's Outer Radius [mm]
6. Wing's CF Boom's Inner Radius [mm]
7. Max Number of Gs of Acceleration in flight 

<img src = "https://github.com/rish01/UAS_VTOL_Wing_Deflection_GUI/blob/master/imgs/deflection_computation_fbd.png" width = 600>

<br/>

## GUI

Following is a screenshot of the GUI:

<img src = "https://github.com/rish01/UAS_VTOL_Wing_Deflection_GUI/blob/master/imgs/GUI_screenshot.png" width = 800>
