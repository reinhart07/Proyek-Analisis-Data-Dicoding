# Proyek-Analisis-Data-Dicoding
conda create --name main-ds python=3.11
conda activate main-ds
pip install -r requirements.txt

mkdir proyek_analisis_data_dicoding
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

streamlit run dashboard.py
