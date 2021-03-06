## `crate:latest`

```console
$ docker pull crate@sha256:78c37c65c9ce751d4df2cd91187f6cbe4747d47f33553a020881ec780f05109d
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `crate:latest` - linux; amd64

```console
$ docker pull crate@sha256:f9c9385b9cf4fc7ad5bb313e21d437d9fc8329299fa30c95514efabda0687a7a
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **129.5 MB (129495615 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:eb8b815cf0eefc3563c858755092546fd0d868986e7df2b6ba2ad34e06cc5c69`
-	Entrypoint: `["\/docker-entrypoint.sh"]`
-	Default Command: `["crate"]`

```dockerfile
# Fri, 03 Nov 2017 22:10:27 GMT
ADD file:92bfed3f8dfbee01eab85c6a1d6bc6894c5a75f9a4e2c414e9b4d05b9fcd19d0 in / 
# Fri, 03 Nov 2017 22:10:27 GMT
CMD ["/bin/sh"]
# Sat, 04 Nov 2017 06:52:42 GMT
MAINTAINER Crate.IO GmbH office@crate.io
# Sat, 04 Nov 2017 06:52:42 GMT
ENV GOSU_VERSION=1.9
# Sat, 04 Nov 2017 06:53:07 GMT
RUN set -x     && apk add --no-cache --virtual .gosu-deps         dpkg         gnupg         curl     && export ARCH=$(echo $(dpkg --print-architecture) | cut -d"-" -f3)     && curl -o /usr/local/bin/gosu -fSL "https://github.com/tianon/gosu/releases/download/$GOSU_VERSION/gosu-$ARCH"     && curl -o /usr/local/bin/gosu.asc -fSL "https://github.com/tianon/gosu/releases/download/$GOSU_VERSION/gosu-$ARCH.asc"     && export GNUPGHOME="$(mktemp -d)"     && gpg --keyserver ha.pool.sks-keyservers.net --recv-keys B42F6819007F00F88E364FD4036A9C25BF357DD4     && gpg --batch --verify /usr/local/bin/gosu.asc /usr/local/bin/gosu     && rm -r "$GNUPGHOME" /usr/local/bin/gosu.asc     && chmod +x /usr/local/bin/gosu     && gosu nobody true     && apk del .gosu-deps
# Sat, 04 Nov 2017 06:53:08 GMT
RUN addgroup crate && adduser -G crate -H crate -D
# Tue, 28 Nov 2017 21:49:14 GMT
ENV CRATE_VERSION=2.2.4
# Tue, 28 Nov 2017 21:49:43 GMT
RUN apk add --no-cache --virtual .crate-rundeps         openjdk8-jre-base         python3         openssl         sigar     && apk add --no-cache --virtual .build-deps         curl         gnupg         tar     && curl -fSL -O https://cdn.crate.io/downloads/releases/crate-$CRATE_VERSION.tar.gz     && curl -fSL -O https://cdn.crate.io/downloads/releases/crate-$CRATE_VERSION.tar.gz.asc     && export GNUPGHOME="$(mktemp -d)"     && gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 90C23FC6585BC0717F8FBFC37FAAE51A06F6EAEB     && gpg --batch --verify crate-$CRATE_VERSION.tar.gz.asc crate-$CRATE_VERSION.tar.gz     && rm -r "$GNUPGHOME" crate-$CRATE_VERSION.tar.gz.asc     && mkdir /crate     && tar -xf crate-$CRATE_VERSION.tar.gz -C /crate --strip-components=1     && rm crate-$CRATE_VERSION.tar.gz     && ln -s /usr/bin/python3 /usr/bin/python     && rm /crate/lib/sigar/libsigar-amd64-linux.so     && apk del .build-deps
# Tue, 28 Nov 2017 21:49:45 GMT
ENV PATH=/crate/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Tue, 28 Nov 2017 21:49:45 GMT
ENV CRATE_HEAP_SIZE=512M
# Tue, 28 Nov 2017 21:49:45 GMT
VOLUME [/data]
# Tue, 28 Nov 2017 21:49:45 GMT
ADD file:c0b3bba944a2572094279072da088c4f681b13f9bed768ebd567555831729fab in /crate/config/crate.yml 
# Tue, 28 Nov 2017 21:49:46 GMT
ADD file:10c08bc017b942a11ef7f1221f33b8224b4549e98c74b9f84e2495fcfb60d8ce in /crate/config/log4j2.properties 
# Tue, 28 Nov 2017 21:49:50 GMT
COPY file:9517f117528edc569ebb34a2c1d3d7bcf342cb124f3b833a681768549d61ebfb in / 
# Tue, 28 Nov 2017 21:49:50 GMT
WORKDIR /data
# Tue, 28 Nov 2017 21:49:50 GMT
EXPOSE 4200/tcp 4300/tcp 5432/tcp
# Tue, 28 Nov 2017 21:49:51 GMT
ENTRYPOINT ["/docker-entrypoint.sh"]
# Tue, 28 Nov 2017 21:49:51 GMT
CMD ["crate"]
```

-	Layers:
	-	`sha256:b1f00a6a160cd3696edba6f13ebd1d6a5808216a78ec4b753444ab8f30483b1f`  
		Last Modified: Wed, 25 Oct 2017 23:22:48 GMT  
		Size: 2.0 MB (1970236 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:d0cc29f953de9dbd81ba60f38d391e14c549fca71fac26979c8a1004eae6ef6e`  
		Last Modified: Sat, 04 Nov 2017 06:54:27 GMT  
		Size: 592.4 KB (592359 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:4d2d49dc6f2b7793edd41d187af9928d502dfc87ee17f50e80febb09501c2085`  
		Last Modified: Sat, 04 Nov 2017 06:54:26 GMT  
		Size: 1.2 KB (1204 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:b23ef3fe0107ed46b56f1bc19b9dd5b2484eaaf195ef7d9ba82e1df7133ea987`  
		Last Modified: Tue, 28 Nov 2017 21:50:18 GMT  
		Size: 126.9 MB (126930308 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:dc3c68ce2b01e00b1d0bc972cc23f32b00e13cf92099ca5a00a9469b9a5ceb44`  
		Last Modified: Tue, 28 Nov 2017 21:50:07 GMT  
		Size: 249.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:8b9146975d83b0379c0ef1ab0b8fb9ebdf7753098e2efa3d5b759646f3a35642`  
		Last Modified: Tue, 28 Nov 2017 21:50:09 GMT  
		Size: 935.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:122808fe2018d7ebbfef070ca95d939ab478faaf512f7c2431518b1c2f4ec34d`  
		Last Modified: Tue, 28 Nov 2017 21:50:07 GMT  
		Size: 231.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:83a9385a241e9b1b7c553b3377fc564f50e2809419862dc3fac3f41c35515fd9`  
		Last Modified: Tue, 28 Nov 2017 21:50:07 GMT  
		Size: 93.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
