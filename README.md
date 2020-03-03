# EEG-Datasets
A list of all public EEG-datasets. This list of EEG-resources is not exhaustive. If you find something new, or have explored any unfiltered link in depth, please update the repository.

* **Motor-Imagery**
  1. [Left/Right Hand MI](http://gigadb.org/dataset/100295):  Includes 52 subjects (38 validated subjects with discriminative features), results of physiological and psychological questionnares, EMG Datasets, location of 3D EEG electrodes, and EEGs for non-task related states
  2. [Motor Movement/Imagery Dataset](https://www.physionet.org/physiobank/database/eegmmidb/): Includes 109 volunteers, 64 electrodes, 2 baseline tasks (eye-open and eye-closed), motor movement, and motor imagery (both fists or both feet)
  3. [Grasp and Lift EEG Challenge](https://www.kaggle.com/c/grasp-and-lift-eeg-detection/data): 12 subjects, 32channels@500Hz, for 6 grasp and lift  events, namely a). HandStart b). FirstDigitTouch c). BothStartLoadPhase d). LiftOff e). Replace  f). BothReleased
  4. [The largest SCP data of Motor-Imagery](https://doi.org/10.6084/m9.figshare.c.3917698): The dataset contains 60 hours of EEG BCI recordings across 75 recording sessions of 13 participants, 60,000 mental imageries, and 4 BCI interaction paradigms, with multiple recording sessions and paradigms of the same individuals. BCI interactions involving up to 6 mental imagery states are considered. [[Article]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6190745/pdf/sdata2018211.pdf)
  5. [BCI Competition IV-1](http://www.bbci.de/competition/iv/#dataset1): 64 EEG channels at 1000Hz sampling rate for 2 classes of left hand, right hand, foot (+ idle state) for 7 subjects. Evaluation data is continuous EEG which contains also periods of idle state.
  6. [BCI Competition IV-2a](http://www.bbci.de/competition/iv/#dataset2a): 22-electrode EEG motor-imagery dataset,  with 9 subjects and 2 sessions, each with 288 four-second trials of imagined movements per subject. Includes movements of the left hand,the right hand, the feet and the tongue. [[Dataset Description]](http://www.bbci.de/competition/iv/desc_2a.pdf)
  7. [BCI Competition IV-2b](http://www.bbci.de/competition/iv/#dataset2b): 3-electrode EEG motor-imagery dataset with 9 subjects and 5 sessions of imagined movements of the left or the right hand, the latest 3 sessions include online feedback. [[Dataset Description]](http://www.bbci.de/competition/iv/desc_2b.pdf)
  8. [High-Gamma Dataset](https://github.com/robintibor/high-gamma-dataset): 128-electrode dataset obtained from 14 healthy subjects with roughly 1000 four-second trials of executed movements divided into 13 runs per subject.  The four classes of movements were movements of either the left hand, the right hand, both feet, and rest.
  9. [Left/Right Hand 1D/2D movements](https://sites.google.com/site/projectbci/): 19-electrode data of one subject with various combinations of 1D and 2D hand movements (actual execution). 
  10. [Imagination of Right-hand Thumb Movement](https://archive.ics.uci.edu/ml/datasets/Planning+Relax): In every trial, subjects were asked to rest and rest data was recorded for 5 mins. Further, 5 second epoch data was also recorded when subjects were asked to imagine right hand thumb movement. 5 of such imagined motor movement, and rest state was recorded for each trial. Single subject, 8 electrodes at 256Hz.

  
* **Emotion-Recognition**
  1. [DEAP](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/): Includes 32 subjects, each watchine 1-min long excerpts of music-videos, rated by users in terms of arousal/valence/like-dislike/dominanace/famaliarity, and frontal face recording of 22/32 subejcts.
  2. [Enterface'06](http://www.enterface.net/results/): Enterface'06 Project 07: EEG(64 Channels) + fNIRS + face video, Includes 16 subjects, where emotions were elicited through selected subset of IAPS dataset.
  3. [Imagined Emotion](http://headit.ucsd.edu/studies/3316f70e-35ff-11e3-a2a9-0050563f2612): 31 subjects, subjects listen to voice recordings that suggest an emotional feeling and ask subjects to imagine an emotional scenario or to recall an experience in which they have felt that emotion before.
  4. [NeuroMarketing](https://drive.google.com/open?id=0B2T1rQUvyyWcSGVVaHZBZzRtTms): 25 subjects, 14 electrodes, Like/Dislike on commercial e-commerce products over 14 categories with 3 images each. Article for the dataset: Analysis of EEG signals and its application to neuromarketing. [[Article]](https://link.springer.com/article/10.1007/s11042-017-4580-6)
  5. [SEED](http://bcmi.sjtu.edu.cn/~seed/seed.html): 15 subjects were shown video clips eliciting positive/negative/neutral emotion and EEG was recorded over 62 channels.
  6. [SEED-IV](http://bcmi.sjtu.edu.cn/~seed/seed-iv.html): 15 subjects were shown video clips ellicity happy/sad/neutral/fear emotions and EEG was recorded over 62 channels (with eye-tracking) for 3 sessions per subject (24 trials per session).
  7. [SEED-VIG](http://bcmi.sjtu.edu.cn/~seed/seed-vig.html): Vigilance labels with EEG data in a simulated driving task. 18 electrodes and eye-tracking included.
  8. [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjetcs were shown video clips (fragments of movies) and they were asked to annotate the emotional state on the scale of valence and arousal. During the whole experiment, audio, video, gaze data and physiological data were recorded simultaneously with accurate synchronisation between sensors.
  9. [Regulation of Arousal](https://ieee-dataport.org/open-access/regulation-arousal-online-neurofeedback-improves-human-performance-demanding-sensory): 18 subjects going through an online flight simulator study with three different audio-feedback silence, sham and BCI. [[Article]](https://www.pnas.org/content/116/13/6482)
  
  
* **Error-Related Potentials (ErrP)**
  1. [BCI-NER Challenge](https://www.kaggle.com/c/inria-bci-challenge): 26 subjects, 56 EEG Channels for a P300 Speller task, and labeled dataset for the response elicited when P300 decodes a correct or incorrect letter.
  
  2. [Monitoring ErrP in a target selection task](http://bnci-horizon-2020.eu/database/data-sets): 6 subjects with 64 EEG electrodes, watching a cursor move towards a target square, and elicited responses are labeled based on whether the cursor moves in right or wrong direction. [[Dataset Description]](https://lampx.tugraz.at/~bci/database/013-2015/description.pdf)
  
  3. [ErrPs during continuous feedback](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/contErrP_description.pdf): 10 subjects with 28 EEG electrodes, playing a video game to study execution and outcome error. [[Dataset Part-1]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part1.rar) [[Dataset Part-2]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part2.rar)
  
  4. [HCI-Tagging](https://mahnob-db.eu/hci-tagging/): Subjetcs were shown images or movie fragments with a tag at the bottom of the screen. In some cases, the tag correctly described something about the situation. However, in other cases the tag did not actually apply to the media item. After each item, a participant was asked to press a green button if they agreed with the tag being applicable to the media item, or press a red button if not. During the whole experiment, audio, video, gaze data and physiological data were recorded simultaneously with accurate synchronisation between sensors.
  
* **Visually Evoked Potentials (VEPs)**
  1. [c-VEP BCI](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_dataset.rar): 9 subjects, 32 EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Dataset description]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_description.pdf) [[Published article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0051077)
  
   2. [c-VEP BCI with dry electrodes](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/dry_cVEP_dataset.rar): 9 subjects, 15 dry-EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)
   
   3. [SSVEP - Visual Search/Discrimination and Handshake](https://archive.ics.uci.edu/ml/datasets/EEG+Steady-State+Visual+Evoked+Potential+Signals#): Includes 3 different tests, (i) Five Box visual test: attnded and unattended disc and square based stimuli, (ii) visual search within natural images: search of a yellow dot stimuli in B&W natural images, (iii) hand shake test: showing left/right hand closed/open images. 30 subjects, 14 electrodes. [[Article 1]](http://www.journalijar.com/uploads/154_IJAR-13703.pdf) [[Article 2]](https://www.hindawi.com/journals/ddns/2018/2143873/) [[More Dataset: Dataset 2]](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html)
   
   4. [Synchronized Brainwave Dataset](https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset): 15 people were presented with 2 different video stimulus including blinks, relaxation, mental mathematics, counting color boxes, and watching superbowl ads. [[Stimulus 1]](https://www.youtube.com/watch?v=zkGoPdpRvaU&feature=youtu.be) [[Stimulus 2]](https://www.youtube.com/watch?v=sxqlOoBBjvc&feature=youtu.be)
  
* **Event Related Potentials [ERPs]**
  1. [Pattern Visual Evoked Potentials](https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software): Dataset#5, 2 subjects for checkboard light pattern (oddball paradigm) recorded at O1 position. 
  2. [Face vs. House Discrimination](https://purl.stanford.edu/xd109qh3109): 7 Epileptic subjects were presented with 50  grayscale stimulations each for Face and House pictures. For each subject, total 3 experimental runs were conducted resulting in 300 stimulations. 
  3. [Target Versus Non-Target](https://zenodo.org/record/2649069): 25 subjects testing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm. 16-electrodes, wet. [publication](https://hal.archives-ouvertes.fr/hal-02126068), [code](https://github.com/plcrodrigues/py.BI.EEG.2012-GIPSA). Dataset id: BI.EEG.2012-GIPSA.
  4. [Target Versus Non-Target](https://zenodo.org/record/2669187): 24 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm. 16-electrodes, wet. Up to 8 sessions per subject. Two experiemental conditions: with and without adaptive calibration using Riemannian geometry. [publication](https://hal.archives-ouvertes.fr/hal-02103098), [code](https://github.com/plcrodrigues/py.BI.EEG.2013-GIPSA). Dataset id: BI.EEG.2013-GIPSA.
  5. [Target Versus Non-Target](https://zenodo.org/record/3266223): 71 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 16-electrodes, dry. [publication](https://hal.archives-ouvertes.fr/hal-02171575), [code](https://github.com/plcrodrigues/py.BI.EEG.2014a-GIPSA). Dataset id: bi2014a.
  6. [Target Versus Non-Target](https://zenodo.org/record/3267302): 38 subjects playing a multiplayer and collaborative version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 32-electrodes per subject, wet, 2 subjects during each session. [publication](https://hal.archives-ouvertes.fr/hal-02173958), [code](https://github.com/plcrodrigues/py.BI.EEG.2014b-GIPSA). Dataset id: bi2014b.
  7. [Target Versus Non-Target](https://zenodo.org/record/3266930): 50 subjects playing Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 32-electrodes, wet. 3 sessions per subjects with modulation of flash duration. [publication](https://hal.archives-ouvertes.fr/hal-02172347), [code](https://github.com/plcrodrigues/py.BI.EEG.2015a-GIPSA). Dataset id: bi2015a.
  8. [Target Versus Non-Target](https://zenodo.org/record/3268762): 44 subjects playing a multiplayer (cooperation and competition) version of Brain Invaders, a visual P300 Brain-Computer Interface using oddball paradigm with adapative Riemannian Geometry (no-calibration). 32-electrodes per subject, wet, 2 subjects for each session. [publication](https://hal.archives-ouvertes.fr/hal-02173913), [code](https://github.com/plcrodrigues/py.BI.EEG.2015b-GIPSA). Dataset id: bi2015b.
  9. [Impedance Data](https://drive.google.com/drive/folders/0B3jfvN2T6iLMLWJMMVJMSXBqajg): 12 subjects for P300 task (Oddball paradigm) with 20% of rare stimuli. In total, there were 128 target stimuli and 512 standard stimuli. The dataset was collected in a way such that one recording contains different impedances in electrodes. [[Article]](https://static1.squarespace.com/static/5abefa62d274cb16de90e935/t/5ac6962a8a922d0b8b8be6a1/1522964012664/Kappenman+2010+Psychophys+Impedance.pdf)
  10. [Sustained-Attention Driving](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task/6427334/5): 27 subjects for sustained-attention driving in a VR settin for monitoring event-related potentials. Each subject participated in two 90 min sessions (w/o and with kinesthetic feedback) and recorded with 32-channels and 500Hz. [[Article]](https://www.nature.com/articles/s41597-019-0027-4#Sec12) [[Pre-processed dataset]](https://figshare.com/articles/Multi-channel_EEG_recordings_during_a_sustained-attention_driving_task_preprocessed_dataset_/7666055/3)
  11. [Dryad-Speech](https://datadryad.org/stash/dataset/doi:10.5061/dryad.070jc): 5 different experiments for studying natural speech comprehension through a variety of tasks including audio, visual stimulus and imagined speech. (i) Audio-book version of a popular mid-20th century American work of fiction - 19 subjects, (ii) presentation of the same trials in the same order, but with each of the 28 speech segments played in reverse, (iii) N400 experiment: subjects read 300 sentences presented  with the rest of the sentence and half which ended with an incongruent word - , (iv) cocktail party experiment: 33 subjects undertook 30 trials, each of 60 s in length, where they were presented with 2 classic works of fiction: one to the left ear, and the other to the right ear. Subjects were divided into 2 groups of 17 and 16 (+1 excluded subject) with each group instructed to attend to the story in either the left or right ear throughout the entire 30 trials, (v) multisensory experiment:  stimuli were drawn from a set of videos that consisted of a male speaking American English in a conversational-like manner. [[Main Article]](https://www.sciencedirect.com/science/article/pii/S0960982218301465) [[Supplemntary Article]](https://www.ncbi.nlm.nih.gov/pubmed/26412129)
  


* **Resting State**
  1. [Resting State EEG Data](https://dataverse.tdl.org/dataverse/txstatecogelectro): 22 subjects, 72 EEG Channels for a resting task of 8 mins with 4 mins of eyes closed and 4 mins of eyes open. [[Article]](https://www.frontiersin.org/articles/10.3389/fnins.2017.00425)
  2. [EID-M, EID-S](https://drive.google.com/drive/folders/1t6tL434ZOESb06ZvA4Bw1p9chzxzbRbj): 8 subjects in rest state (with eyes closed) recorded from 14 electrodes using EPOC+ for 54s at 128 Hz (7000 samples each). EID-M has three trials and EID-S is a signle trial dataset. The dataset was used to develop a person identification system through brainwaves. [[Article]](https://arxiv.org/pdf/1711.06149.pdf)
  
* **Music and EEG**
  1. [Music Imagery Information Retrieval](https://github.com/sstober/openmiir): 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo. [[Article]](https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf)
  
* **Eye-blinks/movements**
  1. [Involuntary Eye Movements during Face Perception](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html): Dataset 1, 26 electrodes, 500Hz sampling rate, and 120 trials. Eye movements and pupil diameter record, EEG and EOG data is present when subject is presented a happy/sad/angry face on the screen. [[Article]](http://www.jneurosci.org/content/suppl/2009/09/30/29.39.12321.DC1/Supplemental_Material.pdf) [P.S: Dataset available on request only]
  2. [Voluntary-Involuntary Eye-Blinks](https://drive.google.com/file/d/0By5iwWd39NblS2tRWmVTdmRzZUU/view?usp=sharing): Voluntary eye-blinks (subject were asked to blink voluntarily within 1s of audio stimulus) and involuntary eye-blinks (natural) was recorded for 20 subjects on 14 electrodes using g.tec. For each subject, 3 sessions with 20 trials each are present in .mat format. [[Article]](https://www.sciencedirect.com/science/article/pii/S0925231216001569)
  3. [EEG-eye state](https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State): Eye-state labeled data for one continuous recording of EEG of 117 seconds with eye-closed and eye-open labels. The dataset was recorded from Emotiv headset.
  4. [EEG-IO](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Voluntary single eye-blinks (external stimulation was provided) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 20 subjects using OpenBCI Device and BIOPAC Cap100C. One session was conducted including around 25 blinks per subject. Manual annotation was done using video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
  5. [EEG-VV, EEG-VR](http://gnan.ece.gatech.edu/eeg-eyeblinks/): Involuntary eye-blinks (natural blinks) and EEG was recorded for frontal electrodes (Fp1, Fp2) for 12 subjects using OpenBCI Device and BIOPAC Cap100C. Subjects performed two activities - watching a video (EEG-VV) and reading an article (EEG-VR). Manual annotation was done using video feed. [[Article]](https://proceedings.allerton.csl.illinois.edu/media/files/0174.pdf)
  6. [Eye State Prediction](http://suendermann.com/corpus/EEG_Eyes.arff.gz): 117 seconds recording of a single subject with labeled eye state data (open and closed) recorded using EPOC headset (14 electrodes). [[Article]](http://suendermann.com/su/pdf/aihls2013.pdf)
  7. [Kara-One](http://www.cs.toronto.edu/~complingweb/data/karaOne/karaOne.html): Imagined and vocalized phonemic and single-word prompts to access the language and speech production. 14 subjects recorded using 64-channel Neuroscan Quick-cap, along with face tracking and audio. [[Article]](http://www.cs.toronto.edu/~complingweb/data/karaOne/ZhaoRudzicz15.pdf)
  
* **Miscellaneous**
  1. [MNIST Brain Digits](http://mindbigdata.com/opendb/index.html): EEG data when a digit(0-9) is shown to the subject, recorded 2s for a single subject using Minwave, EPOC, Muse, Insight. Includes over 1.2M samples. 
  2. [Imagenet Brain](http://www.mindbigdata.com/opendb/imagenet.html): A random image is shown (out of 14k images from the Imagenet ILSVRC2013 train dataset) and EEG signals are recorded for 3s for one subject. Includes over 70k samples.
  3. [Working Memory](https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data): Participants briefly observe an array containing multiple English characters SET (500ms) and maintain the information for three seconds. A TEST character is then presented and participants respond by press of a button if TEST charter matches one of the characters in the SET. 15 students, 64 electrodes and 500Hz sampling rate. Only a small subset of data is available publicly. [[Original Paper]](https://www.memphis.edu/acnl/publications/pdfs/ejn2014b.pdf) [[Further Analysis in ICLR]](https://arxiv.org/pdf/1511.06448.pdf)
  4. [Deep Sleep Slow Osciallation](https://challengedata.ens.fr/challenges/10): 10 seconds of recording starting 10 seconds before the end of a slow oscillation. Data is recorded with a goal to predict whether or not a slow oscillation will be followed by another one in sham condition, i.e. without any stimulation.
  5. [Genetic Predisposition to Alcoholism](https://archive.ics.uci.edu/ml/datasets/EEG+Database): 120 trials for 120 subjects recorded from 64 electrides at 256Hz. Two groups of subjects were considered, alcoholic and control. Stimuli details are given in the paper. 

* **Clinical EEG**
  1. [TUH EEG Resources](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml): Massive amount of data for (i) Abnormal EEG and (ii) EEG Seizures
  2. [Predict-UNM](http://predict.cs.unm.edu/): A large repository of clinical EEG datasets
  
  
    
  
### Others [Unfiltered]
  1. https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html - http://headit.ucsd.edu/studies 
  2. https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software
  3. https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data 
  4. Section 2: https://arxiv.org/pdf/1611.08024.pdf 
  6. EEG Databases for Emotion Recognition, NTU 
  7. https://engineuring.wordpress.com/2009/07/08/downloadable-eeg-data/ 
  8. http://www.brainsignals.de/
  9. http://www.fil.ion.ucl.ac.uk/spm/data/
  10. http://www.brainliner.jp/search/showall/1
  11. http://bnci-horizon-2020.eu/database/data-sets
  13. http://archive.ics.uci.edu/ml/datasets/EEG+Database
  14. https://www.physionet.org/physiobank/database/#neuro
  15. ERP Core Dataset (Coming Soon) https://erpinfo.org/erp-core
  16. https://sites.google.com/site/iitrcsepradeep7/resume
  18. http://memory.psych.upenn.edu/RAM
  19. http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/
  20. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8616018
  21. https://arxiv.org/pdf/1805.06427.pdf
  22. http://www.gtec.at/Research/Biosignal-Data-Sets/content/Biosignal-Data-Sets
  23. http://studycatalog.org/
  26. https://ieee-dataport.org/data-competitions
  27. The Australian EEG Database https://aed.newcastle.edu.au/AED/login.jsp [contact: aed@newcastle.edu.au] 
  28. Links for more datasets: http://www.fieldtriptoolbox.org/faq/open_data/ (might include some duplicates)
  29. https://figshare.com/articles/EEG_dataset/8091242 a paper with the same title is also there
  30. [Search Enginer: Might include a lot of duplicates] https://app.dimensions.ai/discover/data_set?search_text=eeg%20brain-computer%20interfaces&search_type=kws&search_field=full_search
  31. BIDS dataset: https://github.com/bids-standard/bids-examples https://osf.io/cj2dr/ https://zenodo.org/record/2536267 https://osf.io/dvmrb/
  32. Another platform for Neuro datasets: https://openneuro.org/

 
  


  
