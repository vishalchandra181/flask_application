FROM python

COPY app.py /org/
COPY templates /org/
COPY static /org/

RUN pip install flask
RUN pip install flask_login
RUN pip install flask_sqlalchemy
RUN pip install psycopg2
RUN pip install requests

WORKDIR /org
CMD ["flask","run"]
