# ECG dataset  
An electrocardiogram (ECG) is a simple test that can be used to check your heart's rhythm and electrical activity. Sensors attached to the skin are used to detect the electrical signals produced by the heart each time it beats.

A resting 12-lead ECG is recorded at each visit for participants. The record length is 10 seconds and the sample rate is 1000Hz. We collect both the raw waveform ECG signal from all leads and tabular data. The tabular data are features which have been extracted automatically by the machine from the raw data such as the P wave duration.

The information is stored in 2 tabular parquet files: `ecg_main.parquet`, `ecg_qc.parquet`, which contain tabular features and QC checks on the raw ECG waveform data. Mutiple time series parquet files contain the raw and processed ECG waveform data