FROM nginx:alpine

LABEL org.opencontainers.image.source https://github.com/davidpegueroles/the-refactor-project-ci-cd

COPY dist /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
