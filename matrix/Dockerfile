FROM scratch
ADD alpine-minirootfs-3.12.0-x86_64.tar.gz /

RUN apk update && apk add cmatrix 
CMD [ "cmatrix" ]
LABEL maintainer="jmajzer" \
	 description="alpine linux with cmatrix app"