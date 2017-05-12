FROM extremeprog/mongo-sites-api:feature-admin-dbclone

RUN apt-get update; apt-get install -y --force-yes wget

RUN wget https://github.com/gromit6891/system-msa/blob/master/mssp-client-msa.tar.gz
RUN tar -zxvf mongobck.tar.gz

RUN mv mongodb/* /var/lib/mongodb/

#RUN ${ADDITIONAL_COMMAND}

CMD /bin/true
