conda create -n lang6 python=3.13 -y
conda activate lang6

pip install -r requirements.txt

#how to run this app:
#uvicorn  main:app --reload
#streamlit run app.py
