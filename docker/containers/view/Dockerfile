# Image
FROM node:16-alpine

# Set up the working directory
WORKDIR /app/view
COPY . .

RUN yarn install

EXPOSE 3000
CMD ["yarn", "dev"]
