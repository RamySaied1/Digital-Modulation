# Digital-Modulation
CUFE 2020 - CMP - Digital Communication Project - Third Year semester
in this project we will simulate different digital modulation methods.
## BPSK ( binary phase shift keying)
Phase Shift Keying (PSK) is the digital modulation technique in which the phase of the carrier signal is changed by varying the sine and cosine inputs at a particular time. PSK technique is widely used for wireless LANs, bio-metric, contactless operations, along with RFID and Bluetooth communications.
Binary Phase Shift Keying (BPSK) is also called as 2-phase PSK or Phase Reversal Keying. In this technique, the sine wave carrier takes two phase reversals such as 0° and 180°.
BPSK is basically a Double Side Band Suppressed Carrier (DSBSC) modulation scheme, for message being the digital information.
![BPSK](BPSK/bspk_modulated_output_wave.jpg)
### Gemotrical representation 
We know that BPSK signal carries the information about two symbols. These symbols are symbol ‘1’ and symbol ‘0’. We can represent BPSK signal geometrically to show these two symbols. We know that BPSK signal is expressed as,s(t)=b(t)v2Pcos(2pfct)
on rearranging the equation, s(t)=b(t)vPTb.(v2/Tb) cos(2pfct)
now, let ?1(t)= (v2/Tb) cos(2pfct) represents an orthonormal carrier signal.
let Now Eb=PTb Therefore, s(t)= ±vEb?1(t) 
![BPSK](BPSK/Before_Channel_Signal.png)