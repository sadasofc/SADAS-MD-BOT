FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/sadasofc/SADAS-MD-BOT /root/sadas ofc
WORKDIR /root/sadas ofc/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
