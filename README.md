# Intel-Information-Risk-Analyzer

OS Required : **Debian linux**


1) First you need to install tesseract by `sudo apt install tesseract-ocr -y`, DO `sudo apt-get install ffmpeg libsm6 libxext6  -y` if you get any errors with   tesseract

2) Do `git clone https://github.com/blaze-fire/Intel-Information-Risk-Analyzer.git` and `cd Intel-Information-Risk-Analyzer` directory 

3) In the directory type `conda env create -f environment.yml`

4) Then type `conda activate intel-info-risk-visualizer` and in order to run the app type `streamlit run app.py`
