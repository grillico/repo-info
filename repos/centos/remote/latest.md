## `centos:latest`

```console
$ docker pull centos@sha256:7ce971e2495e1708709d8e3d7fd21f4e0502be31a0c73e3029653c77c34c06eb
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64
	-	linux; arm64 variant v8

### `centos:latest` - linux; amd64

```console
$ docker pull centos@sha256:3a32a170c945ffe18334b3f514fcb66f9c14001b2266c9ed8504c72db0acde11
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **73.4 MB (73426838 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:3fa822599e10c5f2080dcf647068c72022b111d31bbec0c5adb8a96e7eb5379b`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 30 Nov 2017 00:13:33 GMT
ADD file:7441d818786942af845a9a1ecdd284f3d9ff7a63909dd076302cebb4d83df781 in / 
# Thu, 30 Nov 2017 00:13:33 GMT
LABEL name=CentOS Base Image vendor=CentOS license=GPLv2 build-date=20171128
# Thu, 30 Nov 2017 00:13:33 GMT
CMD ["/bin/bash"]
```

-	Layers:
	-	`sha256:85432449fd0fabb6bef4772246d9b7948723275a4c7e4dee18728f28d79f1c2c`  
		Last Modified: Thu, 30 Nov 2017 00:19:24 GMT  
		Size: 73.4 MB (73426838 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip

### `centos:latest` - linux; arm64 variant v8

```console
$ docker pull centos@sha256:98fe5d808db716b54bbee79e7cc9b54e9425d69e737e49b865c34d31cad92df7
```

-	Docker Version: 17.06.1-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **73.1 MB (73136372 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b1dbb498d7115269f611cda22e942c5644cfd0b4021a0ac1da0eb0c1ea8bd1e1`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 14 Sep 2017 17:03:39 GMT
ADD file:82f9d72173244544d53139d0733a05d18453746cef8ee7e1d0229657e256ab83 in / 
# Thu, 14 Sep 2017 17:03:40 GMT
LABEL name=CentOS Base Image vendor=CentOS license=GPLv2 build-date=20170912
# Thu, 14 Sep 2017 17:03:41 GMT
CMD ["/bin/bash"]
```

-	Layers:
	-	`sha256:b5e1597e7528cfdae4471cafcd43e5a7c17205ddbc83696536eb85accdfd0fda`  
		Last Modified: Tue, 12 Sep 2017 18:45:12 GMT  
		Size: 73.1 MB (73136372 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
