FROM pytorch/pytorch:1.3-cuda10.1-cudnn7-runtime
MAINTAINER caffeinism <caffeinism@estsoft.com>

RUN pip install jupyter

EXPOSE 8888

WORKDIR /notebook

CMD ["bash", "-c", "source /etc/bash.bashrc && jupyter notebook --notebook-dir=/notebook --ip 0.0.0.0 --no-browser --allow-root"]
