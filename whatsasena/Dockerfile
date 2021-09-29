FROM fusuf/whatsasena:latest

RUN git clone https://phaticusthiccy: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@github.com/phaticusthiccy/WhatsAsenaDuplicated /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
npm install supervisor -g
RUN npm install -g npm@7.24.1
RUN yarn install --no-audit

CMD ["node", "bot.js"]
