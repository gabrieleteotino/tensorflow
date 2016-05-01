FROM tensorflow/tensorflow:latest

MAINTAINER Gabriele Teotino <gabriele@teosoft.it>
ENV REFRESHED_AT 2016-05-01

RUN pip --no-cache-dir install pandas

VOLUME /workspace

# TensorBoard
EXPOSE 6006
# IPython
EXPOSE 8888

WORKDIR "/notebooks"

CMD ["/run_jupyter.sh"]