FROM ubuntu:14.04
MAINTAINER Jeyan Oorjitham <jeyoor@gmx.com>
RUN apt-get update && apt-get install -y \
   build-essential \
   cmake \
   git \
   libncurses-dev
RUN git clone https://github.com/devosoft/avida.git
RUN cd avida; ./build_avida
CMD ["bash"]
