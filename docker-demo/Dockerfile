FROM node:6

WORKDIR /app
EXPOSE 3000

# Install dependencies
ADD ./package.json .
RUN npm install

# Add app
ADD ./src ./src
CMD node ./src/bin/www