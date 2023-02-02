FROM ubuntu
RUN apt-get update && apt upgrade
RUN apt-get install python3 -y
EXPOSE 5555

CMD python3 -m http.server 5555

