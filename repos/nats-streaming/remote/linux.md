## `nats-streaming:linux`

```console
$ docker pull nats-streaming@sha256:0ff61f4e8be43abc767fd6b837b90463691259acf11ac56b1ffc350f76446701
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64
	-	linux; arm variant v7
	-	linux; arm64 variant v8

### `nats-streaming:linux` - linux; amd64

```console
$ docker pull nats-streaming@sha256:c6562f71ad50278b1655c017bc6affb4a2751c0e10cdc06df49877ea1109327d
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **3.1 MB (3137283 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:adcabc934647370d67a598e615881f54ce4bb6b6dd7e3061aabece832a4128f2`
-	Entrypoint: `["\/nats-streaming-server"]`
-	Default Command: `["-m","8222"]`

```dockerfile
# Fri, 27 Oct 2017 00:24:13 GMT
COPY file:6733e752178c9eb51ed9be40e23ad9c2baf82e81f06b968c37b5037f4155c90a in /nats-streaming-server 
# Fri, 27 Oct 2017 00:24:14 GMT
EXPOSE 4222/tcp 8222/tcp
# Fri, 27 Oct 2017 00:24:14 GMT
ENTRYPOINT ["/nats-streaming-server"]
# Fri, 27 Oct 2017 00:24:14 GMT
CMD ["-m" "8222"]
```

-	Layers:
	-	`sha256:6bc5623d46eeedca137ba7b692234af7c629329ca71736cd1eab0671b4e5d546`  
		Last Modified: Fri, 27 Oct 2017 00:24:29 GMT  
		Size: 3.1 MB (3137283 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip

### `nats-streaming:linux` - linux; arm variant v7

```console
$ docker pull nats-streaming@sha256:665e9c4feee905561dc2151d581c906ada4135e5c0f1ea8247f2192ddfd28f77
```

-	Docker Version: 17.06.0-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **2.9 MB (2930162 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:2892d7c4c79f9dfe833d7c8a11f0d0fa34fe75331588bf75f1c2d7b20ad57e58`
-	Entrypoint: `["\/nats-streaming-server"]`
-	Default Command: `["-m","8222"]`

```dockerfile
# Thu, 26 Oct 2017 23:21:37 GMT
COPY file:db1f14e5f219544bf853ff8f6d124d9cdb5ae365abe4eea2ddc40c637cc744cf in /nats-streaming-server 
# Thu, 26 Oct 2017 23:21:41 GMT
EXPOSE 4222/tcp 8222/tcp
# Thu, 26 Oct 2017 23:21:42 GMT
ENTRYPOINT ["/nats-streaming-server"]
# Thu, 26 Oct 2017 23:21:42 GMT
CMD ["-m" "8222"]
```

-	Layers:
	-	`sha256:ef57d0a0fc94ba76cee1cf4aef257b25281b5878f54670e3949e06708c61f1dc`  
		Last Modified: Thu, 26 Oct 2017 23:21:56 GMT  
		Size: 2.9 MB (2930162 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip

### `nats-streaming:linux` - linux; arm64 variant v8

```console
$ docker pull nats-streaming@sha256:8765379e4036f079e01402360593cf6dc4f3cd22dc49c0c029cb39319621637b
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **2.9 MB (2858116 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:f4f983a020a24093a446dae4f55b4031b23c6562b97bc1b6c4bb901c31a50bda`
-	Entrypoint: `["\/nats-streaming-server"]`
-	Default Command: `["-m","8222"]`

```dockerfile
# Thu, 26 Oct 2017 23:21:50 GMT
COPY file:2b535dfbe081857e0adf5bc3d51034789b9b521c31cc24343bc98b5ade496456 in /nats-streaming-server 
# Thu, 26 Oct 2017 23:21:51 GMT
EXPOSE 4222/tcp 8222/tcp
# Thu, 26 Oct 2017 23:21:52 GMT
ENTRYPOINT ["/nats-streaming-server"]
# Thu, 26 Oct 2017 23:21:52 GMT
CMD ["-m" "8222"]
```

-	Layers:
	-	`sha256:243b2fc29f0e9e0072b212560f12e46ab13fa534fc834be479df46017fa9e3a5`  
		Last Modified: Thu, 26 Oct 2017 23:22:22 GMT  
		Size: 2.9 MB (2858116 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip