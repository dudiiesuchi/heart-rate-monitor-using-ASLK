# heart-rate-monitor-using-ASLK



# Heart Rate Monitoring using ASLK

This project demonstrates a simple yet effective **Photoplethysmography (PPG)**-based heart rate monitoring system using **Analog System Lab Kit (ASLK)** and discrete components. It captures and visualizes the PPG signal from a user's finger using a green LED and photodiode setup.


##  Problem Statement

Design a PPG system (TX and RX) to acquire and display clean PPG signals on an oscilloscope using the ASLK.


##  Sensor Setup

* **LED**: Green LED used for illumination.
* **Photodiode**: Reverse biased (0V bias).
* **CTR (Current Transfer Ratio)**:
  
  $$
  \text{CTR} = \frac{I_{PD}}{I_{LED}} = 0.1\% \text{ to } 1\%
  $$

  
* **PI (Perfusion Index)**:
  
  $$
  \text{PI} = \frac{I_{PD,AC}}{I_{PD,DC}} = 0.2\% \text{ to } 2\%
  $$

##  System Specifications

* **LED Current**: 5 mA to 10 mA
* **Signal Bandwidth**: 30 bpm to 240 bpm
* **PPG Signal Amplitude**: > 100 mV (peak to peak)
* **Line Frequency Attenuation**: 40 dB at 50 Hz
* **Output**: Clean PPG waveform on oscilloscope



##  Hardware Used

* Analog System Lab Kit (ASLK)
* Green LED
* IR Photodiode
* Operational Amplifiers (for signal conditioning)
* Oscilloscope



##  Output

The system outputs a clean PPG waveform that corresponds to the user’s heart rate, visible on the oscilloscope. The waveform can be further processed for BPM calculation and digital display in future versions.



##  Future Scope

* BPM calculation circuit integration
* Bluetooth or serial transmission to microcontroller
* OLED display of heart rate
* Integration into wearable systems



##  Diagram
![WhatsApp Image 2025-06-30 at 09 41 07_a0723a79](https://github.com/user-attachments/assets/2dde22fc-5484-4a97-bb46-cb5f74cc5bfc)
![WhatsApp Image 2025-06-30 at 09 41 08_abe0c8a7](https://github.com/user-attachments/assets/9f482c8b-c3d5-48a4-8ac7-81283d35505d)




