FROM python
WORKDIR /poll
EXPOSE 80
COPY . /poll
RUN pip3 install -r requirements.txt
CMD [ "flask", "run", "--host=0.0.0.0", "--port=80" ]