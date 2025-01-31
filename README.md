# Fettuccine-Alfredo
very basic and cheap constant current circuit for medium power LED's

This project is about to design a very simple LED driver circuit for medium power LED's. I'd like to play around with different LED color temperatures and shapes. 

# Simulations and Schematics
![circuit](./Images/SpiceResults3.png)
![circuit](./Images/SpiceResults1.png)
![circuit](./Images/SpiceResults2.png)
![circuit](./Images/Schematic1.png)

# Adjusting Current
```math
I_{LED} \approx I_{R_S} = \frac{U_{D} - U_{BE}}{R_S}  
```

```math
I_{LED} = \frac{1.8 V - 0.7 V}{100 \Omega} = 11mA  
```

## Revision 0 uses PLCC 2835 LED Footprint and 3528 (alternative)
![rev 0.1](./Images/CC_LED_Driver_rev_01.png)

## Revision 1 uses 3528 Footprint only
![rev 0.1](./Images/CC_LED_Driver_rev_10.png)

# Real World Examples
## Lamp
I used the [timer clock project](https://github.com/LMWB/Cannelloni-al-Forno) and three of this LED boards to create a illumination of my courtyard.  
![Garage Light](Images/IMG_7542.jpg)  
![Garage Light](Images/IMG_7544.jpg)  
![Garage Light](Images/IMG_7546.jpg)  

## Star


# Sources
## Material
high performance power LED found on ebay  
![LED warm white](Images/led-ebay.PNG)
