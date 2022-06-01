FROM python:3.9
COPY ./stocks_products /stocks_products
WORKDIR /stocks_products
RUN pip install -r /stocks_products/requirements.txt
CMD ["python", "/stocks_products/manage.py",  "migrate"]
CMD ["python", "/stocks_products/manage.py", "runserver", "0.0.0.0:8000"]
