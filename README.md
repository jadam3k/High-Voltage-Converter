

This is a small, simple high-voltage generator project that demonstrates how to use the MC34063 DC-DC switching regulator. The device works from a +12 V source and employs a buck-boost topology to supply a high-voltage, low-current output (~250 V).

## PCB Status

The PCB has been fully designed and routed. All components have been connected, and the work is done. Everything went smoothly — this was a quick and simple project.

## Essential Components

<table><tbody><tr><td>Reference</td><td>Qty</td><td>Value</td></tr><tr><td>CN1</td><td>1</td><td>+12V/GND/GND/HV</td></tr><tr><td>IC1</td><td>1</td><td>MC34063 SMD</td></tr><tr><td>L1</td><td>1</td><td>180uH</td></tr><tr><td>Q1</td><td>1</td><td>STN3N40K3</td></tr><tr><td>D1</td><td>1</td><td>ES1G-13-F</td></tr><tr><td>C1</td><td>1</td><td>10uF 400V</td></tr><tr><td>C2</td><td>1</td><td>10uF 400V</td></tr><tr><td>Feedback Resistors (R4/R5)</td><td>2</td><td>470K / 47K</td></tr></tbody></table>

## How It Works

- **MC34063** is the component that manages the switching cycle.

 -L1 is the inductor where energy is stored when the MOSFET Q1 is ON, and it is later delivered to the output through diode D1 and capacitor C1 when Q1 is OFF.

- The capacitor C1 serves to even out the voltage of the output.

- The feedback resistors are used to keep the output voltage at the set value (~250 V).

## Images

### Schematic:
<img width="1179" height="548" alt="image" src="https://github.com/user-attachments/assets/c7e5d7e5-f93c-4f01-a164-32c5680ad580" />


### PCB: 
<img width="988" height="610" alt="image" src="https://github.com/user-attachments/assets/d52c9887-cbb2-4bb4-b490-de46dd623d70" />|

### 3D VIEW:
<img width="831" height="520" alt="image" src="https://github.com/user-attachments/assets/e6a15cd5-f423-4c80-95b9-96e1fb96a8cd" />


