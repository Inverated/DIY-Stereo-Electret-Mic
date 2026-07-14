# Stereo Electret Mic

Inspired by MubarakNative [STUDIO-QUALITY ELECTRET MIC PREAMP BUILD](https://mubaraknative.github.io/build_instruction.html).


![Completed](/Final%20Image.jpg)

Modifications made
-
- Use 4 mics in total, 2 left and 2 right for stereo input from the front and back
- Integrated multiturn trimmer potentiometer for fine tuning channel volume
- Added additional decoupling capacitor to the power rails and power rails of the op amp to reduce noise 
- Used a dual 9v power supply instead of a virtual ground using a voltage divider
- Used an OP2134 instead of NE5532 (Or any direct NE5532 should works)

Note
-
- Add some damping material (See photo) to reduce wind sound
- R15 resistor at the output should be increased / tied to a dual potentiometer to adjust the volume. Current 1k value have too much noise. \
(Not an electrical engineer, probably can adjust an RC filter somewhere to filter out the noise before the output. IDK)
- Some capacitor value from the original schematic was changed not because it is better but cause its the closest value i have lying around.