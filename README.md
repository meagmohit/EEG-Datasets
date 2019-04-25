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
  
* **Emotion-Recognition**
  1. [DEAP](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/): Includes 32 subjects, each watchine 1-min long excerpts of music-videos, rated by users in terms of arousal/valence/like-dislike/dominanace/famaliarity, and frontal face recording of 22/32 subejcts.
  2. [Enterface'06](http://www.enterface.net/results/): Enterface'06 Project 07: EEG(64 Channels) + fNIRS + face video, Includes 16 subjects, where emotions were elicited through selected subset of IAPS dataset.
  3. [Imagined Emotion](http://headit.ucsd.edu/studies/3316f70e-35ff-11e3-a2a9-0050563f2612): 31 subjects, subjects listen to voice recordings that suggest an emotional feeling and ask subjects to imagine an emotional scenario or to recall an experience in which they have felt that emotion before.
  4. [NeuroMarketing](https://drive.google.com/open?id=0B2T1rQUvyyWcSGVVaHZBZzRtTms): 25 subjects, 14 electrodes, Like/Dislike on commercial e-commerce products over 14 categories with 3 images each. Article for the dataset: Analysis of EEG signals and its application to neuromarketing. [[Article]](https://link.springer.com/article/10.1007/s11042-017-4580-6)
  5. [SEED](http://bcmi.sjtu.edu.cn/~seed/seed.html): 15 subjects were shown video clips eliciting positive/negative/neutral emotion and EEG was recorded over 62 channels.
  6. [SEED-IV](http://bcmi.sjtu.edu.cn/~seed/seed-iv.html): 15 subjects were shown video clips ellicity happy/sad/neutral/fear emotions and EEG was recorded over 62 channels (with eye-tracking) for 3 sessions per subject (24 trials per session).
  7. [SEED-VIG](http://bcmi.sjtu.edu.cn/~seed/seed-vig.html): Vigilance labels with EEG data in a simulated driving task. 18 electrodes and eye-tracking included.
  
* **Error-Related Potentials (ErrP)**
  1. [BCI-NER Challenge](https://www.kaggle.com/c/inria-bci-challenge): 26 subjects, 56 EEG Channels for a P300 Speller task, and labeled dataset for the response elicited when P300 decodes a correct or incorrect letter.
  
  2. [Monitoring ErrP in a target selection task](http://bnci-horizon-2020.eu/database/data-sets): 6 subjects with 64 EEG electrodes, watching a cursor move towards a target square, and elicited responses are labeled based on whether the cursor moves in right or wrong direction. [[Dataset Description]](https://lampx.tugraz.at/~bci/database/013-2015/description.pdf)
  
  3. [ErrPs during continuous feedback](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/contErrP_description.pdf): 10 subjects with 28 EEG electrodes, playing a video game to study execution and outcome error. [[Dataset Part-1]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part1.rar) [[Dataset Part-2]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/Continous_ErrP_dataset_Part2.rar)
  
* **Visually Evoked Potentials (VEPs)**
  1. [c-VEP BCI](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_dataset.rar): 9 subjects, 32 EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Dataset description]](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/cVEP_description.pdf) [[Published article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0051077)
  
   2. [c-VEP BCI with dry electrodes](https://www-ti.informatik.uni-tuebingen.de/~spueler/eeg_data/dry_cVEP_dataset.rar): 9 subjects, 15 dry-EEG Channels for a VEP BCI speller (32 characters) task, and labeled dataset for the response elicited for the label associated with the speller. [[Article]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0172400)
   
   3. [SSVEP - Visual Search/Discrimination and Handshake](https://archive.ics.uci.edu/ml/datasets/EEG+Steady-State+Visual+Evoked+Potential+Signals#): Includes 3 different tests, (i) Five Box visual test: attnded and unattended disc and square based stimuli, (ii) visual search within natural images: search of a yellow dot stimuli in B&W natural images, (iii) hand shake test: showing left/right hand closed/open images. 30 subjects, 14 electrodes. [[Article 1]](http://www.journalijar.com/uploads/154_IJAR-13703.pdf) [[Article 2]](https://www.hindawi.com/journals/ddns/2018/2143873/) [[More Dataset: Dataset 2]](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html)
  
* **Event Related Potentials [ERPs]**
  1. [Pattern Visual Evoked Potentials](https://www2.le.ac.uk/departments/engineering/research/bioengineering/neuroengineering-lab/software): Dataset#5, 2 subjects for checkboard light pattern (oddball paradigm) recorded at O1 position. 

* **Resting State**
  1. [Resting State EEG Data](https://dataverse.tdl.org/dataverse/txstatecogelectro): 22 subjects, 72 EEG Channels for a resting task of 8 mins with 4 mins of eyes closed and 4 mins of eyes open. [[Article]](https://www.frontiersin.org/articles/10.3389/fnins.2017.00425)
  2. [EID-M, EID-S](https://drive.google.com/drive/folders/1t6tL434ZOESb06ZvA4Bw1p9chzxzbRbj): 8 subjects in rest state (with eyes closed) recorded from 14 electrodes using EPOC+ for 54s at 128 Hz (7000 samples each). EID-M has three trials and EID-S is a signle trial dataset. The dataset was used to develop a person identification system through brainwaves. [[Article]](https://arxiv.org/pdf/1711.06149.pdf)
  
* **Music and EEG**
  1. [Music Imagery Information Retrieval](https://github.com/sstober/openmiir): 10 subjects, 64 EEG Channels for a music imagery task of 12 different pieces w/ different meter, length and tempo. [[Article]](https://pdfs.semanticscholar.org/cde4/b1ec89f2c05a41f1143792a890a00e89541a.pdf)
  
* **Eye-blinks/movements**
  1. [Involuntary Eye Movements during Face Perception](http://www2.hu-berlin.de/eyetracking-eeg/testdata.html): Dataset 1, 26 electrodes, 500Hz sampling rate, and 120 trials. Eye movements and pupil diameter record, EEG and EOG data is present when subject is presented a happy/sad/angry face on the screen. [[Article]](http://www.jneurosci.org/content/suppl/2009/09/30/29.39.12321.DC1/Supplemental_Material.pdf) [P.S: Dataset available on request only]
  2. [Voluntary-Involuntary Eye-Blinks](https://drive.google.com/file/d/0By5iwWd39NblS2tRWmVTdmRzZUU/view?usp=sharing): Voluntary eye-blinks (subject were asked to blink voluntarily within 1s of audio stimulus) and involuntary eye-blinks (natural) was recorded for 20 subjects on 14 electrodes using g.tec. For each subject, 3 sessions with 20 trials each are present in .mat format. [[Article]](https://www.sciencedirect.com/science/article/pii/S0925231216001569)
  
* **Miscellaneous**
  1. [MNIST Brain Digits](http://mindbigdata.com/opendb/index.html): EEG data when a digit(0-9) is shown to the subject, recorded 2s for a single subject using Minwave, EPOC, Muse, Insight. Includes over 1.2M samples. 
  2. [Imagenet Brain](http://www.mindbigdata.com/opendb/imagenet.html): A random image is shown (out of 14k images from the Imagenet ILSVRC2013 train dataset) and EEG signals are recorded for 3s for one subject. Includes over 70k samples.
  3. [Working Memory](https://github.com/pbashivan/EEGLearn/tree/master/Sample%20data): Participants briefly observe an array containing multiple English characters SET (500ms) and maintain the information for three seconds. A TEST character is then presented and participants respond by press of a button if TEST charter matches one of the characters in the SET. 15 students, 64 electrodes and 500Hz sampling rate. Only a small subset of data is available publicly. [[Original Paper]](https://www.memphis.edu/acnl/publications/pdfs/ejn2014b.pdf) [[Further Analysis in ICLR]](https://arxiv.org/pdf/1511.06448.pdf)

* **Clinical EEG**
  1. [TUH EEG Resources](https://www.isip.piconepress.com/projects/tuh_eeg/html/downloads.shtml): Massive amount of data for (i) Abnormal EEG and (ii) EEG Seizures
  
  
    
  
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
  15. http://www.physionet.org/pn6/chbmit/
  16. https://sites.google.com/site/iitrcsepradeep7/resume
  18. http://memory.psych.upenn.edu/RAM
  19. http://fcon_1000.projects.nitrc.org/indi/cmi_eeg/
  20. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8616018
  21. https://arxiv.org/pdf/1805.06427.pdf
  22. http://www.gtec.at/Research/Biosignal-Data-Sets/content/Biosignal-Data-Sets
  23. http://studycatalog.org/
  24. http://predict.cs.unm.edu/
  25. https://datadryad.org/resource/doi:10.5061/dryad.070jc
  26. https://ieee-dataport.org/data-competitions
  27. https://challengedata.ens.fr/challenges/10 

  
