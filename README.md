CHERRY ROOM - INTERAURAL COHERENCE ESTIMATION APP<br/>
Version 1.0<br/>
Documentation File<br/>
Author/Developer: Lampros Chantzis<br/>
Date: 26/11/2019<br/>

---------------------------------------------------------------------------------------------------------------------------------------
1. GENERAL<br/>
"Cherry Room" is a Matlab plug-in developed with Matlab's App Designer. It uses a frame processing algorithm to estimate and present
graphs of Magnitude and Phase of Coherence Function between two input signals. All the proseccing takes place at Frequency Domain as a
Hanning Window filter is applied to every frame of the signals. Further information about Coherence Function and Signal's Frame
Processing can be found here: http://en.wikipedia.org/wiki/Coherence_(signal_processing). Note that Cherry Room does not follow the 
theoretical formulas for Coherence Function calculation but instead it uses an iretative algorithm for every pair of frames of the 
divided input signals.

---------------------------------------------------------------------------------------------------------------------------------------
2. CONTENTS<br/>
In this Repository are:<br/>
Resources: The Required files to run this app.<br/>
Screens: A layout preview of the app.<br/>
Test Audio Files: Some testing audio files for input to the app.<br/>
Source Code: The mlapp file that contents the source code of the app. It can be opened with Matlab(2016 or later).<br/>
Packaged App: The app installer file to add "Cherry Room" to your Matlab Apps.<br/>
 
---------------------------------------------------------------------------------------------------------------------------------------
3. INSTALL<br/>
In order to run "Cherry Room" you must have Matlab (2016 or later). After you install the app in the Matlab apps you can run it through 
Matlab Apps at the top of your Matlab interface screen. All required files and folders are contained in the installation file. Finally
when you load your audio to the app use the files in the "Test Audio Files" folder that will be installed with the app in order to 
prevent problems with Matlab path.

---------------------------------------------------------------------------------------------------------------------------------------
4. HOW TO USE<br/>
i. Import Files: Click on the Load Files button on the left panel of your layout. Add the path of your disired file and repeat for the 
second input.<br/>
ii. Choose Window Length: After loading your inputs you can choose the length of the Hanning window which will be applied to the inputs
frames. The default value is 512 samples but you can add more.<br/>
iii. Choose Smoothing Factor: As the frame processing takes place, an iterative method is used to each frame that takes into acount a
rate of the previous frame in order to follow better and smoother the theoretical values of Coherence Function. Note that as bigger the
smoothing factor is, as slower the variation of Coherence Function is.<br/>
iv. Graphs: On the right panel of your layout Magnitude and Phase of Coherence Function will be presented as soon as you press the 
Coherence Estimation Button.

---------------------------------------------------------------------------------------------------------------------------------------
5. LISCENCE AND CREDITS<br/>
"Cherry Room" is a software developed for my thesis under the subject "Audio Signals Analysis for Listener's Envelopement 
Estimation". Its developement was supervised by Professor of Electrical & Computer Engineering, John Mourjopoulos and
Audiogroup of Patras University. Any suggestions or questions on this software are welcome.

Enjoy Cherry Room<br/>
Thank you