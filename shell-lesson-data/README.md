# DataCapentry Repository

This repository contains data files and scripts related to the North Pacific Gyre research project.

## Repository Structure

```
.
├── north-pacific-gyre/
│   ├── NENE01729A.txt
│   ├── NENE01729B.txt
│   ├── NENE01736A.txt
│   ├── NENE01751A.txt
│   ├── NENE01751B.txt
│   ├── NENE01812A.txt
│   ├── NENE01843A.txt
│   ├── NENE01843B.txt
│   ├── NENE01971Z.txt
│   ├── NENE01978A.txt
│   ├── NENE01978B.txt
│   ├── NENE02018B.txt
│   ├── NENE02040A.txt
│   ├── NENE02040B.txt
│   ├── NENE02040Z.txt
│   ├── NENE02043A.txt
│   ├── NENE02043B.txt
│   ├── goodiff.sh
│   ├── goostats.sh
│   └── notes.text
└── README.md
```

## Data Files

The `north-pacific-gyre/` directory contains sample data files in text format:
- `NENE*.txt`: Sample data files from the North Pacific Gyre research
- Each file contains approximately 4KB of data

## Scripts

The repository includes two shell scripts for data processing:

### goostats.sh
A script to calculate basic statistics on the data files.

### goodiff.sh
A script to compare differences between data files.

## Usage

To use the scripts, navigate to the `north-pacific-gyre/` directory and run:

```bash
./goostats.sh NENE01729A.txt
./goodiff.sh NENE01729A.txt NENE01729B.txt
```

Make sure the scripts are executable:
```bash
chmod +x goostats.sh goodiff.sh
```

## Notes

The `notes.text` file is available for any additional documentation or observations related to the data.