FROM node:latest 

WORKDIR backend/

COPY ./ . 

RUN npm i 

EXPOSE 80

ENTRYPOINT ["--env-file=.env.production","npm", "run", "start"]