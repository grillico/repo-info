## `gradle:jre9`

```console
$ docker pull gradle@sha256:be0b1454195193d8d6ac6c1319d732d66cbdcf9315f4b2d216c3872afd44f089
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `gradle:jre9` - linux; amd64

```console
$ docker pull gradle@sha256:dc665b6bd8767f376a60def476c5a4b233787c48452520627ebd8d3129d6ccc1
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **339.5 MB (339450822 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:e16b498396150e30083097911534c19121d2c72272c7f83bc47edfba1f281714`
-	Default Command: `["gradle"]`

```dockerfile
# Sat, 04 Nov 2017 05:26:10 GMT
ADD file:d558b03d3d859cf66504349fc540b4c9ea26365896e7cc64fa87a79ca21bcf78 in / 
# Sat, 04 Nov 2017 05:26:11 GMT
CMD ["bash"]
# Sat, 04 Nov 2017 15:27:54 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Sat, 04 Nov 2017 15:28:00 GMT
RUN set -ex; 	if ! command -v gpg > /dev/null; then 		apt-get update; 		apt-get install -y --no-install-recommends 			gnupg 			dirmngr 		; 		rm -rf /var/lib/apt/lists/*; 	fi
# Sat, 04 Nov 2017 18:56:04 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzip2 		unzip 		xz-utils 	&& rm -rf /var/lib/apt/lists/*
# Sat, 04 Nov 2017 18:56:05 GMT
ENV LANG=C.UTF-8
# Sat, 04 Nov 2017 18:56:05 GMT
RUN { 		echo '#!/bin/sh'; 		echo 'set -e'; 		echo; 		echo 'dirname "$(dirname "$(readlink -f "$(which javac || which java)")")"'; 	} > /usr/local/bin/docker-java-home 	&& chmod +x /usr/local/bin/docker-java-home
# Sat, 04 Nov 2017 18:56:06 GMT
RUN ln -svT "/usr/lib/jvm/java-9-openjdk-$(dpkg --print-architecture)" /docker-java-home
# Sat, 04 Nov 2017 18:56:06 GMT
ENV JAVA_HOME=/docker-java-home
# Sat, 04 Nov 2017 18:56:09 GMT
ENV JAVA_VERSION=9.0.1+11
# Sat, 04 Nov 2017 18:56:09 GMT
ENV JAVA_DEBIAN_VERSION=9.0.1+11-1
# Sat, 04 Nov 2017 18:56:52 GMT
RUN set -ex; 		if [ ! -d /usr/share/man/man1 ]; then 		mkdir -p /usr/share/man/man1; 	fi; 		apt-get update; 	apt-get install -y 		openjdk-9-jre="$JAVA_DEBIAN_VERSION" 	; 	rm -rf /var/lib/apt/lists/*; 		[ "$(readlink -f "$JAVA_HOME")" = "$(docker-java-home)" ]; 		update-alternatives --get-selections | awk -v home="$(readlink -f "$JAVA_HOME")" 'index($3, home) == 1 { $2 = "manual"; print | "update-alternatives --set-selections" }'; 	update-alternatives --query java | grep -q 'Status: manual'
# Sat, 04 Nov 2017 21:25:35 GMT
CMD ["gradle"]
# Sat, 04 Nov 2017 21:25:35 GMT
ENV GRADLE_HOME=/opt/gradle
# Wed, 22 Nov 2017 18:09:17 GMT
ENV GRADLE_VERSION=4.3.1
# Wed, 22 Nov 2017 18:09:17 GMT
COPY file:e08b5c84a9d5a31f261ecabb5457633b5bf067646b5794580a81902b3318127f in /etc/ssl/certs/java/cacerts 
# Wed, 22 Nov 2017 18:09:17 GMT
ARG GRADLE_DOWNLOAD_SHA256=15ebe098ce0392a2d06d252bff24143cc88c4e963346582c8d88814758d93ac7
# Wed, 22 Nov 2017 18:09:26 GMT
# ARGS: GRADLE_DOWNLOAD_SHA256=15ebe098ce0392a2d06d252bff24143cc88c4e963346582c8d88814758d93ac7
RUN set -o errexit -o nounset 	&& echo "Downloading Gradle" 	&& wget --no-verbose --output-document=gradle.zip "https://services.gradle.org/distributions/gradle-${GRADLE_VERSION}-bin.zip" 		&& echo "Checking download hash" 	&& echo "${GRADLE_DOWNLOAD_SHA256} *gradle.zip" | sha256sum --check - 		&& echo "Installing Gradle" 	&& unzip gradle.zip 	&& rm gradle.zip 	&& mv "gradle-${GRADLE_VERSION}" "${GRADLE_HOME}/" 	&& ln --symbolic "${GRADLE_HOME}/bin/gradle" /usr/bin/gradle 		&& echo "Adding gradle user and group" 	&& groupadd --system --gid 1000 gradle 	&& useradd --system --gid gradle --uid 1000 --shell /bin/bash --create-home gradle 	&& mkdir /home/gradle/.gradle 	&& chown --recursive gradle:gradle /home/gradle 		&& echo "Symlinking root Gradle cache to gradle Gradle cache" 	&& ln -s /home/gradle/.gradle /root/.gradle
# Wed, 22 Nov 2017 18:09:26 GMT
USER [gradle]
# Wed, 22 Nov 2017 18:09:26 GMT
VOLUME [/home/gradle/.gradle]
# Wed, 22 Nov 2017 18:09:27 GMT
WORKDIR /home/gradle
# Wed, 22 Nov 2017 18:09:30 GMT
# ARGS: GRADLE_DOWNLOAD_SHA256=15ebe098ce0392a2d06d252bff24143cc88c4e963346582c8d88814758d93ac7
RUN set -o errexit -o nounset 	&& echo "Testing Gradle installation" 	&& gradle --version
```

-	Layers:
	-	`sha256:3a8649ffa174245c68120e05b22db9c8a8f781cc4d9c24816fb562ecf8ab9652`  
		Last Modified: Mon, 09 Oct 2017 21:39:55 GMT  
		Size: 47.6 MB (47561948 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:d3a6b3f31b5b5d71ed7ce6bd30da25edc39f05c116f292f6e2a9a206cde538ae`  
		Last Modified: Sat, 04 Nov 2017 15:46:02 GMT  
		Size: 8.6 MB (8629999 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:2aedc2c7a79b6aa0fb79d2e79a62e840b7cf70414ece1c9b6fd747267ba76d55`  
		Last Modified: Sat, 04 Nov 2017 15:46:02 GMT  
		Size: 9.5 MB (9512934 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:3f0c26c1c94d5d4a0ef5acdf7b1fbee94a790368e9614210ed68d7ecda436bea`  
		Last Modified: Sat, 04 Nov 2017 19:05:32 GMT  
		Size: 855.5 KB (855473 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:c06b9b5dba20339e663479b51caf0676be4275b4afb0d6147c828ce6b1c6dbf4`  
		Last Modified: Sat, 04 Nov 2017 19:05:31 GMT  
		Size: 247.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:575425a3fcf40302c971a89bc2e0b0b1c99c7351390118233c122fc4b6125abf`  
		Last Modified: Sat, 04 Nov 2017 19:05:31 GMT  
		Size: 131.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:d55eb4e2af396ff2ad411d2b965cf677cd6b57c24a5e87d90568a1e8d3a09b88`  
		Last Modified: Sat, 04 Nov 2017 19:06:04 GMT  
		Size: 199.8 MB (199813754 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:fbd145691b07e7039d58a3a90df720466d033a84a502834d0096f1b61a1417aa`  
		Last Modified: Wed, 22 Nov 2017 18:16:42 GMT  
		Size: 76.1 KB (76074 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:d9aa21c169111fb2dd06c2c9e4d60006c36e29fbd9773b0681fb4341d7b86bb1`  
		Last Modified: Wed, 22 Nov 2017 18:16:47 GMT  
		Size: 73.0 MB (73000124 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:51aa166e5abc602c60ee1a4106953454d268c3c7f7c382329f53c124fedc2cc9`  
		Last Modified: Wed, 22 Nov 2017 18:16:42 GMT  
		Size: 138.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
