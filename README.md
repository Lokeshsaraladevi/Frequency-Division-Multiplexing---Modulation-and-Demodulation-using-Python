![WhatsApp Image 2026-04-10 at 7 08 24 AM](https://github.com/user-attachments/assets/fd87c1ea-1cfc-472d-aa01-ade935943e40)
![WhatsApp Image 2026-04-10 at 7 08 25 A](https://github.com/user-attachments/assets/6e0c9dcf-ef84-4e65-bf00-266bc1ddbd6b)
# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Program__ :
![WhatsApp Image 2026-04-10 at 7 08 24 AM](https://github.com/user-attachments/assets/9a751ac9-5735-4e99-af89-d0eefe4d2223)
![lk](https://github.com/user-attachments/assets/ae2c5a6e-89a9-4752-bda3-03a8a538a5f4)


__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

__Tabulation__ :
![WhatsApp Image 2026-04-10 at 7 08 28 AM](https://github.com/user-attachments/assets/b1c3c6ad-128a-470c-a386-01eb4b9729c7)

__Output__:

![WhatsApp Image 2026-04-10 at 7 08 25 A](https://github.com/user-attachments/assets/c651ceb6-ab74-45c7-8fdf-d3f1464c3dd1)
![lm](https://github.com/user-attachments/assets/923b95b6-d7d0-4247-b522-e5e372de80f2)

__Result__:

![45](https://github.com/user-attachments/assets/0dbb9b78-1095-4339-8641-3b94f39e4c3f)
