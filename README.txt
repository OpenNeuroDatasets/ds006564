
Experiment Details:

Participants watched short films during fMRI while focusing on the main character’s mental states.  The films were paired with soundtracks varying in musical properties, enabling investigation of how controlled music-driven memory associations influence ToM encoding through predictive priming mechanisms.

TR = 2s

Information to relate patterns of functional brain organization to phenotypic measures (i.e., personality traits):

The dataset allows to investigate brain mechanisms underlying individual variation in measures related to ASD including: autism traits (Baron-Cohen et al., 2001), empathy traits, and ToM (Baron-Cohen and Wheelwright, 2004)]. The influence of three common co-morbidities: depression, anxiety and alexithymia can also be assessed (Spielberger et al., 1970; Beck, 1991; Vorst and Bermond, 2001; Bird et al., 2010; Heaton et al., 2012; Strang et al., 2012).


Link to General Behavioural Table (https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=1356882045#gid=1356882045) including: 

- Demographics (gender, musical training, paradigm version A or B)
- Autism traits measures: empathy quotient, cognitive empathy, emotional reactivity, autism quotient, social skills, attention switching, attention to detail, communication, imagination (Baron-Cohen and Wheelwright, 2004).
- Depression traits (BDI-II), Anxiety traits (A-State score), Alexithimia (Spielberger et al., 1970; Beck, 1991; Vorst and Bermond, 2001; Bird et al., 2010; Heaton et al., 2012; Strang et al., 2012).
- Behavioural data collected inside the scanner.


Task Mapping Table:

The following table defines how 3D scans are grouped into BIDS-compliant 4D NIfTI files based on the naturalistic task they belong to:

Naturalistic Task Name
Scan Index (1-based)
Experimental Design
Output Filename
naturalistic-rest-pendulous
6–408
Link to Pendulous Design 01 (block: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=2013130588#gid=2013130588) and 02 (event-related: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=127456479#gid=127456479)
sub-XX_task-natrestpendulous_bold.nii.gz

naturalistic-rorschach
408–502
Link to Rorschach Design: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=11411923#gid=11411923
sub-XX_task-natrorschach_bold.nii.gz

naturalistic-tunnel
502–637
Link to Tunnel Design: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=389529649#gid=389529649
sub-XX_task-nattunnel_bold.nii.gz

naturalistic-seti
637–913
Link to SETi Design: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=2055828508#gid=2055828508
sub-XX_task-natseti_bold.nii.gz

naturalistic-pov
913–1046
Link to POV Design: https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=1748720858#gid=1748720858
sub-XX_task-natpov_bold.nii.gz

naturalistic-kandinski
1046–1159
sub-XX_task-natkandinski_bold.nii.gz


Note: Replace 'sub-XX' with the actual subject ID, e.g., 'sub-01', 'sub-02'.


Link to Technical Table (https://docs.google.com/spreadsheets/d/1RtUboA4nd4tg-X9HG_LaLM2eXA8GFAXzZ7xLzVXM2zE/edit?gid=11411923#gid=11411923) including complete timepoints, audio and visual technical details for all naturalistic paradigms, scanner details.


Preprocessing details:

Data were processed using Statistical Parametric Mapping (SPM), version 12 (www.fil.ion.ucl.ac.uk/spm). Following correction for the temporal difference in acquisition between slices, EPI volumes were realigned and resliced to correct within subject movement. A mean EPI volume was obtained during realignment and the structural MRI was coregistered with that mean volume. The coregistered structural scan was normalized to the Montreal Neurological Institute (MNI) T1 template (32). The same deformation parameters obtained from the structural image, were applied to the realigned EPI volumes, which were resampled into MNI-space with isotropic voxels of 3 cubic millimetres. The normalized images were smoothed using a 3D Gaussian kernel and a filter size of 6 mm FWHM. A temporal high-pass filter with a cut-off frequency of 256Hz was applied with the purpose of removing scanner attributable low frequency drifts in the fMRI time series. 


For references see: Bravo F, Glogowski J, Stamatakis EA, Herfert K (2024) Dissonant music engages early visual processing. Proc Natl Acad Sci USA 121:e2320378121. (Full text can be downloaded from here: https://drive.google.com/file/d/1VPhewm2k_aG7afdgeSu_364eM29Dcta4/view?usp=sharing)


For questions or support please email :
Dr. Fernando Bravo
Email: nanobravo@fulbrightmail.org
PI - Coordinating Investigator - Studienleiter