# DL-fBPM-analysis
Continuous biomarker monitoring with single molecule resolution by measuring free particle motion

**Basic software:**
1. Python

**Additional supporting software:**
1. PIP -> installation of packages such as Keras and Tensorflow
2. Jypyter notebook -> work environment

**Analysis steps:**
1. Import Libaries and functions
2. Section 'Data import and Model selection'
    - Choose the correct Deep Learning models for particle size (1 µm or 3 µm in diameter), which should be stored in the same folder.
        01: distinguishes unbound from bound states
        12: distinguises single bound from multivalent bound states.
    - Input the pixel size (µm/pixel).
    - Input the measurement framerate (Hz).
    - Specify the measurement window matching the values provided in the Deep Learing models
        1 µm particles: 60 and 100
        3 µm particles: 120 and 180
2. Section: 'Start Analyzing All .txt Files'
    - Make sure that the data files, e.g. .txt files with particle trajectories, are in the same folder.
    - Run analysis.
