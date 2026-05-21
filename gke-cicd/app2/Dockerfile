FROM python:3.15-rc-slim-trixie

EXPOSE 8081
WORKDIR /app2

COPY . ./

RUN pip install -r requirements.txt

CMD ["python", "app.py"]