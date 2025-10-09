FROM python:3.14.0 
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt 
EXPOSE 4000 
ENTRYPOINT [ "python" ] 
CMD [ "main.py" ] 
