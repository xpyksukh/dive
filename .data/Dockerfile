FROM alpine:latest
ADD README.md /somefile.txt
RUN mkdir /root/example
RUN cp /somefile.txt /root/example/somefile1.txt
RUN cp /somefile.txt /root/example/somefile2.txt
RUN cp /somefile.txt /root/example/somefile3.txt
RUN mv /root/example/somefile3.txt /root/saved.txt
RUN cp /root/saved.txt /root/.saved.txt
RUN rm -rf /root/example/
ADD .data/ /root/.data/
RUN cp /root/saved.txt /tmp/saved.again1.txt
RUN cp /root/saved.txt /root/.data/saved.again2.txt
