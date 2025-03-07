FROM python:3.9

RUN pip install pandas

# location in the container where we will be doing work (pasting the datapipeline.py)
WORKDIR /app

# copy source destination
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python","pipeline.py" ]

