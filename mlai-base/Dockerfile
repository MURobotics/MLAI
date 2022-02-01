FROM python:3.7.12

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

RUN chmod +x launch.sh
ENTRYPOINT [ "./launch.sh" ]