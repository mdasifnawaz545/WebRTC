# Pulling the base image from the DH as the project requires and Node IDE in order to run the project initially.
FROM node
WORKDIR /myapp
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 5174
CMD ["npm","run","dev","--","--host"]
