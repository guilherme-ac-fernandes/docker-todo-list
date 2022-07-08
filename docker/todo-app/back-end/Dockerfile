FROM node:14-alpine
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
CMD ["npm", "start"]
EXPOSE 3001