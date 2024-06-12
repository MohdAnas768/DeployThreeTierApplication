# grab node 14 application
FROM node:14
# set a workdirectory
WORKDIR /usr/src/app
# all package file
COPY package*.json ./
# run npm install
RUN npm install
COPY . .
CMD ["node", "index.js"]
