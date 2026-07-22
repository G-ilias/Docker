FROM python:3.8-slim
WORKDIR /app
COPY . .
RUN pip install flask redis
EXPOSE 5003
CMD ["python", "appv2.py"]