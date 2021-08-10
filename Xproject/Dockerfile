FROM fusuf/whatsasena:latest

RUN git clone https://github.com/myworkonlygbtes/mgx03repox /root/mgx03repox
WORKDIR /root/mgx03repox/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
