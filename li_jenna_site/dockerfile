FROM node:18-alpine

WORKDIR /li_jenna_site

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=7775

EXPOSE 7775

CMD ["npm", "run", "dev"]
