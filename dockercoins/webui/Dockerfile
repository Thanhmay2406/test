FROM node:20-slim
WORKDIR /app
RUN npm install express@4 redis@4
COPY files/ /files/
COPY webui.js /app/
EXPOSE 80
CMD ["node", "/app/webui.js"]
