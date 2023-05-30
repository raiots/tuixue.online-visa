FROM python:3.8

COPY . /App/api
WORKDIR /App/api

RUN pip install -i https://mirrors.ustc.edu.cn/pypi/web/simple -r requirements.txt

EXPOSE 8888

CMD ["python", "manage.py",  "runserver", "0:8888"]
