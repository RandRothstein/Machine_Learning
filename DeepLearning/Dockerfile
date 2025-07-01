FROM continuumio/miniconda3

COPY . /usr/src/
EXPOSE 5000
WORKDIR /usr/src/
RUN pip install -r requirements.txt
CMD ["python", "Flaskapi.py"]

