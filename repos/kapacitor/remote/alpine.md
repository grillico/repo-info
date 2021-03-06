## `kapacitor:alpine`

```console
$ docker pull kapacitor@sha256:f383c66d466ae883df9908563d0f615918be41c6fe8bf0092fd64aa08adabe60
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `kapacitor:alpine` - linux; amd64

```console
$ docker pull kapacitor@sha256:101dccb14e467df81fef93d172e87dd4c35239634e0e2bbdc644fa74a6439708
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **16.9 MB (16897457 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:05d63ddd5e5a176bd025acaf5656bd9ce1f9f78bab75683ee1a4008451747489`
-	Entrypoint: `["\/entrypoint.sh"]`
-	Default Command: `["kapacitord"]`

```dockerfile
# Fri, 03 Nov 2017 22:10:18 GMT
ADD file:1e87ff33d1b6765b793888cd50e01b2bd0dfe152b7dbb4048008bfc2658faea7 in / 
# Fri, 03 Nov 2017 22:10:18 GMT
CMD ["/bin/sh"]
# Tue, 14 Nov 2017 19:01:53 GMT
RUN echo 'hosts: files dns' >> /etc/nsswitch.conf
# Tue, 14 Nov 2017 19:14:00 GMT
RUN apk add --no-cache ca-certificates &&     update-ca-certificates
# Tue, 14 Nov 2017 19:14:25 GMT
ENV KAPACITOR_VERSION=1.3.3
# Tue, 14 Nov 2017 19:14:33 GMT
RUN set -ex &&     apk add --no-cache --virtual .build-deps wget gnupg tar &&     for key in         05CE15085FC09D18E99EFB22684A14CF2582E0C5 ;     do         gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key" ||         gpg --keyserver pgp.mit.edu --recv-keys "$key" ||         gpg --keyserver keyserver.pgp.com --recv-keys "$key" ;     done &&     wget -q https://dl.influxdata.com/kapacitor/releases/kapacitor-${KAPACITOR_VERSION}-static_linux_amd64.tar.gz.asc &&     wget -q https://dl.influxdata.com/kapacitor/releases/kapacitor-${KAPACITOR_VERSION}-static_linux_amd64.tar.gz &&     gpg --batch --verify kapacitor-${KAPACITOR_VERSION}-static_linux_amd64.tar.gz.asc kapacitor-${KAPACITOR_VERSION}-static_linux_amd64.tar.gz &&     mkdir -p /usr/src &&     tar -C /usr/src -xzf kapacitor-${KAPACITOR_VERSION}-static_linux_amd64.tar.gz &&     rm -f /usr/src/kapacitor-*/kapacitor.conf &&     chmod +x /usr/src/kapacitor-*/* &&     cp -a /usr/src/kapacitor-*/* /usr/bin/ &&     rm -rf *.tar.gz* /usr/src /root/.gnupg &&     apk del .build-deps
# Tue, 14 Nov 2017 19:14:35 GMT
COPY file:4046787774ea4c49703132e9dbc6fb3a19cb54632aa7032dd8379f12b56034d9 in /etc/kapacitor/kapacitor.conf 
# Tue, 14 Nov 2017 19:14:35 GMT
EXPOSE 9092/tcp
# Tue, 14 Nov 2017 19:14:35 GMT
VOLUME [/var/lib/kapacitor]
# Tue, 14 Nov 2017 19:14:36 GMT
COPY file:440a837280df72a19ed72b91fab9bdcfd268250b241bbc22509699f880fe0d17 in /entrypoint.sh 
# Tue, 14 Nov 2017 19:14:36 GMT
ENTRYPOINT ["/entrypoint.sh"]
# Tue, 14 Nov 2017 19:14:36 GMT
CMD ["kapacitord"]
```

-	Layers:
	-	`sha256:b56ae66c29370df48e7377c8f9baa744a3958058a766793f821dadcb144a4647`  
		Last Modified: Wed, 25 Oct 2017 23:21:25 GMT  
		Size: 2.0 MB (1991435 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:26cac9feb97207d563cb8d1bc7b3c916ee79f81618908db9454602925da50b7c`  
		Last Modified: Tue, 14 Nov 2017 19:02:53 GMT  
		Size: 155.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:11ced91b7c571794d29c8c666e6b8ac7d56fdb67c704fff7d90b7dd177051850`  
		Last Modified: Tue, 14 Nov 2017 19:14:50 GMT  
		Size: 351.0 KB (351012 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:662db3dbf3e005f4c22921cbbfc7480e99c8cb979cf8beebd0b5e67d13ceb2f0`  
		Last Modified: Tue, 14 Nov 2017 19:15:11 GMT  
		Size: 14.6 MB (14554404 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:10cd84d91bc318df67caa077505a626f691440e11cf3cdb1cca01fc72017da3e`  
		Last Modified: Tue, 14 Nov 2017 19:15:07 GMT  
		Size: 223.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:304a1d879041d1825a49db7c79f636e92aa6d70adaf56c20b32cc9cbd2b295f2`  
		Last Modified: Tue, 14 Nov 2017 19:15:08 GMT  
		Size: 228.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
