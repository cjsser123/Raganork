FROM souravkl11/raganork:test

RUN git clone https://github.com/cjsser123/Raganorkraganork
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
