# Mobile cloud access times datasets

This repository contain datasets for cloud access times across various contexts, locations, access network types, and mobile network operators (MNOs). The data is organized into two primary directories: one for LTE/4G data and the other for Wi-Fi data. Each dataset corresponds to specific scenarios outlined in the research paper. The datasets have been cleaned and represent the Round Trip Time (RTT) ping values in milliseconds (ms).

These datasets can be used for analyzing cloud access times in different scenarios and environments. Researchers and developers can leverage this data for mobile application testing, performance analysis, and mobile access network studies.

The repository is structured as follows:

```
/Cloud-Access-Time-Dataset-Archive
├── LTE
│   ├── Indoor-DE-eu-central-1b-MNO1.dat
│   ├── Outdoor-DE-us-east-1b-MNO3.dat
│   ├── Train-DE-ap-south-1-MNO1.dat
│   ├── Vehicle-DE-us-east-1b-MNO1.dat  
│   ├── Walk-DE-eu-central-1b-MNO3.dat
│   └── Walk-US-us-east-1b-MNO2.dat
│
└── WiFi
    ├── Cafe-DE-us-east-1b.dat
    ├── Cafe-US-us-east-1b.dat
    ├── Campus-DE-us-east-1b.dat
    ├── Dormitory-DE-us-east-1b.dat
    ├── Home-DE-eu-central-1b.dat
    └── Office-DE-eu-central-1b.dat
```

Each file is named using the following convention: <scenario>_<mobile_location>_<cloud_backend_location>-<MNO>.dat


## Background
The datasets were collected as a part of research for the paper [Generation of realistic cloud access times for mobile application testing using transfer learning](https://www.sciencedirect.com/science/article/abs/pii/S0140366421001067)

## License
The datasets are licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

