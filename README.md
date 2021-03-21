<h1 align="center">
	BATTERY MODULE 2 CELLS
	<br>
</h1>

<h4 align="center">Electrical power system battery module 2 cells hardware project.</h4>

<p align="center">
	<a href="https://github.com/spacelab-ufsc/spacelab#versioning">
		<img src="https://img.shields.io/badge/status-in%20suspended-lightgray?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-2c/releases">
		<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/spacelab-ufsc/battery-module-2c?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc//battery-module-2c/releases">
		<img alt="GitHub commits since latest release (by date)" src="https://img.shields.io/github/commits-since/spacelab-ufsc/battery-module-2c/latest?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-2c/commits/master">
		<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/spacelab-ufsc/battery-module-2c?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-2c/issues">
		<img alt="GitHub issues" src="https://img.shields.io/github/issues/spacelab-ufsc/battery-module-2c?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-2c/graphs/contributors">
		<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/spacelab-ufsc/battery-module-2c?color=yellow&style=for-the-badge">
	</a>
	<a href="#license">
		<img src="https://img.shields.io/badge/open--source-project-lightgray?style=for-the-badge">
	</a>
	<a href="https://github.com/spacelab-ufsc/battery-module-2c">
		<img src="https://img.shields.io/badge/heritage-prototype-lightgray?style=for-the-badge">
	</a>
</p>

<p align="center">
  	<a href="#overview">Overview</a> •
  	<a href="#repository-organization">Repository Organizarion</a> •
  	<a href="#license">License</a> •
  	<a href="#releases">Releases</a> •
  	<a href="#notes">Notes</a>
</p>

<!---
<p align="center">
	<img width="45%" src="https://github.com/spacelab-ufsc/battery-module-2c/blob/master/images/bat-pcb-top.png">
	<img width="45%" src="https://github.com/spacelab-ufsc/battery-module-2c/blob/master/images/bat-pcb-bottom.png">
</p>
--->

## Overview

The Battery Module 2 Cells batteries are not on the EPS PCB due to size restrictions. This auxiliary PCB contains the batteries and it is connected to the the EPS PCB using a power header. The Batteries,  [ICR18650-30B](http://gamma.spb.ru/media/pdf/liion-lipolymer-lifepo4-akkumulyatory/ICR18650-30B.pdf), are two lithium-ion connected in series that supply up to 22.2 Wh. The electrical characteristics are displayed in the Table below.

|         Parameter         	| Value 	| Unit 	|
|:-----------------------------:|:-------------:|:-----:|
|      Nominal Capacity     	|  2950 	|  mAh 	|
|      Nominal Voltage      	|  3.78 	|   V  	|
|      Charging Voltage     	|  4.35 	|   V  	|
| Standard Charging Current 	|  1475 	|  mA  	|
| Max. Charging  Current    	|  2950  	|  mA  	|
| Max. Discharging Current  	|  5900  	|  mA  	|
| Discharge cut-off Voltage 	|  2.75  	|  V    |
| Operating Temperature     	|  0-45  	|  ºC   |

The batteries are fixed in the batteries PCB by a 18650 battery holder. Also, a mechanical holder is placed over the batteries and screwed to the board. One heater is placed around each battery.

<!---
## Repository Organization
	- doc: Technical documentation (including firmware, hardware, user guide, and datasheet).
	- hardware: On-board computer module hardware project (sources and outputs).
--->

## License

This project is open-source under CERN Open Hardware License v2.0. Some third-part files and libraries are subjected to their specific terms and licenses.

## Releases
<!---
The Battery Module 2 cells hardware releases are synchronized in order to garantee compatibility. Then, using diferent versions might lead to unpredictable behavior. Refer to the [documentation](https://github.com/spacelab-ufsc/battery-module-2/tree/master/doc) for compatibility notes.
--->
## Notes

More info about the SpaceLab: [GitHub](https://github.com/spacelab-ufsc/spacelab) and [Website](https://spacelab.ufsc.br/en/home/)
