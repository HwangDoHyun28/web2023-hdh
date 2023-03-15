FROM python:3.9
WORKDIR /code
COPY ./requirements.txt /code/requirements.txt
RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt
COPY ./app /code/app
#CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "80"]
# 도커 컴포즈가 실행을 시켜주기 떄문에 제거
