FROM node
WORKDIR /myapp
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5174
EXPOSE 3000
CMD ["node","app.js"]
