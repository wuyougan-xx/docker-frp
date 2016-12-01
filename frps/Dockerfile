FROM alpine:3.4

COPY frps /usr/local/bin/

RUN chmod +x /usr/local/bin/frps && \
	mkdir /etc/frp

COPY frps.ini /etc/frp/

EXPOSE 80 443 4443
CMD ["frps", "-c", "/etc/frp/frps.ini"]

