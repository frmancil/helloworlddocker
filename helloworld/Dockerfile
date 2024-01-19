FROM node:latest
WORKDIR /Mancilla_Francisco_site
COPY package.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
