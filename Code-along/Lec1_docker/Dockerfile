FROM python:3.11

# host container
# lägger in vår main.py i mappen .
ADD main.py .


RUN pip install plotly_express dash
# kör ett kommando när vi spinner upp docker containern.
# python och main.py ska köras.
# från image spinner vi upp en docker container
# som är ett system som är isolerat från host systemet



CMD ["python", "./main.py"]