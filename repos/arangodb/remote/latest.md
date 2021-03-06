## `arangodb:latest`

```console
$ docker pull arangodb@sha256:5b6e66f7f5090eb9c85cc9ec6c09f6898b2da16367440c49608496ba0d1e0cdd
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `arangodb:latest` - linux; amd64

```console
$ docker pull arangodb@sha256:b6291d9fc5f4de3c7b113eebc46043279f5d550ab705801e96e655e32ad98145
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **111.9 MB (111923894 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c93b9ab933a18dd320490cfc61baa218893e67484e2151de7e96d856f666e5e2`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["arangod"]`

```dockerfile
# Sat, 04 Nov 2017 05:26:40 GMT
ADD file:a71e077a42995a68ffe4834d85cfe26af4ea12aa8ed43decc03cc487124b1f70 in / 
# Sat, 04 Nov 2017 05:26:40 GMT
CMD ["bash"]
# Sat, 04 Nov 2017 18:07:53 GMT
MAINTAINER Frank Celler <info@arangodb.com>
# Sat, 04 Nov 2017 18:07:53 GMT
ENV ARCHITECTURE=amd64
# Sat, 04 Nov 2017 18:07:54 GMT
ENV DEB_PACKAGE_VERSION=1
# Mon, 20 Nov 2017 19:21:26 GMT
ENV ARANGO_VERSION=3.2.8
# Mon, 20 Nov 2017 19:21:27 GMT
ENV ARANGO_URL=https://download.arangodb.com/arangodb32/Debian_9.0
# Mon, 20 Nov 2017 19:21:27 GMT
ENV ARANGO_PACKAGE=arangodb3-3.2.8-1_amd64.deb
# Mon, 20 Nov 2017 19:21:27 GMT
ENV ARANGO_PACKAGE_URL=https://download.arangodb.com/arangodb32/Debian_9.0/amd64/arangodb3-3.2.8-1_amd64.deb
# Mon, 20 Nov 2017 19:21:27 GMT
ENV ARANGO_SIGNATURE_URL=https://download.arangodb.com/arangodb32/Debian_9.0/amd64/arangodb3-3.2.8-1_amd64.deb.asc
# Mon, 20 Nov 2017 19:21:38 GMT
RUN apt-get update &&     apt-get install -y --no-install-recommends gpg dirmngr     &&     rm -rf /var/lib/apt/lists/*
# Mon, 20 Nov 2017 19:21:42 GMT
RUN gpg --keyserver hkps://hkps.pool.sks-keyservers.net --recv-keys CD8CB0F1E0AD5B52E93F41E7EA93F5E56E751E9B
# Mon, 20 Nov 2017 19:21:50 GMT
RUN apt-get update &&     apt-get install -y --no-install-recommends         libjemalloc1         ca-certificates         pwgen         curl     &&     rm -rf /var/lib/apt/lists/*
# Mon, 20 Nov 2017 19:21:51 GMT
RUN mkdir /docker-entrypoint-initdb.d
# Mon, 20 Nov 2017 19:22:08 GMT
RUN curl --fail -O ${ARANGO_SIGNATURE_URL} &&           curl --fail -O ${ARANGO_PACKAGE_URL} &&             gpg --verify ${ARANGO_PACKAGE}.asc &&     (echo arangodb3 arangodb3/password password test | debconf-set-selections) &&     (echo arangodb3 arangodb3/password_again password test | debconf-set-selections) &&     DEBIAN_FRONTEND="noninteractive" dpkg -i ${ARANGO_PACKAGE} &&     rm -rf /var/lib/arangodb3/* &&     sed -ri         -e 's!127\.0\.0\.1!0.0.0.0!g'         -e 's!^(file\s*=).*!\1 -!'         -e 's!^#\s*uid\s*=.*!uid = arangodb!'         -e 's!^#\s*gid\s*=.*!gid = arangodb!'         /etc/arangodb3/arangod.conf     &&     rm -f ${ARANGO_PACKAGE}*
# Mon, 20 Nov 2017 19:22:08 GMT
VOLUME [/var/lib/arangodb3 /var/lib/arangodb3-apps]
# Mon, 20 Nov 2017 19:22:09 GMT
COPY file:bfaf23a38db232ba7808c846a5fb078a1b190c5fa005d63561e6805ab638afeb in /entrypoint.sh 
# Mon, 20 Nov 2017 19:22:09 GMT
ENTRYPOINT ["/entrypoint.sh"]
# Mon, 20 Nov 2017 19:22:09 GMT
EXPOSE 8529/tcp
# Mon, 20 Nov 2017 19:22:10 GMT
CMD ["arangod"]
```

-	Layers:
	-	`sha256:3e17c6eae66cd23c59751c8d8f5eaf7044e0611dc5cebb12b1273be07cdac242`  
		Last Modified: Mon, 09 Oct 2017 21:41:38 GMT  
		Size: 45.1 MB (45129088 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:cd46798682c2f2fb8af1fb635e6971757a6a0c16db2cbf53a3bfe2c975e65c63`  
		Last Modified: Mon, 20 Nov 2017 19:26:35 GMT  
		Size: 6.9 MB (6920920 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:4aace3253c1317558a4dda0cfb3917a20871456cc40b675db8e64c7b5ba3cf3b`  
		Last Modified: Mon, 20 Nov 2017 19:26:31 GMT  
		Size: 3.5 KB (3469 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:5ef9acc918f2ecb42363c7173e4ff27795b8a3f1d578c58f35e82fa3fc0b635c`  
		Last Modified: Mon, 20 Nov 2017 19:26:33 GMT  
		Size: 7.4 MB (7351413 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:a960a1847b8efd7013b5bcdc87da1c0f2e99d5d9d70a4e0a1f989a16913c97f9`  
		Last Modified: Mon, 20 Nov 2017 19:26:31 GMT  
		Size: 115.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:46e2e3410d9f42033e7733834f7df7b4046ec73aa6fe146ddaa29521e1f1aaae`  
		Last Modified: Mon, 20 Nov 2017 19:28:28 GMT  
		Size: 52.5 MB (52517059 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:ce92b49269106a3349600703f7a37bfdeffb725abcebc6d43a2a40b19a56327b`  
		Last Modified: Mon, 20 Nov 2017 19:26:32 GMT  
		Size: 1.8 KB (1830 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
