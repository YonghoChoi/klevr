FROM ubuntu
LABEL version=0.2

COPY ./conf/* /conf/
COPY ./klevr-manager /
COPY ./wait-for-it.sh /
COPY ./init-db.sh /
CMD [ "./klevr-manager" ]
EXPOSE 8090

