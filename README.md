# Build Log 
Day #1 10/15
The main issue in the circuit topology of the Plasma Entropy Source V.1 was the anode; where 200Vdc , 10kvac and the decoupling capacitors all met. The 200Vdc took the path of less impedance and traveled through the 10kv strike line instead of through the tube. 
To combat this issue, I decided to redesign the power supply essentially. Instead of these three components meeting at one node, I removed the 10kv strike voltage and opted for ionization by induction instead. 
I put the tube inside of an aluminum spring and connected one end of the 10kv supply output to it. 
I got the positive column fully extended but the tube won't sustain on solely DC yet. 

Day #2 10/17
I started working on the power supply. It's imperative to this project I minimize electrical noise, so I'm avoiding switching power supply's and am instead using a transformer I found in an old radio receiver. I need two or three 12Vdc and one 6vdc. In order to filter mains ripples out, I put one 7500uf or 8500uf capacitor per output of halfwave rectifier. As predicted the ripples are 120hz post rectification. For whatever reason I noticed some higher frequency noise as well on my oscilloscope , the VPP in the mV so noise of relatively low amplitude. I added linear regulators (L78012) and .1uF and 100uF on the ouput , now the noise is no more.

