FROM huisebug/sec_re:kibana-oss-6.3.2
USER root
RUN yum -y install wget unzip
RUN wget https://github.com/anbai-inc/Kibana_Hanization/archive/master.zip && unzip master.zip && cd Kibana_Hanization-master && python main.py /usr/share/kibana
