# signal Journey

## destinations 
- **Code:** Generated as telemetry or data packets from the satellite's onboard computer.
- **Modulation:** Converting binary data into radio-frequency carrier waves for transmission.
- **Transmission:** Pushing the modulated signal through the satellite antenna into space.
- **Atmosphere:** Traveling across free-space path loss and atmospheric interference down to Earth.
- **Ground station:** Rooftop antenna capturing the faint electromagnetic wave.
- **LNA:** Low-Noise Amplifier boosting the weak signal before cable loss.
- **Transceiver:** The indoor radio hardware receiving the tuned frequency signal.
- **Demodulator:** Stripping the carrier frequency to turn the wave back into baseband/audio.
- **Audio cables or direct usb:** Transferring the demodulated baseband data into the computer.
- **Software decoding:** Processing the stream in tools like GNU Radio to turn it back into binary.

## communication modes

| Mode | Transmission Direction | Can You Command It? | Complexity & Mechanics | Rarity for Student Sats |
| :--- | :--- | :--- | :--- | :--- |
| **Simplex** | One-way (Downlink only) | No | Very low; satellite constantly broadcasts beacons without listening. | Common for absolute beginner/hobbyist sats |
| **Half-Duplex** | Two-way (Alternating) | Yes | Medium; shares frequency/hardware, requiring time-switching protocols so transmitter and receiver don't collide. | Very popular for standard university CubeSats |
| **Full-Duplex** | Two-way (Simultaneous) | Yes | High; uses separate frequency bands simultaneously (e.g., VHF uplink, UHF downlink) with robust circuit isolation. | Used in advanced/ISRO-backed missions |
