## `nats:windowsservercore`

```console
$ docker pull nats@sha256:f34e1040023b4299dd3f668c1fa46a547f00808feb14939306786dc19756d8af
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	windows version 10.0.14393.1884; amd64

### `nats:windowsservercore` - windows version 10.0.14393.1884; amd64

```console
$ docker pull nats@sha256:ab745e120202a3c4c2b0356f262c56bf729b641a1165eb3524033fd6255a92a6
```

-	Docker Version: 17.06.1-ee-2
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **5.4 GB (5359469214 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:3a70a7c3125fbc5b54c46faac050a7db0ecffaefbe5e4a240a784180f6424f6f`
-	Entrypoint: `["gnatsd"]`
-	Default Command: `["-c","gnatsd.conf"]`

```dockerfile
# Tue, 13 Dec 2016 10:53:31 GMT
RUN Apply image 10.0.14393.0
# Mon, 13 Nov 2017 21:42:13 GMT
RUN Install update 10.0.14393.1884
# Tue, 14 Nov 2017 23:32:14 GMT
RUN cmd /S /C #(nop)  ENV NATS_DOCKERIZED=1
# Wed, 15 Nov 2017 00:24:57 GMT
RUN cmd /S /C #(nop) WORKDIR C:\gnatsd
# Wed, 15 Nov 2017 00:24:58 GMT
RUN cmd /S /C #(nop) COPY file:61c1931f3ccb93e5489015f8e20111fb3b675785d0003458700c148a3daff2df in gnatsd.exe 
# Wed, 15 Nov 2017 00:25:00 GMT
RUN cmd /S /C #(nop) COPY file:8fad70d15db71db30b9945fba2b3d29035a631ee4fe410e797aef6981c2a1879 in gnatsd.conf 
# Wed, 15 Nov 2017 00:25:00 GMT
RUN cmd /S /C #(nop)  EXPOSE 4222/tcp 6222/tcp 8222/tcp
# Wed, 15 Nov 2017 00:25:01 GMT
RUN cmd /S /C #(nop)  ENTRYPOINT ["gnatsd"]
# Wed, 15 Nov 2017 00:25:02 GMT
RUN cmd /S /C #(nop)  CMD ["-c" "gnatsd.conf"]
```

-	Layers:
	-	`sha256:3889bb8d808bbae6fa5a33e07093e65c31371bcf9e4c38c21be6b9af52ad1548`  
		Last Modified: Tue, 13 Dec 2016 10:53:31 GMT  
		Size: 4.1 GB (4069985900 bytes)  
		MIME: application/vnd.docker.image.rootfs.foreign.diff.tar.gzip
	-	`sha256:ead9f4ead3c5a712cb213a5318f4a8bf3604bc16e16ce4f7cf0b66f7d2073282`  
		Last Modified: Mon, 13 Nov 2017 21:42:13 GMT  
		Size: 1.3 GB (1286993027 bytes)  
		MIME: application/vnd.docker.image.rootfs.foreign.diff.tar.gzip
	-	`sha256:139303713dae40ff590b66954070b5354fdf1da3648e90a3888b4c2e9a8a197a`  
		Last Modified: Tue, 14 Nov 2017 23:32:38 GMT  
		Size: 1.2 KB (1197 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:88c5a48af7889eb60f20b1263b024aef25c2a274cfeb0b25016537f6a1f85969`  
		Last Modified: Wed, 15 Nov 2017 00:25:24 GMT  
		Size: 1.3 KB (1343 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:c0d830ff3fda976c1c1e35f39f9a3ff1445cffb2b5136f9eea02108f2aaeff4c`  
		Last Modified: Wed, 15 Nov 2017 00:25:22 GMT  
		Size: 2.5 MB (2482307 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:d9fe3d73fa90c13b9b78e44bddb390a0787be8073f7b9e3b28af190f9a81f904`  
		Last Modified: Wed, 15 Nov 2017 00:25:21 GMT  
		Size: 1.9 KB (1856 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:be9a4344df4263899eb4e89730d08bb31fe7f1719fd9b26bd7416fe917d8d5fc`  
		Last Modified: Wed, 15 Nov 2017 00:25:21 GMT  
		Size: 1.2 KB (1199 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:8564c105386fa8971354829104f18bb3e969eefd47decd406f43d8a3e2df3030`  
		Last Modified: Wed, 15 Nov 2017 00:25:22 GMT  
		Size: 1.2 KB (1193 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:94ed1b6549b1da29d43ca17e6ddb6425fd421af32235ab3a72a04a7d93fca2de`  
		Last Modified: Wed, 15 Nov 2017 00:25:21 GMT  
		Size: 1.2 KB (1192 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
