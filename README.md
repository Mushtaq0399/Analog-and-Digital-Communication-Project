# Amplitude Shift Keying Generation Using Bipolar Junction Transitors

## Study on Analog and Digital Communications and VLSI

Software: Multisim

Hardware: ELVIS Measurements

## About 

Amplitude shift keying - ASK - in the context of digital communications is a modulation process, which imparts to a sinusoid two or more discrete amplitude levels. 
These are related to the number of levels adopted by the digital message. For a binary message sequence there are two levels, one of which is typically zero. Thus the modulated waveform consists of bursts of a sinusoid.

Figure 1 illustrates a binary ASK signal (lower), together with the binary sequence which initiated it (upper). Neither signal has been bandlimited. 

![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/9288c15b-1aa9-4a43-91d0-f4d3a18f2b70)

Two main componens:

- Modulator

The ASK modulator block diagram comprises of the carrier signal generator, the binary sequence from the message signal and the band- limited filter. Following is the block diagram of the ASK Modulator.

![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/c9caad31-42dc-4690-a51f-65944a73efac)

The carrier generator, sends a continuous high-frequency carrier. The binary sequence from the message signal makes the unipolar input to be either High or Low. The high signal closes the switch, allowing a carrier wave. Hence, the output will be the carrier signal at high input. When
 
there is low input, the switch opens, allowing no voltage to appear. Hence, the output will be low.
The band-limiting filter, shapes the pulse depending upon the amplitude and phase characteristics of the band-limiting filter or the pulse-shaping filter.

- Demodulator

  1. Asynchronus

     The Asynchronous ASK detector consists of a half-wave rectifier, a low pass filter, and a comparator. Following is the block diagram for the same.
     The modulated ASK signal is given to the half-wave rectifier, which delivers a positive half output. The low pass filter suppresses the higher
     frequencies and gives an envelope detected output from which the comparator delivers a digital output.

     ![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/3479dd5c-1862-478a-aef6-0d4ddf6728a3)

  2. Synchronous

     Synchronous ASK detector consists of a Square law detector, low pass filter, a comparator, and a voltage limiter. Following is the block diagram for the same.

     ![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/140415db-3767-4a1c-8c0e-cb5f285c0b6a)

     The ASK modulated input signal is given to the Square law detector. A square law detector is one whose output voltage is proportional to the square of the amplitude modulated input voltage.
     The low pass filter minimizes the highe frequencies. The comparator and the voltage limiter help to get a clean digital output.

## Implemenataion

![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/6ea437de-e0ea-4804-834a-40ad646e4b43)

Outcome: We have some disadvantages, we can further go to FSk. But ASK can be generated through passing sinusoidal signal with unipolar binary sequence. 
While ASK can be demodulated through passing modulated signal with rectifier, LPF and comparator then the signal we get will be the message signal which we have given. 
Demodulation can be done through two methods, Asynchronous and synchronous. Like this the signal can be modulated and demodulated using ASK.

![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/67ed0136-29ff-4880-8b99-b31148b4d13f)

![image](https://github.com/Mushtaq0399/Analog-and-Digital-Communication-Project/assets/139509924/d556be13-9ac5-4535-812f-6b0c536ea204)



Author of this project: 
- [Mushtaq Hussain Shaik](https://www.linkedin.com/in/mushtaqhussainshaik/)
