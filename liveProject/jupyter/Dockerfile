FROM python:3.7-slim
WORKDIR /usr/src/app
RUN mkdir src
WORKDIR src
RUN python -m pip install jupyter
RUN pip list
CMD jupyter notebook --ip 0.0.0.0 --no-browser --allow-root

