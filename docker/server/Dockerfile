FROM node

RUN apt update && \
    apt upgrade -y && \
    apt install -qq -y iputils-ping

WORKDIR /apps

EXPOSE 3000 3033

CMD ["/bin/bash", "/apps/start-server.sh"]