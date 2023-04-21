FROM python:3.10.10-slim

ENV HOME /root
COPY ./ /root/
WORKDIR /root
RUN pip install -r /root/requirements.txt
ENTRYPOINT ["python", "cluster_launcher.py"]