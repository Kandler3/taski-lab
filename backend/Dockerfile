FROM  python:3.10
EXPOSE 8000
WORKDIR /app 
COPY requirements.txt /app

RUN python -m pip install setuptools
RUN pip3 install -r requirements.txt --no-cache-dir

COPY . /app

RUN python3 manage.py migrate

CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000", "--noreload"]