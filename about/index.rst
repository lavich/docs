.. freejoy documentation master file, created by
   sphinx-quickstart on Sat Mar  7 14:26:05 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Описание проекта
===================================

.. toctree::
   :maxdepth: 1
   :caption: Оглавление:

Features
--------

FreeJoy supports the following external periphery:

* 8 analog inputs
* 128 push buttons or toggle switches
* 4 POV hats
* 16 Incremental encoders
* Converting analog inputs to buttons (up to 12 buttons per axis)
* Shift registers 74HC165 and CD4021 for extending inpits number
* TLE5010/TLE5011 sensors as axes sources

Axes
----
FreeJoy supports up to 8 analog inputs at pins A0-A7 and TLE5010/5011 sensors as axes sources. Every axis has its ouw settings as:

* Source/destination (X, Y, Z, Rx, Ry, Rz, Slider1, Slider2)
* Output enabling/disabling
* Resolution
* Calibration (manual or automatical)
* Smothing (4 levels of filtration)
* Inversion
* Dead zone
* Magnet offset option
* Curve shaping
* Functions for combined axes
* Axes from buttons/encoders

Buttons
-------
FreeJoy allows you to connect up to 128 digital inputs as single inputs (tied to VCC or GND), matrix of buttons, shift register inputs and axes to buttons inputs. Inputs can be configured as:

* Regular push button
* Inverted push button
* Toggle switch ON/OFF
* Toggle switch ON
* Toggle switch OFF
* POV hat button
* Incremental encoder input
* Radio buttons
* 5 shifts

Exrenal configuration tool
-----------------------------

FreeJoy configuration is possible both by changing definitions in source code and by using external [utility](https://github.com/vostrenkov/FreeJoyConfigurator).

<img src="https://b.radikal.ru/b12/2001/56/821d02d9e447.png" width="500"/>

For information how to configure your device check [wiki page](https://github.com/vostrenkov/FreeJoy/wiki)