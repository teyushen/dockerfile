FROM frolvlad/alpine-oraclejdk8
ADD sqlcl /

RUN apk update \ 
	&& apk --no-cache add \
		bash \
		vim \
		htop \
		curl \
		procps \
		tzdata \
	&& rm -rf /var/cache/apk/*

CMD ["/bin/bash"]