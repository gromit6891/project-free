FROM extremeprog/mongo-sites-api:feature-admin-dbclone

RUN apt-get update; apt-get install -y --force-yes wget

RUN wget https://github.com/gromit6891/system-msa/raw/master/client-msa.tar.gz
RUN tar -zxvf client-msa.tar.gz

RUN mv mongodb/* /var/lib/mongodb/

#RUN ${ADDITIONAL_COMMAND}

CMD /bin/true
