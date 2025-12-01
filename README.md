# EX.NO: 2 – Verification of Fiber Losses

## Aim:
To measure propagation and bending losses for two wavelengths in plastic fiber.

## Equipments Required:
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

## Theory:  
Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km. Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.
<img width="815" height="431" alt="513074558-ef4632d0-e2dd-4b03-ae63-f571fafe3337" src="https://github.com/user-attachments/assets/f86140d5-74c7-40c7-854b-ff4ff3a2b244" />


## Procedure:
1. Connect the power supply with proper polarity to the kit link-B and switch it on.
2. Keep all Switch Faults in OFF position.
3. Keep switch SW8 towards TX position.
4. Keep switch SW9 towards TX1 position.
5. Keep Jumper JP5 towards +12V position.
6. Keep Jumpers JP6, JP9, JP10 shorted.
7. Keep Jumper JP8 towards sine position.
8. Keep Intensity control pot P2 towards minimum position.
9. Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer. 
<img width="743" height="301" alt="517679235-e72fbc49-0624-4b15-a4d4-65f39f04196d" src="https://github.com/user-attachments/assets/46b40c6d-6daf-45d4-8602-442136f97851" />

10. Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
11. Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
12. Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
13. Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.
<img width="716" height="294" alt="517679288-72fea700-a99c-41ed-9dfa-e3bb04be70d8" src="https://github.com/user-attachments/assets/31b09863-0179-4188-a122-b7b671005ecb" />
14. Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
15. Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
 <img width="696" height="286" alt="517679313-01ee210d-f880-4ee7-b18f-95b9a5679aed" src="https://github.com/user-attachments/assets/14fb86df-d56a-4e25-934b-2adb6f01cad6" />
16.  If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
17. Where a = nepers/ Meter L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm

18. Keep switch SW9 towards TX2 position.
19. Keep Jumper JP7 towards +12V position.
20. Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
21. Observe the detected signal at post ANALOG OUT on oscilloscope.
<img width="829" height="342" alt="517679348-0ac9a0a2-7c28-4a01-9ffd-ff0f907fac57" src="https://github.com/user-attachments/assets/084ba202-d13c-4322-8d33-580f990d095b" />

22. Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
23. Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
24. If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ] Where a = nepers/ Meter L1 = Fiber Length for V1 ; L2 = Fiber Length for V2 This a is for peak wavelength of 950nm
25. Compare the two a values.
## MEASUREMENT OF BENDING LOSSES:

26. Remove fiber cable from SFH450V (950nm) & SFH350V and insert one meter fiber between SFH756V (660nm) & SFH350V.
27. Bend the Fiber in a loop. Measure the amplitude of the received signal.
28. Keep reducing the diameter of bend to about 2 cm & take corresponding out voltage readings. (Do not reduce loop diameter less than 1 cm).
29. Plot a graph of the received signal amplitude versus the loop diameter.
## Tabulation:

### Propagation Loss:

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|        1     |       5             |           10           |
|        0.5   |       5             |           14           |

### Bending Loss:

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
| 1 for 8cm        |        5            |             10.3       |
| 0.5 for 6.4 cm   |        5            |             9.76       |
  


## Calulation:

![WhatsApp Image 2025-11-16 at 23 43 32_d3d4cfae](https://github.com/user-attachments/assets/e62037df-131a-4d74-aab8-248f92bbd588)


## Result:
- The experiment successfully verified the losses in a fiber-optic link:

- The propagation (transmission) loss was measured over different lengths of the fiber for two wavelengths (660 nm & 950 nm) and found to increase with length, confirming the expected attenuation behaviour.

- The bending loss was observed by varying the loop diameter of the fiber and measuring output amplitude — as the bend diameter decreased, the output dropped, verifying increased bending loss.

- Hence, the aim of measuring both propagation loss and bending loss characteristics of the fiber was achieved.

---
