FROM python:latest

ADD server.py /server/

ADD index_main.py /server/
ADD index_account.py /server/
ADD index_cuisines.py /server/
ADD index_fridge.py /server/
ADD index_inf.py /server/
ADD index_rec.py /server/
ADD index_recipes.py /server/

ADD main.html /server/
ADD recommend.html /server/
ADD recipes.html /server/
ADD cuisines.html /server/
ADD account.html /server/
ADD fridge.html /server/
ADD inform.html /server/


RUN pip install redis

WORKDIR /server/