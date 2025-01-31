# Proyek-Analisis-Data-Dicoding
**Setup Environment Setup Environment**
conda create --name main-ds python=3.11
conda activate main-ds
pip install -r requirements.txt

**Setup Environment - Shell/Terminal**
mkdir proyek_analisis_data_dicoding
cd proyek_analisis_data
python -m venv env
source env/bin/activate  # Gunakan 'env\Scripts\activate' di Windows
pip install -r requirements.txt

**Run steamlit app**
pip install -r requirements.txt
streamlit run dashboard.py
