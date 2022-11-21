FROM python:3.10
LABEL maintainer="Despoina Kypraiou"
EXPOSE 3111
WORKDIR /techtrends
COPY techtrends ./

RUN pip install -r requirements.txt
RUN python init_db.py
CMD ["python", "app.py"]