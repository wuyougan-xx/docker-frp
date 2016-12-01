FROM alpine:3.4

COPY frpc /usr/local/bin/

RUN chmod +x /usr/local/bin/frpc && \
        mkdir /etc/frp

COPY frpc.ini /etc/frp/

CMD ["frpc", "-c", "/etc/frp/frpc.ini"]

