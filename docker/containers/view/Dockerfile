# Image
FROM node:16-alpine

# Set up the working directory
WORKDIR /app/view
COPY . .
RUN yarn install
RUN yarn run build

ENV NUXT_HOST=0.0.0.0
ENV NUXT_PORT=3000

EXPOSE 3000
CMD ["yarn", "dev"]
