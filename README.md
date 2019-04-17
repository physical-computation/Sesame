# Sensor-Augmented-SLS
This is the top-level repository for the hardware and firmware of the University of Cambridge Warp hardware platform. Three other repositories, [`Warp-hardware`](https://github.com/physical-computation/Warp-hardware), [`Warp-firmware`](https://github.com/physical-computation/Warp-firmware), and [`Sesame-logger`](https://github.com/physical-computation/Sesame-logger), contain the hardware design for the Warp sensor platform, and the firmware for Warp, and a Python tool for controlling the printer and four sensor groups (the 248-channel spectrometer, the 22-sensor Warp, and the 4-sensor Bosch CISS). These repositories are included here as git submodules.

## Cloning the Repository 
The correct way to clone this repository to get the hardware and firmware submodules is:
```bash
	git clone --recursive git@github.com:physical-computation/Sensor-Augmented-SLS.git
```
To update all submodules
```bash
	git pull --recurse-submodules
	git submodule update --remote --recursive
```
If you forgot to clone with `--recursive`, and end up with empty submodule directories, you can remedy this with
```bash
	git submodule update --init
```

## How We Use GitHub to Track the Construction
We created an "Issue" for each step of the assembly process and we used Issue Labels to tag the steps with information such as whether a step is relevant to a sensor component integration.

## Assembly
The GitHub issues tagged `Mechanical Assembly` contain both instructions for assembly as well as pictures of our actual assembly work. The picture below is a collage of some of the assembly step pictures.

<img width="1184" alt="sesame-assembly" src="https://user-images.githubusercontent.com/86417/56277494-5bd19e00-60fc-11e9-9604-13b1446db845.png">


## How We Use GitHub to Track Measurements and Prints
We created an "Issue Tamplate" to make it easy to initiate a new experiment using the system and to fill in detail about a print and measurement. The `Sesame-logger` tool initiates a print in the SLS machine and at the same time also automatically creates a new GitHub repository to contain the sensor data that results from the print.

## Operation
<img width="1050" alt="sesame-spectrometer-and-external-sensor" src="https://user-images.githubusercontent.com/86417/56277491-5bd19e00-60fc-11e9-8bce-bfee81975c8c.png">
<img width="1177" alt="sesame-chamber-hat-and-spectrometer" src="https://user-images.githubusercontent.com/86417/56277492-5bd19e00-60fc-11e9-860c-b8a5fcda5f2d.png">
<img width="1161" alt="sesame-spectrometer-fiber" src="https://user-images.githubusercontent.com/86417/56277498-5bd19e00-60fc-11e9-9bdd-85cf7afb2185.png">
<img width="1014" alt="sesame-spectrometer-fiber-window" src="https://user-images.githubusercontent.com/86417/56277499-5bd19e00-60fc-11e9-9bf0-fa77b9e34c70.png">

## Acknowledgements
The original assembly team consisted of Rae Zhao, James Rhodes, Vlad-Mihai Mandric, and Phillip Stanley-Marbell. Later stages of the assembly involved Youchao Wang, Andrew Kadis, and Thomas Garry. The spectrometer integration hardware and print automation software was designed and implemented by Thomas Garry.

This research is supported by an Alan Turing Institute award TU/B/000096 under EPSRC grant EP/N510129/1, by Royal Society grant RG170136, and by EPSRC grants EP/P001246/1 and EP/R022534/1.

<img width="830" alt="sesame-credits" src="https://user-images.githubusercontent.com/86417/56280813-e61d0080-6102-11e9-9db4-6b07d1e80715.png">
