# Voice_Processing_Project

**Introduction**  
This project focuses on transmitting and processing audio signals using Double Sideband Suppressed Carrier (DSBSC) modulation. The aim is to demonstrate the modulation and demodulation processes, including the effects of noise on the signal at the receiver end. This project is designed to deepen the understanding of modulation techniques and their practical applications in audio signal processing.

**Blocks Used and Their Importance**  
- **Multimedia Block**: This block is the source of the audio signal, providing the 1024-sample input for modulation. It serves as the starting point of the signal-processing chain.
- **Carrier Signal (Sine Wave)**: A sine wave is used as the carrier for DSBSC modulation. The carrier signal is crucial as it determines the frequency at which the audio signal is transmitted.
- **Multiplier**: The multiplier is responsible for combining the audio signal with the carrier signal, thereby generating the DSBSC-modulated signal. This block is essential for the modulation process.
- **Band-Pass Filter (BPF) and Low-Pass Filter (LPF)**: These filters are applied to remove unwanted frequencies and ensure that the signal remains within the desired frequency band during transmission and reception.
- **Spectrum Analyzers**: A series of spectrum analyzers are employed to visualize the signal's frequency components at various stages. These analyzers include tools for measuring power, frequency distribution, and the effects of noise on the signal.
- **Noise Block**: Noise is introduced at the receiver to simulate real-world conditions, making the analysis more realistic and comprehensive.

**Idea of the Project**  
The primary objective of this project is to illustrate the process of audio transmission using DSBSC modulation, a technique known for its efficiency in bandwidth usage and energy conservation. By introducing noise at the receiver, the project also aims to provide a realistic scenario where the robustness of the modulation scheme can be analyzed. The use of various blocks, including filters and spectrum analyzers, is designed to give a comprehensive understanding of the signal's journey from transmission to reception.

**Procedure**  
1. **Signal Source**: Start with a 1024-sample audio signal from the Multimedia Block.
2. **Modulation**: Use a sine wave as the carrier and apply DSBSC modulation using the Multiplier block.
3. **Filtering**: Apply Band-Pass and Low-Pass Filters to refine the signal and remove unwanted frequencies.
4. **Spectrum Analysis**: Utilize various spectrum analyzers to visualize and analyze the signal's frequency components throughout the process.
5. **Noise Addition**: Introduce noise at the receiver to simulate real-world conditions and observe its effect on the signal.
6. **Signal Analysis**: Plot the signal graph and spectrum at the receiver to understand the impact of noise and the effectiveness of the filtering.

**Results**  
- The project successfully demonstrates the transmission of an audio signal using DSBSC modulation.
- Spectrum analysis shows how the signal's frequency components evolve through modulation, filtering, and noise addition.
- The Band-Pass and Low-Pass Filters effectively remove unwanted frequencies, improving signal clarity.
- Noise addition at the receiver reveals the impact of real-world conditions on signal integrity, highlighting areas for improvement in the modulation and filtering process.

**Conclusion**  
- DSBSC modulation is effective in transmitting audio signals with efficient bandwidth usage.
- Proper filtering is crucial for maintaining signal quality and reducing noise effects.
- The project provides valuable insights into the practical challenges of audio signal processing and the effectiveness of different techniques in mitigating noise.
- Future work could explore advanced noise reduction strategies and the application of different modulation schemes to further enhance signal robustness.
