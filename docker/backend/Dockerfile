from node:12

COPY *.json ./
COPY packages packages
RUN npx lerna bootstrap

ENV NODE_ENV 'production'

CMD npx lerna exec --scope @crowdaq/backend npm run start
