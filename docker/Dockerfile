FROM python:3.9.0-slim

RUN pip install -U platformio
RUN platformio update
# To get the test platforms
RUN pip install PyYaml
#ENV PATH /code/buildroot/bin/:/code/buildroot/tests/:${PATH}
