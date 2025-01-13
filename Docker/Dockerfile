FROM node:12.4.0

COPY ../app/ /app/

WORKDIR /app

ENV MONGODB_URL=mongodb+srv://vermaaashir:Jan%409304@cluster0.udwjv.mongodb.net/jsamazona

ENV JWT_SECRET=somethingsecret

ENV PAYPAL_CLIENT_ID=sb

ENV PORT=3000

RUN npm install

RUN npm run build

EXPOSE 3000

CMD [ "npm","start" ]
