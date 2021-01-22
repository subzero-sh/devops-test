FROM python:3
RUN pip install flask
COPY . /app
WORKDIR /app
EXPOSE 5000 
ENTRYPOINT [ "python" ] 
CMD [ "main.py" ] 