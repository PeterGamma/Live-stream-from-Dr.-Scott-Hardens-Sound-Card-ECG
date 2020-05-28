
   Live stream is also possible from Sound Card ECG with AD8232 from Scott Harden. Sound cards have 16 bit sampling rate, which is higher than the 8 - 10 bit sampling rate of the standard Bitalino ECG.
  
  This device was developed by the experienced research scientist and low-cost biomedical device builder Scott Harden, which is a social animal, and does make it easy to get real time data, as compared to Garmin devices. More than 10 years of experience makes Scott an excellent device builder, who built a high quality low cost device which is potentially a research grade device.
  
  https://swharden.com/wp/2019-03-15-sound-card-ecg-with-ad8232/
  
  Signal transmission over an audio cable to a soundcard is more stable than over bluetooth 3.0. With wireless transmission, it is always a risk that the connection is lost.
  
  Scott has developed high quality open source data aquisition software for his sound Card ECG, which is easy to use, and could potentially be integrated in other data aquisition software and platforms (MIT licence).
  
  https://github.com/swharden/SoundCardECG

Unfortunately, there is no Matlab interface for Scott s device. Audio signals can be processed in Matlab. There is a problem, when using multiple soundcards, for instance when using multiple sound cards for using multiple sound card data aquisition systems. But in Matlab, the problem of multiple soundcards is solved:

https://www.mathworks.com/help/daq/multichannel-audio-input-and-output.html

But this is still no ECG Matlab software. For Matlab, there is a paper from researcher from India using the AD8232 (wich is also used by Scott Harden) interfacing to Matlab with an Arduino. but they did no standard tests with the device for better user acceptance:

https://www.researchgate.net/publication/336878101_Wearable_ECG_Recorder_with_MATLAB
