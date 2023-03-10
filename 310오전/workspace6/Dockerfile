FROM python:3.8

WORKDIR /workspace6

COPY . /workspace6

RUN python -m pip install --upgrade pip

RUN pip install -r requirements.txt

ENTRYPOINT ["jupyter"]

EXPOSE 8899

CMD ["notebook","--ip","0.0.0.0","--port","8899","--allow-root","--NotebookApp.token='password'"]