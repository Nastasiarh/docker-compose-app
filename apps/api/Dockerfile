FROM node:14
WORKDIR /opt/app
ADD . .
RUN nmp install && npm run build api
CMD ["node", "./dist/apps/api/main.js"]