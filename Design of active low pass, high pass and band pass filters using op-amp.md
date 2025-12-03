![WhatsApp Image 2025-12-03 at 22 36 23_d7381766](https://github.com/user-attachments/assets/4b4f21ce-fe76-4b80-8cd0-80938d6232f8)# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS

![WhatsApp Image 2025-12-03 at 22 35 10_057af5d5](https://github.com/user-attachments/assets/c1e8ab2e-20cb-44d4-8f1f-24fb318340e3)

## HIGH-PASS

![WhatsApp Image 2025-12-03 at 22 35 24_b75c5d7b](https://github.com/user-attachments/assets/e359f08e-a14e-4dac-a499-cb6b2d0f607d)

## BAND-PASS

![WhatsApp Image 2025-12-03 at 22 36 08_f4b95bce](https://github.com/user-attachments/assets/23268267-219d-445c-a861-a355849dc6b4)

## MODEL GRAPH:
## LOW_PASS

![WhatsApp Image 2025-12-03 at 22 35 12_20075894](https://github.com/user-attachments/assets/91759119-ba99-4f36-949e-018a4acd0155)

## HIGH-PASS

![WhatsApp Image 2025-12-03 at 22 35 55_52c0dfbb](https://github.com/user-attachments/assets/a8012b5c-baae-4705-9b0e-6fa08d79a657)

## BAND-PASS

![WhatsApp Image 2025-12-03 at 22 36 09_a5c99a65](https://github.com/user-attachments/assets/1c2e8811-6e65-4505-a114-ab25c0b0571f)

## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS

![WhatsApp Image 2025-12-03 at 22 35 17_becdff07](https://github.com/user-attachments/assets/f3ed6729-f5c1-4754-955e-eccf7d965597)

## HIGH-PASS

![WhatsApp Image 2025-12-03 at 22 36 05_a65b5290](https://github.com/user-attachments/assets/6f599031-ed6d-4410-87bc-29946e4dd04a)

## BAND-PASS

![WhatsApp Image 2025-12-03 at 22 36 23_e59a82c8](https://github.com/user-attachments/assets/1dc0ab9f-7da6-4801-afdd-77cce97ad778)

## CALCULATIONS:
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## GRAPH:
## LOW_PASS

![WhatsApp Image 2025-12-03 at 22 36 24_5e1ab7eb](https://github.com/user-attachments/assets/5680365c-3fa7-4b78-8b9b-13c7a871553a)

## HIGH-PASS

![WhatsApp Image 2025-12-03 at 22 36 24_e44e8a07](https://github.com/user-attachments/assets/63248224-e7ba-4706-b271-9dfdd0778f99)

## BAND-PASS

![WhatsApp Image 2025-12-03 at 22 36 10_a567b17b](https://github.com/user-attachments/assets/675f572c-86e7-45b6-8a9b-1fe114c20df6)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

