FROM continuumio/miniconda3:latest

RUN apt-get update
RUN apt-get install pandoc -y
RUN apt-get install pandoc-citeproc -y

RUN conda install matplotlib=3.5.0 -y
RUN conda install pandas=1.3.4 -y
RUN conda install requests=2.26.0 -y
RUN conda install scikit-learn=1.0.1 -y
RUN conda install vega_datasets=0.7.0 -y
RUN conda install jinja2=3.0.2 -y
RUN conda install lightgbm=3.2.1 -y
RUN conda install py-xgboost=1.5.0 -y
RUN conda install catboost=0.26.1 -y
RUN conda install openpyxl=3.0.9 -y


RUN pip install graphviz==0.19
RUN pip install altair_saver==0.5.0
RUN pip install pycountry==20.7.3
RUN pip install mglearn==0.1.9
