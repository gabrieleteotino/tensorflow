FROM tensorflow/tensorflow:0.8.0-devel

MAINTAINER Gabriele Teotino <gabriele@teosoft.it>
ENV REFRESHED_AT 2016-04-26

RUN pip --no-cache-dir install pandas

VOLUME /data

# TensorBoard
EXPOSE 6006
# IPython
EXPOSE 8888

WORKDIR "/notebooks"

CMD ["/run_jupyter.sh"]