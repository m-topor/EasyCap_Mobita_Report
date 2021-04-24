# EasyCap_Mobita_Report
# In search for the most optimal EEG method: A practical evaluation of a water-based electrode EEG system.  
  
### What does this repository contain?  
This repository is directly related to a research report titled **"In search for the most optimal EEG method: A practical evaluation of a water-based electrode EEG system.  "**   
This repository contains files with processed EEG data extracted for statistical comparisons and visualisation.  
The code for all analyses included in the report is also provided within the repository in the format of R Markdown. The resulting lab book with all outputs in a Word Document isa also included.  
Figures that are included in the repository are those that were extracted from BrainVision Analyzer and also used in the research report.  
  
### File directory  
**Lab Book with all analyses:**  
- **tech_report_analyses.rmd** - An R Markdown file including code that uses all of the files below to compose a fully comprehensive lab book with results and figures presented in the paper.  
- **tech_report_analyses.docx** - The lab book output in the format of a Word document  

**Data files:**  
- **ERN.csv** - Mean amplitude extracted for 0-100ms post response. There are spearate columns for EasyCap and Mobita data and for mean amplitude for correct and error responses. Participant data are already directly matched for within subject comparisons.   
- **ERN_peak.csv** - Peak details extracted for the ERN difference wave observed with EasyCap and Mobita. There are separate columns for peak time and maximum amplitude for each system. Participant data are already directly matched for within subject comparisons.  
- **FFT_range_alpha_all.csv** - averaged alpha frequency (8-14Hz) power extracted in uV<sup>2</sup> from stimulus-locked epochs (-200 to 500ms relative to stimulus) per channel per EEG system. Participant data are already directly matched for within subject comparisons.  
- **FFT_range_high_beta_all.csv** - averaged high beta frequency (24-30Hz) power extracted in uV<sup>2</sup> from stimulus-locked epochs (-200 to 500ms relative to stimulus) per channel per EEG system. Participant data are already directly matched for within subject comparisons.
- **FFT_range_low_beta_all.csv** - averaged low beta frequency (14-24Hz) power extracted in uV<sup>2</sup> from stimulus-locked epochs (-200 to 500ms relative to stimulus) per channel per EEG system. Participant data are already directly matched for within subject comparisons.
- **FFT_range_theta_all.csv** - averaged theta frequency (4-8Hz) power extracted in uV<sup>2</sup> from stimulus-locked epochs (-200 to 500ms relative to stimulus) per channel per EEG system. Participant data are already directly matched for within subject comparisons.  
- **freq_channel_selection.csv** - grand average power values observed at each channel (peripheral channels excluded) for each EEG system per frequency of interest (theta, alpha, low beta, high beta). The 5 channels with the strongest activity for each EEG system are highlighted and overlapping channels are then used for direct comparisons.  
- **P300.csv** Mean amplitude extracted for 300-500ms post stimulus onset. There are spearate columns for EasyCap and Mobita data. Participant data are already directly matched for within subject comparisons.  
- **P300_peak.csv** - Peak details extracted for the P300 observed with EasyCap and Mobita. There are separate columns for peak time and maximum amplitude for each system. Participant data are already directly matched for within subject comparisons.  
- **pre_processing_data.csv** - This file contains details regarding the number of epochs remaining for each participant and each system after pre-rpocessing (columns 4:12), number of blocks included in analyses which is matched across the two systems (column 13), the number of interpolated channels (columns 14:15), the number of rejected ICA components per system (columns 16:17), the number of rejected epochs during artefact rejection for each type of epochs (stimulus-locked, response-locked correct and response-locked error; columns 18:23). Participant data are already directly matched for within subject comparisons.   
- **range_2Hz_all.csv** - averaged frequency at 0.1-2Hz after pre-processing extracted for each channel and system from stimulus-locked epochs (-200 to 500ms relative to stimulus). Participant data are already directly matched for within subject comparisons.  
- **range_50Hz_all.csv** - averaged frequency at 49-51Hz after pre-processing extracted for each channel and system from stimulus-locked epochs (-200 to 500ms relative to stimulus). Participant data are already directly matched for within subject comparisons.
- **raw_2Hz_all.csv** - averaged frequency at 0.1-2Hz on raw data (prior to pre-processing) extracted for each channel and system from stimulus-locked epochs (-200 to 500ms relative to stimulus). Participant data are already directly matched for within subject comparisons.
- **raw_50Hz_all.csv** - averaged frequency at 49-51Hz on raw data (prior to pre-processing) extracted for each channel and system from stimulus-locked epochs (-200 to 500ms relative to stimulus). Participant data are already directly matched for within subject comparisons.
- **RMS.csv** - averaged RMS values extracted from a subset of electrodes (excluding peripheral electrodes) per system. Participant data are already directly matched for within subject comparisons.  
- **SNR_E.csv** - SNR values extracted for each participant and each channel from averaged stimulus-locked epochs (-200 to 500ms relative to stimulus), this datafile onclu contains data from EasyCap recordings
- **SNR_M.csv** - SNR values extracted for each participant and each channel from averaged stimulus-locked epochs (-200 to 500ms relative to stimulus), this datafile onclu contains data from Mobita recordings
  
**Figures:**
- **ERN.jpg** - Figure comparing the ERN waveform and topography between EasyCap and Mobita  
- **fig1_raw_freq.jpg** - raw data frequency spectrum with power values reflected in black for EasyCap and red for Mobita  
- **fig2_range_freq.jpg** - pre-processed data data frequency spectrum with power values reflected in black for EasyCap and red for Mobita  
- **freq_topographies.jpg** - topographies for all frequencies comparing activity observed with EasyCap and Mobita. First row is EasyCap and second row is Mobita.  
- **P300.jpg** - Figure comparing the P300 waveform and topography between EasyCap and Mobita  
- **P300_fz_pz.jpg** - Figure comparing the P300 waveform between EasyCap and Mobita at Fz and Pz channels 
