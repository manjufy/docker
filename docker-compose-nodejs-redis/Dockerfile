FROM node:10
WORKDIR /app
COPY package*.json ./
RUN npm install -g nodemon
RUN npm install
# If you are building your code for production
# RUN npm install --only=production

# Bundle app source
COPY . .

EXPOSE 8080
CMD ["npm", "start"]