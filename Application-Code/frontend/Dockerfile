FROM node:14
# Work Directory
WORKDIR /usr/src/app
# Copy a file start with json
COPY package*.json ./

RUN npm install
COPY . .
CMD [ "npm", "start" ]
