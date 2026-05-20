# Take pateela
FROM python:3.14

# Add ingrediants
WORKDIR /app


COPY . .

# Mix process/the items

RUN pip install -r requirements.txt

EXPOSE 8000

#Gas on

CMD ["python", "main.py"]

