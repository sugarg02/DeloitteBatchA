FROM continuumio/anaconda3:4.4.0
EXPOSE 5000
WORKDIR /python-docker
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
CMD python app.py