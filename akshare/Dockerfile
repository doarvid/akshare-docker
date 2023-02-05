FROM python:3.7

WORKDIR /app

COPY requirements.txt ./
# RUN pip install -i https://pypi.tuna.tsinghua.edu.cn/simple  --no-cache-dir -r requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python", "-m", "aktools","--host","0.0.0.0" ]
