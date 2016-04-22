FROM node:5.10

RUN npm install -g parse-server mongodb-runner

COPY ./init.sh /
RUN chmod +x /init.sh

CMD /init.sh