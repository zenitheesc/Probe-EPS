<h1 align="center" style="color:white; background-color:black">Probe-EPS</h1>
<h4 align="center">Eletrical power system for stratospheric probes, using Zenith Stack</h4>

<p align="center">
	<a href="http://zenith.eesc.usp.br/">
    <img src="https://img.shields.io/badge/Zenith-Embarcados-black?style=for-the-badge"/>
    </a>
    <a href="https://eesc.usp.br/">
    <img src="https://img.shields.io/badge/Linked%20to-EESC--USP-black?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/zenitheesc/Probe-EPS?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/issues">
    <img src="https://img.shields.io/github/issues/zenitheesc/Probe-EPS?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/commits/main">
    <img src="https://img.shields.io/github/commit-activity/m/zenitheesc/Probe-EPS?style=for-the-badge">
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/zenitheesc/Probe-EPS?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/commits/main">
    <img src="https://img.shields.io/github/last-commit/zenitheesc/Probe-EPS?style=for-the-badge"/>
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/issues">
    <img src="https://img.shields.io/github/issues-raw/zenitheesc/Probe-EPS?style=for-the-badge" />
    </a>
    <a href="https://github.com/zenitheesc/new-zenith-template/pulls">
    <img src = "https://img.shields.io/github/issues-pr-raw/zenitheesc/Probe-EPS?style=for-the-badge">
    </a>
</p>

<p align="center">
    <a href="#environment-and-tools">Environment and Tools</a> •
    <a href="#z-hub">Z-Hub</a> •
    <a href="#aroca-(battery)-eps">Aroca (Battery) EPS</a> •
    <a href="#london-(power)-eps">London (Power) EPS</a>
</p>

This configuration of the Eletrical power system requires a board that monitors the charger and battery, in addition to performing thermal control.

## Environment and tools

This system was designed using Eagle v.9.4.2

## Z-Hub

<p align = "center">
<img src="https://github.com/zenitheesc/Probe-EPS/blob/main/Images/Z-Hub.png"/>
</p>

<a href="https://github.com/zenitheesc/Probe-EPS/tree/main/Hardware/Aroca_EPS-v.2.0"><h2>Aroca (Battery) EPS</h2></a>

<p align = "center">
<img src="https://github.com/zenitheesc/Probe-EPS/blob/main/Images/Aroca.png"/>
</p>

This subsystem is primarily responsible for the active thermal control of the batteries, in addition to supporting battery monitoring and load balancing

<a href="https://github.com/zenitheesc/Probe-EPS/tree/main/Hardware/London_EPS-v.2.0"><h2>London (Power) EPS</h2></a>

<p align = "center">
<img src="https://github.com/zenitheesc/Probe-EPS/blob/main/Images/London.png"/>
</p>

Functioning as an extension of the previous subsystem, it performs conversions of battery voltage levels to the levels requested within the hardware, making the necessary distribution, as well as controlling the loading of batteries through solar panels.

---

<p align="center">
    <a href="http://zenith.eesc.usp.br">
    <img src="https://img.shields.io/badge/Check%20out-Zenith's Oficial Website-black?style=for-the-badge" />
    </a> 
    <a href="https://www.facebook.com/zenitheesc">
    <img src="https://img.shields.io/badge/Like%20us%20on-facebook-blue?style=for-the-badge"/>
    </a> 
    <a href="https://www.instagram.com/zenith_eesc/">
    <img src="https://img.shields.io/badge/Follow%20us%20on-Instagram-red?style=for-the-badge"/>
    </a>

</p>
<p align = "center">
<a href="zenith.eesc@gmail.com">zenith.eesc@gmail.com</a>
</p>
