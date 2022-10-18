FROM alpine:3.16
RUN apk update && apk add --no-cache \
    git \
    bash \
    curl \
    wget \
    python3 \
    py3-pip
RUN pip install --upgrade pip && \
    pip install --upgrade awscli
ENV AWS_ACCESS_KEY_ID=""
ENV AWS_SECRET_ACCESS_KEY=""
ENV AWS_DEFAULT_REGION=""
CMD ["/bin/bash"]