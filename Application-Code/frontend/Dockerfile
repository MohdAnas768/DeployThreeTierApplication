FROM node:14
# Work Directory
WORKDIR /app
# Copy a file start with json
COPY package*.json ./
# Install a npm
RUN npm install
#COPY a file
COPY . .
# run code after make container that is a different between RUN and cmd
CMD [ "npm", "start" ]
