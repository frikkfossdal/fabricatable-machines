
# Rack and Pinion for Fusion360 

## 18.02.2018 Update: Parametric version of the axis
Parametric model of a axis fusion360. Drop it into your model and break the link and it will be added to your timeline. All parameters will be imported.

Designed for 8 mm thick stock for all parts.

![Overview1](./img/iso_with_axis_plate.JPG)
![Overview1](./img/axis.gif)
![](./img/motor_plate.gif)

The rack clearance is wide enought so that the pinion clears the rack teeth when adjusting the glide blocks.

All parts are parametric but I have favourited the most used and most stable parameters, shown below:
![](./img/parameters.jpg)


### TODO:
* Design and test a viper system
* Mill a test axis and try with Nema 24 motors

## Previous versions:

![Overview1](./img/rack_n_pinion.gif)
![Overview2](./img/overview_rolled.jpg)

Standard settings:
* "Standard" 45 mm / revolution pinion 
* Needs a 2 mm mill to machine.

It is Fully parametric and jointed. Use the Master Dimensions sketch to change the control dimensions or how they are calculated.
You can also control it from the parameters window.

![Master Dimensions](./img/master_dimensions.jpg)

To be able to mill the rack with a larger diameter milling bit, experiment with increasing the 
tooth_pos_radius parameter. It needs to be smaller than the main "rolling radius" so I have set it up so that the offset can be tuned.


![Tooth position control dimension](./img/tooth_pos_radius.jpg)
