# MicTestApp
Microphone test app for sight singing

# To build:
- javac UdmtMicTestApp.java
- ./makejar.bat

# To run:
- Always run the application from the command line.  The app will display console messages as it runs.
- java -jar UdmtMicTestApp.jar
- Allow access to microphone.
- The checkbox is used if you want to save the audio and FFT data.
- Start singing a syllable, then press RECORD.  Hold your note for a few seconds.
- If you chose to save the data, you will see files: dat1.csv and fft1.csv.
- You can listen to what was recorded using the PLAY RECORDED VOICE button.
- The number appended to the filenames increments with each recording that is saved.
- If you exit the app and want to keep the recording data, move the files out of the application directory because saves will start with a suffix of 1.

# Sample console output:
```
init method called for Applet: UdmtMicTest ver: 0.12
======================================================================================
ixlookup>=253 <= 267
FLAT RED: 252 thru 253
FLAT YELLOW: 254 thru 255
SHARP RED: 265 thru 266
SHARP YELLOW: 263 thru 264
ixLookup=264
range=15
midpt=260.0
fcents=0.26666668
calccents=26

FFT Fundamental Freq Index=264 MIDI=53
F3 YELLOW  SHARP  APPROX CENTS OFF: 26
SAVING CSV
DONE RECORDING
```
