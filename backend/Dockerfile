FROM python:3

ENV PYTHONUNBUFFERED 1
WORKDIR /django-todo-react/backend
COPY requirements.txt ./
RUN pip install -r requirements.txt
#RUN pipenv shell

COPY . ./
EXPOSE 8000
RUN python3 manage.py runserver