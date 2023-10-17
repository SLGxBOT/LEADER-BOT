FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/SLGxBOT/LEADER-BOT /root/SLGxBOT
WORKDIR /root/SLGxBOT/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
