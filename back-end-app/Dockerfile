FROM node:20

LABEL org.opencontainers.image.source https://github.com/davidpegueroles/the-refactor-project-ci-cd

WORKDIR /usr/src/app

COPY package.json package-lock.json ./

RUN npm ci --only=production

COPY dist ./dist

EXPOSE 3000

CMD ["node", "dist/main.js"]
