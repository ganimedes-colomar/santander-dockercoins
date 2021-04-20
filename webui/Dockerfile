FROM node
RUN npm install redis && npm install express
COPY webui.js .
COPY files /files

ENTRYPOINT ["node"]
CMD ["webui.js"]
