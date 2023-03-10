FROM python:3.8

WORKDIR /workspace5

COPY . /workspace5

RUN python -m pip install --upgrade pip

RUN pip install -r requirements.txt

ENTRYPOINT ["jupyter"]

EXPOSE 8890

CMD ["notebook","--ip","0.0.0.0","--port","8890","--allow-root","--NotebookApp.token='password'"]