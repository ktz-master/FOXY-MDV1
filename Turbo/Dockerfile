FROM fusuf/whatsasena:latest

RUN git clone https://github.com/js-masterofc/FOXY-MDV1 /root/Alexa
WORKDIR /root/Alexa/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines

CMD ["node", "bot.js"]
 
