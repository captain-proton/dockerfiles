FROM neo4j:3.5.3

ENV APOC_VERSION 3.5.0.7
ENV APOC_URI https://github.com/neo4j-contrib/neo4j-apoc-procedures/releases/download/${APOC_VERSION}/apoc-${APOC_VERSION}-all.jar

ADD ${APOC_URI} plugins/

EXPOSE 7474 7473 7687

CMD ["neo4j"]


