FROM node
WORKDIR usr
COPY . .
#RUN npm config rm proxy
#RUN npm config rm https-proxy
RUN npm install http-server

RUN npm install mqtt


#EXPOSE 80
EXPOSE 8080
#EXPOSE 1883
CMD ["node","jj.js"]
