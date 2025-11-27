# Tetra_Skin v1.0 README
Based on the famous tetrahedral DCTL https://github.com/npeason/Tetra-DCTLOFX, I have developed a new version for skin tones.

The recent modifications focus on streamlining the interface and enhancing the precision of skin tone manipulation:

Control Isolation: Only the parameters for the Red, Yellow, Magenta, and White vectors have been kept. These axes are sufficient for manipulating the skin tone (Red-Yellow axis). The controls for Green, Cyan, and Blue were hidden to clean up the interface, as they typically do not affect human skin.

Tetrahedral Logic: The exact tetrahedral interpolation mathematics from the original file was retained. This ensures the continued delivery of the same smooth and organic color processing quality.

Skin Keyer (Qualification): A "Qualification" section was added at the beginning. The script now internally generates a mask based on Hue and Saturation. This crucial addition ensures that while the sliders are moved, the effect is applied only to the skin and does not impact other red or yellow objects in the background (such as a wall or a car).
