FROM debian:9.5-slim
ADD entrypoint.sh /entrypoint.sh
RUN echo hello
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
