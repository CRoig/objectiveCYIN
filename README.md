objectiveCYIN
=============

This class implements an objective-C version of YIN algorithm [1].

float objcYIN(UInt32 inNumberFrames, float sampleRate, float *inData);

Inputs:
1. inNumberFrames: the number of frames of the input buffer.
2. sampleRate: the sample rate of the incoming data.
3. inData: the samples of the input sound.

This method could be called in the micLineInCallback of an IO AudioUnit within a AUGraph. 

[1] De Cheveigné, Alain, and Hideki Kawahara. "YIN, a fundamental
      frequency estimator for speech and music." The Journal of the
      Acoustical Society of America 111.4 (2002): 1917-1930.
