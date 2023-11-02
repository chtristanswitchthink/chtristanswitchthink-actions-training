FROM alpine:3.10

# Copy entrypoint.sh to our filesystem
COPY entrypoint.sh /entrypoint.sh

# Make it executable
RUN chmod +x entrypoint.sh

# Execute entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
