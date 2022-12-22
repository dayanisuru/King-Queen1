FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/dayanisuru/king-Queen1 /root/Isuru
WORKDIR /root/Isuru/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
