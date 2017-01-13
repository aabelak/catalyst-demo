FROM gartnercatalyst/node_base
MAINTAINER Anna Belak <anna.belak@gartner.com>
ADD . /srv/app
WORKDIR /srv/app
RUN npm install
EXPOSE 80
ENTRYPOINT ["node", "index.js"]