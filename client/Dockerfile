# use node 21 as a base for the container
FROM node:21
WORKDIR /app
COPY . .

# run the build task
RUN npm i
RUN npm run build
# RUN npm run start

EXPOSE 3000

CMD npm start
