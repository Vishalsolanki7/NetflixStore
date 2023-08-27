FROM python:3
COPY . .
RUN pip install --upgrade pip
RUN pip install flask flask_cors
RUN export FLASK_APP=index.py
RUN export FLASK_ENV=development
CMD ["flask","run"]
