# K/Ka-Band SATCOM Orthomode Transducer (OMT)

## Overview

This design presents a multi-port Orthomode Transducer (OMT) developed and analyzed using CST Studio Suite for satellite communication applications.

The OMT consists of one common port, two transmit (TX) ports and one receive (RX) port. The transmit channels operate over the Ka-band frequency range from 27.5 GHz to 31 GHz, while the receive channel operates over the K-band frequency range from 17.7 GHz to 21.2 GHz.

The two TX ports are implemented using WR28 rectangular waveguide interfaces, while the RX port uses a WR42 rectangular waveguide interface. The common port combines the orthogonal polarization components and provides the shared RF interface of the structure.

## Key Features

- **Simulation Tool:** CST Studio Suite
- **Component Type:** Orthomode Transducer (OMT)
- **Application:** SATCOM
- **Number of Ports:** 4
- **TX Ports:** 2
- **RX Ports:** 1
- **TX Frequency Range:** 27.5–31 GHz
- **RX Frequency Range:** 17.7–21.2 GHz
- **TX Port Standard:** WR28
- **RX Port Standard:** WR42

## OMT Geometry

<table>
<tr>
<td align="center">
  <img src="OMT_geometry1.png" width="100%">
</td>
<td align="center">
  <img src="OMT_geometry2.png" width="100%">
</td>
</tr>
</table>

## Return Loss

### Ka-Band Horizontal Port Return Loss

<img src="Ka_Horizontal_Port_Return_Loss.png" width="100%">

### Ka-Band Vertical Port Return Loss

<img src="Ka_Vertical_Port_Return_Loss.png" width="100%">

### K-Band Horizontal Port Return Loss

<img src="K_Horizontal_Return_Loss.png" width="100%">

### Common Port Return Loss

<img src="Common_Port_Return_Loss.png" width="100%">

## Insertion Loss

### Ka-Band Horizontal Port to Common Port

<img src="InsertionLoss_KaHorizontalPort_to_CommonPort.png" width="100%">

### Ka-Band Vertical Port to Common Port

<img src="InsertionLoss_KaVerticalPort_to_CommonPort.png" width="100%">

## Isolation

### Isolation Between K-Band Horizontal and Ka-Band Vertical Ports

<img src="Isolation_Between_K-Horizontal and Ka-Vertical.png" width="100%">

### Isolation Between Ka-Band Vertical and Ka-Band Horizontal Ports

<img src="Isolation_Between_Ka-Vertical and Ka-Horizontal.png" width="100%">
