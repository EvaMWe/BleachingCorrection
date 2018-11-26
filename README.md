# BleachingCorrection
a matlab coded algorithm to correct bleaching effects from fluorescence microscopy derived frame sequences

Principle:
Recording of an independent blank curve without stimulations or treatment to recorde the course of the bleauching.
Fitting of that curve by an exponential fit to get correction parameters
Core is an iterative deconvoltuion of the experimental curve and the fit
