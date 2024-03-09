FROM python:3
LABEL maintainer="Riadh Kacem"
LABEL org.opencontainers.image.title="Hello world image"
ADD helloworld.py /
RUN pip install flask
RUN pip install flask_restful
EXPOSE 8080
CMD [ "python" , "./helloworld.py" ]