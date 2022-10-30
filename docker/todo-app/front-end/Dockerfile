FROM node:14-alpine 
EXPOSE 3000
WORKDIR /todo-app/front-end
ENV REACT_APP_API_HOST=localhost
ENV REACT_APP_API_PORT=3001
ADD node_modules.tar.gz .
COPY . . 
ENTRYPOINT ["npm", "start"]
