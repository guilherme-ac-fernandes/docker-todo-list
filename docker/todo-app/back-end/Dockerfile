FROM node:14-alpine
WORKDIR /app
COPY . .
ADD node_modules.tar.gz .
CMD ["npm", "start"]
EXPOSE 3001