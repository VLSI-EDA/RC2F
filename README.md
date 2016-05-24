# Reconfigurable Cloud Computing Framework (RC2F)

[![Documentation Status](https://readthedocs.org/projects/rc2f/badge/?version=latest)](http://rc2f.readthedocs.io/en/latest/?badge=latest)
![Latest tag](https://img.shields.io/github/tag/VLSI-EDA/RC2F.svg?style=flat)
[![Latest release](https://img.shields.io/github/release/VLSI-EDA/RC2F.svg?style=flat)](https://github.com/VLSI-EDA/RC2F/releases)
[![Apache License 2.0](https://img.shields.io/github/license/VLSI-EDA/RC2F.svg?style=flat)](LICENSE.md)


This software is published and maintained by **Chair for VLSI Design, Diagnostics and Architecture** - 
Faculty of Computer Science, Technische Universität Dresden, Germany  
**http://vlsi-eda.inf.tu-dresden.de**

<img src="https://raw.githubusercontent.com/VLSI-EDA/RC2F/master/docs/_static/images/logo_tud.jpg" width="300" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://raw.githubusercontent.com/VLSI-EDA/RC2F/master/docs/_static/images/rc2f_logo.jpg" width="350" />

## 1 Overview

Hardware acceleration using FPGAs in a cloud environment requires, in addition to resource management and user administration, a framework realizing the vFPGA concept and allowing integration of user cores. We therefore provide the RC2F framework which is fully integrated into our RC3E environment and provides high communication throughput using PCIe. The framework is typically used in our RAaaS and BAaaS models.

The main part of the RC2F framework consists of a controller managing the configuration and the user cores as well as the monitoring of status information. The controller's memory space is accessible from the host through the API and on the FPGA via dedicated control signals (full reset, user reset, test loopback, etc.). In- and output-FIFO for streaming  applications providing high throughput and memory interfaces for configuration are provided as user interfaces.

