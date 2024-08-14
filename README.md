# Colpitts Oscillator and Amplitude Modulation

This project focuses on the design, simulation, and construction of a Colpitts Oscillator, followed by its application in amplitude modulation and demodulation.

## Part 1: Colpitts Oscillator

### Objective
To design, simulate, and construct a Colpitts Oscillator capable of generating stable and tunable sinusoidal oscillations within a specified frequency range.

### Key Components
- Non-ideal amplifier (transistor-based)
- LC oscillation circuit
- Common Emitter Transistor configuration

### Design Considerations
1. **Frequency of Oscillation:** 
   \[
   \omega = \sqrt{\frac{C_1 + C_2}{C_1 C_2 L_3}}
   \]
2. **Gain of the Oscillator:** 
   \[
   A_1 = -\frac{C_1}{C_2}
   \]

### Implementation
- Designed circuit using \(C_1 = C_2 = 1 \text{ nF}\) and \(L_3 = 5 \text{ μH}\)
- **Expected frequency:** 3.2847 MHz
- **Simulated frequency:** 3.7 MHz
- **Hardware (DSO) frequency:** 3.83 MHz

### Challenges
1. Circuit sensitivity to capacitor values
2. Initial oversight of Radio Frequency Choke (RFC)

## Part 2: Application - Amplitude Modulation

### Switching Modulation
Implemented a switching modulator circuit for amplitude modulation.

### Demodulation
Used a low-pass filter to demodulate the amplitude modulated signal.

### Results
- Successfully modulated and demodulated various signals:
  - 10 kHz sinusoidal wave
  - 10 kHz ramp signal
  - 10 kHz square wave

## Advantages of Colpitts Oscillator
1. High-frequency sinusoidal signal generation
2. Simple and easy implementation
3. Temperature resilience
4. High frequency stability
5. Purer sinusoidal waveform

## Challenges Faced
1. Limited range of inductor values
2. Difficulty in generating low-frequency sine waves
3. Limitations of electronic devices at high frequencies

## Conclusion
The Colpitts Oscillator proves to be a versatile and reliable circuit for generating high-frequency signals, with practical applications in RF communication, clock generation, and audio oscillators.
