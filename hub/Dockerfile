ARG VERSION=3.3.6

FROM quay.io/jupyterhub/k8s-hub:${VERSION}
COPY requirements.txt /tmp
RUN pip install -r /tmp/requirements.txt
RUN rm -f requirements.txt
