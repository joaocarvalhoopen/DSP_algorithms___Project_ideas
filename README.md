# DSP algorithms - Project ideas

Some time ago I made a list of some cool project ideas that can be made with DSP algorithms, there are not new, but they are aggregated here under the some list. My hope is to inspire others, maybe  students that are learning DSP, transmit them that this theory and the practical algorithms that came with the theory have many really cool applications. Many of those projects can also be implemented with deep learning technics.

## Example of projects:

1. Detect the voice of a child, a women or a men (FFT - segment on different range of frequencies).

2. Detect the frequency of a sound, How a guitar tuner works, with auto-correlation, comparing between zero crossing, auto correlation and FFT approaches.

3. Detect whistles, and different kind and sequence of whistles.

4. How to detect a sound, or the similarity of a sound to a pre-recorded sound with Dynamic Time Warp algorithm (DTW).

5. How the generation of speech works, vocoders.

6. How the recognition of speech works (with markov Hidden Models and with Deep Learning).

7. How the cocktail party problem is solved and see the simples static case with ICA - Independent Component Analysis algorithm.

8. How SETI detects faint periodic signals, that are below de SNR. Or how the Voyager 1 signals can be received on earth, and sended to voyager 1. How the algorithms behind WSPR (Weak Signal Propagation Reporter) work.  

9. Detect the direction of the most powerful sound or impulse,like a shoot or to track a quadricopter only by it’s sound.

10. How can you generate the sound of an instrument, like a guitar or a trumpet (Karplus strong).

11. Directional Sound Bar (how to make phased arrays or beam forming).

12. How phased array of microphones works, and how to make a directional microphone, that without motors to move it’s direction.

13. Acoustic Radar in 1D.

14. Acoustic Radar in 2D and 3D (the 2D version can be made with a 20 dollar usb external card like Behringer UCA 222 USB Audio Interface, that has 2 inputs and 2 outputs).

15. Acoustic Camera ( Can be made using two usb sound cards  Behringer UCA 222 USB).

16. How to compress an image with wavelets.

17. How to make the sound recording go faster in preview mode, without altering the pitch of the voice.

18. How the the DSP of a ultrasound array of a ecography works, to detect different kind of biological material.

19. how to make a 3d Scanner just with sound, microphones and speaker.

20. How an acoustic spot light works (explaining the demodulation at high sound pressures).

21. Explaining how to make a radar with Doppler Effect to measure the velocity.

22. Explaining how to detect an event in a time series like the stock marker with wavelets, typical of an imminent buy or sell moment, with old financial data from yahoo site.

23. Explaining a little bit why statistics is important in DSP, for signal estimation and detection.

24. How to make a AM or FM radio receiver with just a low frequency microcontroller, using an band pass filter and careful  aliasing sample frequency.

25. How to extend the range of a text radio emitter/receiver by repeating the message many times.

26. How modulation works, and how can you do it.

27. How Shazam works, how can you in a simple way identify every music in the world with a simple 15 seconds snippet.

28. How to have more bit’s of resolution from an ADC using multiple samples.

29. Detect the position of the touch on a table based on the triangulation of the signal to 3 piezo. Virtual Keyboard.

30. Determine the position of a person in a room based on triangulation of the steps with some piezos or directly with sound.  

31. Determine the velocity of a car based only on the Doppler effect when it passes perpendicular to a road side person. Android Phone/FFT.

32. Measure the heart rate with a piezo or a accelerometer on a phone that is taped to the arm.

33. Measure the heart rate with a camera and a band pass filter on the change of color in the pixels of the image (MIT).
 
34. Detect the velocity RPM of a car motor with just a piezo.

35. Detect a gear that is connected to a motor is near it's fail point, by putting a vibrations microphone (Piezo), and them doing a FFT and seeing the principal components of the signal, the RPM and the number of teth give the wear of the gear.

36. Voice Pitch changer.

37. Scrambler for voice.

38. Noise canceling Phones (ADC + Delay and Phase shift + DAC).

39. Spike Noise canceler for LP Records.

40. Audio Effects (echo, reverb, phaser, ring modulation).

41. Audio equalizer.

42. Audio Bandwidth simulator for Telephone, AM Radio, FM Audio or CD Audio.

43. Implement a Digital CrossOver for multi-amplifier speakers.

44. Ambient noise canceling with 2 microphones Front of phone back of phone placement.

45. Vocal removal from Music.

46. Speaker recognition, recognizing which person is speaking.

47. Program to extract the musical notes from a music, manual help just do the FFT and a graph of frequency vs time, in which amplitude is mapped to color.

48. Implementation of ADPCM Compression and decompression algorithm.

49. Video Stabilization using correlation between n and n-1 video frames.

50. Implement super-resolution in raw video, with algorithm or with deep learning.