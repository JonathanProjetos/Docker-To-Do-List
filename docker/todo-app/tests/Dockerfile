FROM mjgargani/puppeteer:trybe1.0
WORKDIR /
COPY . ./
ADD node_modules.tar.gz ./
EXPOSE 3000
CMD [ "npm", "test" ]