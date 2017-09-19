FROM alpine:latest

LABEL multi.label1="value1" \
      multi.label2="value2" \
      other="value3"

WORKDIR /home

COPY StupidLoopScript.sh StupidLoopScript.sh

ENTRYPOINT sh StupidLoopScript.sh