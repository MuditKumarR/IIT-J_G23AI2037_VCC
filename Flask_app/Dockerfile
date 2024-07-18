FROM python:3.11
WORKDIR /usr/src/app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
CMD ["python", "./dummy_app.py"]docker run -p 8888:5000 yourusername/catnip