FROM python:3.7-slim

RUN mkdir /dashboard

COPY requirements.txt /dashboard

WORKDIR /dashboard

RUN pip3 install -r requirements.txt

COPY . /dashboard

EXPOSE 9501

CMD ["streamlit", "run", "dashboard_app.py"]
