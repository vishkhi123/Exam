# Exam
--Java
--DotNet
--WPT
это сделано
FROM node:7
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
CMD node server.js
EXPOSE 6969
exam over
done
