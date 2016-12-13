FROM alpine:3.4
RUN apk update && apk add ca-certificates && apk add openssl

WORKDIR /opt
RUN wget https://releases.hashicorp.com/terraform/0.7.13/terraform_0.7.13_linux_amd64.zip \
  && unzip terraform_0.7.13_linux_amd64.zip \
  && rm terraform_0.7.13_linux_amd64.zip

RUN ln -s /opt/terraform /bin/terraform

WORKDIR /var/terraform

ENTRYPOINT ["terraform"]
