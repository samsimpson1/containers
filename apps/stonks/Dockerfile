FROM alpine:3.21

RUN apk update && apk add python3 py3-websocket-client py3-requests py3-mongo

WORKDIR /app

COPY src/* /app/

CMD ["sh", "-c", "python ./scrape.py"]