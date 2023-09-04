FROM baptistearno/typebot-builder:2.16
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENV GOOGLE_CLIENT_ID
ENV GOOGLE_CLIENT_SECRET

EXPOSE 8080
ENTRYPOINT ["/entrypoint.sh"]
