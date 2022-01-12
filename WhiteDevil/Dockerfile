FROM KTBwhitedevil:latest

RUN git clone https://github.com/Ziyankp/Bixby-ser /root/whitedevil
WORKDIR /root/whitedevil/ 
ENV KL=Kerala/India
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ziyankp/White

CMD ["node","white", "bot.js"]
