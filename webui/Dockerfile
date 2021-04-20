FROM node
RUN npm install redis && npm install express
COPY webui.js .
COPY files /files

ENTYPOINT ["node"]
CMD ["webui.js"]
