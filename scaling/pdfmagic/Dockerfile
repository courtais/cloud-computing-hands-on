FROM python:2

WORKDIR /mci/ei1518/courtais/ASR/Kubernetes/cloud-computing-hands-on/scaling/pdfmagic

RUN pip install delegator.py
RUN pip install	web.py

EXPOSE 8080

CMD ["python", "/mci/ei1518/courtais/ASR/Kubernetes/cloud-computing-hands-on/scaling/pdfmagic/pdfmagic.py"]
