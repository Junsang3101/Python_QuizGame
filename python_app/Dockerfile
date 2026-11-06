FROM python:3.10-slim
WORKDIR /python_app
COPY requirements.txt .
RUN pip --no-cache-dir install -r requirements.txt
COPY . .
CMD [ "python", "src/main.py" ]