FROM alpine:3.18.3

RUN apk update && apk upgrade && apk add coreutils
ADD quick_start /quick_start
ADD get_data.sh /bin/
RUN chmod +x /bin/get_data.sh
ENTRYPOINT ["/bin/get_data.sh"]
