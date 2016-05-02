FROM tensorflow/tensorflow:latest

MAINTAINER Gabriele Teotino <gabriele@teosoft.it>
ENV REFRESHED_AT 2016-05-02

RUN pip install --upgrade pip
RUN pip --no-cache-dir install pandas
RUN pip --no-cache-dir install sklearn

VOLUME /workspace

# TensorBoard
EXPOSE 6006
# IPython
EXPOSE 8888

WORKDIR "/workspace"

CMD ["/run_jupyter.sh"]