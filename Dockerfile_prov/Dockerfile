FROM malumondelli/bioworkbench 

RUN wget https://zenodo.org/record/1303382/files/swift_provenance.db.gz
#https://zenodo.org/record/1242591/files/swift_provenance.db.gz
RUN mv /root/swift_provenance.db.gz /srv/shiny-server/workbench/swift_provenance.db.gz
RUN gunzip /srv/shiny-server/workbench/swift_provenance.db.gz



