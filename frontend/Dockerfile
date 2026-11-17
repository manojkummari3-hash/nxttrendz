from node:22-alpine
WORKDIR /app
Copy package.json package-lock.json ./
RUN npm install
copy . .
CMD ["npm","run","dev"]
