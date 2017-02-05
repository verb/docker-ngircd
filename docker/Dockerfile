FROM alpine:3.5
MAINTAINER Lee Verberne <lee@blarg.org>

RUN apk add --update \
	ca-certificates \
	ngircd \
&& rm -rf /var/cache/apk/*

USER ngircd
CMD ["ngircd", "--nodaemon"]
