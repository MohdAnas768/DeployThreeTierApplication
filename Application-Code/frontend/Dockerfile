FROM node:14
# Work Directory
WORKDIR /app
# Copy a file start with json 
# package* means all file start with package copy the file
COPY package*.json ./
# Install a npm
RUN npm install
#COPY a file
COPY . .
# run code after make container that is a different between RUN 
CMD [ "npm", "start" ]
