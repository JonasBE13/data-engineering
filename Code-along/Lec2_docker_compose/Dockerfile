FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install plotly_express dash
# kör ett kommando när vi spinner upp docker containern.
# python och main.py ska köras.
# från image spinner vi upp en docker container
# som är ett system som är isolerat från host systemet

EXPOSE 8050

CMD ["python", "./src/main.py"]