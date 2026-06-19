# Shuffle the fuck up
![logo](./images/logo.svg)

The card shuffling machine created in this project was made in the last two days of the phycom (Physical Computing) module. The device is inspired by the standard shuffle machine that is sold everywhere.

## Ideation
In the ideation phase we started by thinking about the overall design and which functionality could improve the device. We came up with different designs and improvements. 


### Design
When experimenting with different designs, we came up with around 3-4 different models. All shared similarities but also some small differences. Mostly we were always reminded by the standard design for these shuffle machines.  

![Crazy 8](./images/ideation.jpg)

### Functionality
The extra functionality which we thought of consisted of:
- Automatically turning off when all cards were shuffled, this could be done with 2 LDR on both sides of the device, directly under the cards.
- Counting the shuffled cards, this implementation would be rather difficult to implement.
- Splitting cards and after Splitting shuffling them again, this would also be difficult because we only had 2 motors.
- Distributing the specific number of cards after shuffling, this would also be rather difficult because of the limitation of the motor counts.

![mindmap](./images/mindmap.jpg)

### Naming
Most important thing in ideation is the naming of the overall project, so after many different ideas we came up with a funny and genius name, ´Shuffle the fuck up´ short ´STFU´.

![name](./images/name_logo.jpg)

## Prototyping
In the prototyping process we tried to check if the two motors even have enough power to slide the cards towards the middle so that the shuffling even works. 

![motor_test](./images/motor_test.jpg)

---

With that out the way, we started constructing the overall structure for the device. We used the size of the cards as a means to figure out the measurements.

![meausurements](./images/measurements.jpg)

---

After we had the aproximate measurements. We used the cardboard to get a feeling for the dimensions. And to see where we could route all the cables.

![cardboard_1](./images/cardboard_1.jpg)

![cardboard_2](./images/cardboard_2.jpg)

![cardboard_3](./images/cardboard_3.jpg)

![cardboard_4](./images/cardboard_4.jpg)

![cardboard_5](./images/cardboard_5.jpg)

![cardboard_6](./images/cardboard_6.jpg)

---

The next step was to get a feeling for the wheels that push the cards in the middle. For that we designed a first version and printed them with the 3d printer.

![wheels_1](./images/wheels_1.jpg)

![wheels_2](./images/wheels_2.jpg)

---

The Cardboard prototype was used to also fit the wheels and try the functionality for the first time.

![wheels_fitting_1](./images/wheels_fitting_1.jpg)

![wheels_fitting_2](./images/wheels_fitting_2.jpg)

![wheels_fitting_3](./images/wheels_fitting_3.jpg)


## 3D Modelling
After getting all the measurements and seeing the prototype with cardboard we began to model the overall structure for the 3d-print.

![modell_1](./images/modelling_1.jpg)

![modell_2](./images/modelling_2.jpg)

---

With some time tinkering around we got the final model ready for printing.

[Modells](./modells/)

## Construction

The print was finally finished and we had to connect it the first time.

![print_1](./images/print_1.jpg)

![print_2](./images/print_2.jpg)

![print_3](./images/print_3.jpg)

![print_4](./images/print_4.jpg)

---

To improve the overall style we added a 3d-printed logo on the side.

![logo_side](./images/logo_plate.jpg)

---

Now we just had to create a structure to hold the wheels in place. For that we designed another structure that should hold the wheels in the box.

[motor_holder](./modells/motor_holder.stl)

---
In that process we realised that we had to increase the size of the wheels. so that they had more contact with the cards. We also used TPU instead of PLA so we get more grip.

![TPU_wheel_1](./images/TPU_wheel_1.jpg)

![TPU_wheel_2](./images/TPU_wheel_2.jpg)

--- 

After printing and trying to put it together we had to remove some parts of the backplate so that the box holds better together, also because the small pins broke off very quickly we improved with some m3 thread.

![backplate_improvisation](./images/improvisation_1.jpg)

![m3_improvisation](./images/improvisation_2.jpg)

---

Next step was to connect all the cables and assemble the device with the interior components.

![assemble_1](./images/assemble_1.jpg)

![assemble_2](./images/assemble_2.jpg)

![assemble_3](./images/assemble_3.jpg)

--- 

The complete device:

![finished_part_1](./images/finished_1.jpg)
![finished_part_2](./images/finished_2.jpg)

## Issues
The angle for the cards is propably not enough, because the card get stuck, so it needs a bit more time to tinker aroung.


## Parts

- Shuffler main structure
- Shuffler backplate
- 4x Shuffler motor holder
- 2x Shuffler top limiter
- 2x motors
- 4x TPU wheels
- Battery
- Button
- cables

## Assembly Instructions
To put the STFU shuffler together, follow these steps:

1) **Wheel Preparation:** Press the 4x TPU wheels onto the shafts of the 2x motors (two wheels per motor).

2) **Motor Mounting:** Place the motors into their designated slots inside the main shuffler structure. Secure them in place using the 4x motor holders.

3) **Wiring the Circuit:** Route the cables through the interior channels.
    - Wire the button in series with the battery pack.

    - Wire the two motors in parallel to the switch, ensuring the polarity is set so that both motors spin inward toward the center of the device when activated.

4) **Card Limiters:** Install the 2x top limiters above the card bays to ensure only a few cards can slide through at a time.

5) **Closing the Chassis:** Align the backplate with the main structure. Secure it using M3 screws into the threaded holes to ensure a tight, durable fit.
