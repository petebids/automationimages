FROM petebids/3270:v1

ADD app.py /

RUN pip3 install setuptools
RUN pip3 install py3270 

CMD ["python3", "app.py"]