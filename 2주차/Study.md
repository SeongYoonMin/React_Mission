리액트를 위한 Dockerfile

FROM : node:alpine <br>
WORKDIR : /usr/src/app <br>
COPY: package.json ./ <br>
RUN: npm install <br>
COPY: ./ ./ <br>
CMD: "npm", "run", "start" <br>

