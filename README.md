# AHN3 Download Script

This Python script allows for automated downloading of AHN3 files based on the geographical extent of a shapefile.

## Usage

1. Place the `ahn3_download.py` script in a directory on your PC.
2. Ensure there is only one shapefile in this directory.
3. Run the script. The script checks if the shapefile's projection is 'Rd_new' (also known as Rijksdriehoeksstelsel). If not, the script will stop.
4. The script checks the extent of your shapefile with the AHN3 tiles.
5. You will be prompted to choose one of the following to download: ["05m_dsm", "05m_dtm", "5m_dsm", "5m_dtm", "laz"]
6. The script will download the selected data and place the .ZIP files in the same directory where `ahn3_download.py` is located.

## Prerequisites

This script is designed to be run with Python 3 and does not require any additional libraries beyond the Python Standard Library.

## How to Run

The script can be run in any Python environment. If Python is not installed, [Anaconda](https://www.anaconda.com/products/distribution) is recommended.

To run the script:

1. Navigate to the directory containing `ahn3_download.py` using your file explorer.
2. Run the script with your Python interpreter, e.g., `C:\Users\n_de_\anaconda3\python.exe`

## Contact

For any questions, feel free to reach out to hulsterhydrology@gmail.com
