FROM python:3.9-alpine

WORKDIR /user-app

COPY . ./

RUN pip install -r requirements.txt

EXPOSE 3001

CMD ["flask", "run", "--host=0.0.0.0", "--port=3001"]