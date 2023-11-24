FROM python:slim
RUN apt-get update 
RUN apt-get install -y sudo 
RUN sudo apt-get install gcc -y 
RUN sudo apt-get install gfortran -y
RUN sudo apt-get install gdb -y
RUN pip install  fprettify 

RUN sudo apt-get install git-all -y
RUN sudo apt install cmake -y
RUN  pip install -U pip
RUN pip install --upgrade --force-reinstall fypp
RUN sudo apt-get install build-essential -y
 RUN echo 'PATH="$PATH:/usr/local/include"' >> ~/.bashrc
  RUN echo 'PATH="$PATH: /usr/local/lib"' >> ~/.bashrc
 # source ~/.bashrc
