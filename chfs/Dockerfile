FROM alpine

COPY chfs /

RUN chmod +x chfs

CMD ./chfs --path="/data/files/|/data/media/" --rule="admin:admin123:rwd"
