# app-epoch

Brainlife App to create epochs based on the events recorded in the Raw object’s STIM channels using MNE-Python Epoch method mne.Epochs function

1) Input file is: 
    * `meg/fif` meg data file
    * event.tsv (optional)
2) Input number is:
    * tmin and tmax (Start and end time of the epochs in seconds, relative to the time-locked event)
3) Input boolean is:
    * meg bool
    If True include MEG channels. 
    
    * eeg bool
    If True include EEG channels.
    
    * stim bool
    If True include stimulus channels.
    
    * eog bool
    If True include EOG channels.
    
    * ecg bool
    If True include ECG channels.
    
    * emg bool
    If True include EMG channels.

4) Ouput files are:
    * `epochs/fif`
    * HTML report


## Authors
- Saeed Zahran (saeed.zahran@icm-institute.org)
