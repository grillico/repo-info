## `golang:1-windowsservercore-ltsc2016`

```console
$ docker pull golang@sha256:b3a53771e29460c76a6f2ef6af0cd22431301422ccd5cb9c55a29ccd7134d297
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	windows version 10.0.14393.1884; amd64

### `golang:1-windowsservercore-ltsc2016` - windows version 10.0.14393.1884; amd64

```console
$ docker pull golang@sha256:fa5ef0f55865039b0e0693bd9bd0d399d89733df819ddc89871e8d9c8d77a9e4
```

-	Docker Version: 17.06.1-ee-2
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **5.5 GB (5501387396 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a1efd649e10179465d87e69fbb5ce3bd21e11e334d2074dfe9d0e6074d9785ae`
-	Default Command: `["c:\\windows\\system32\\cmd.exe"]`
-	`SHELL`: `["powershell","-Command","$ErrorActionPreference = 'Stop'; $ProgressPreference = 'SilentlyContinue';"]`

```dockerfile
# Tue, 13 Dec 2016 10:53:31 GMT
RUN Apply image 10.0.14393.0
# Mon, 13 Nov 2017 21:42:13 GMT
RUN Install update 10.0.14393.1884
# Wed, 15 Nov 2017 03:14:47 GMT
SHELL [powershell -Command $ErrorActionPreference = 'Stop'; $ProgressPreference = 'SilentlyContinue';]
# Wed, 15 Nov 2017 03:14:48 GMT
ENV GIT_VERSION=2.11.1
# Wed, 15 Nov 2017 03:14:48 GMT
ENV GIT_TAG=v2.11.1.windows.1
# Wed, 15 Nov 2017 03:14:49 GMT
ENV GIT_DOWNLOAD_URL=https://github.com/git-for-windows/git/releases/download/v2.11.1.windows.1/MinGit-2.11.1-64-bit.zip
# Wed, 15 Nov 2017 03:14:50 GMT
ENV GIT_DOWNLOAD_SHA256=668d16a799dd721ed126cc91bed49eb2c072ba1b25b50048280a4e2c5ed56e59
# Wed, 15 Nov 2017 03:16:09 GMT
RUN Write-Host ('Downloading {0} ...' -f $env:GIT_DOWNLOAD_URL); 	Invoke-WebRequest -Uri $env:GIT_DOWNLOAD_URL -OutFile 'git.zip'; 		Write-Host ('Verifying sha256 ({0}) ...' -f $env:GIT_DOWNLOAD_SHA256); 	if ((Get-FileHash git.zip -Algorithm sha256).Hash -ne $env:GIT_DOWNLOAD_SHA256) { 		Write-Host 'FAILED!'; 		exit 1; 	}; 		Write-Host 'Expanding ...'; 	Expand-Archive -Path git.zip -DestinationPath C:\git\.; 		Write-Host 'Removing ...'; 	Remove-Item git.zip -Force; 		Write-Host 'Updating PATH ...'; 	$env:PATH = 'C:\git\cmd;C:\git\mingw64\bin;C:\git\usr\bin;' + $env:PATH; 	[Environment]::SetEnvironmentVariable('PATH', $env:PATH, [EnvironmentVariableTarget]::Machine); 		Write-Host 'Verifying install ...'; 	Write-Host '  git --version'; git --version; 		Write-Host 'Complete.';
# Wed, 15 Nov 2017 03:16:10 GMT
ENV GOPATH=C:\gopath
# Wed, 15 Nov 2017 03:17:04 GMT
RUN $newPath = ('{0}\bin;C:\go\bin;{1}' -f $env:GOPATH, $env:PATH); 	Write-Host ('Updating PATH: {0}' -f $newPath); 	[Environment]::SetEnvironmentVariable('PATH', $newPath, [EnvironmentVariableTarget]::Machine);
# Wed, 15 Nov 2017 03:17:05 GMT
ENV GOLANG_VERSION=1.9.2
# Wed, 15 Nov 2017 03:21:25 GMT
RUN $url = ('https://golang.org/dl/go{0}.windows-amd64.zip' -f $env:GOLANG_VERSION); 	Write-Host ('Downloading {0} ...' -f $url); 	Invoke-WebRequest -Uri $url -OutFile 'go.zip'; 		$sha256 = '682ec3626a9c45b657c2456e35cadad119057408d37f334c6c24d88389c2164c'; 	Write-Host ('Verifying sha256 ({0}) ...' -f $sha256); 	if ((Get-FileHash go.zip -Algorithm sha256).Hash -ne $sha256) { 		Write-Host 'FAILED!'; 		exit 1; 	}; 		Write-Host 'Expanding ...'; 	Expand-Archive go.zip -DestinationPath C:\; 		Write-Host 'Verifying install ("go version") ...'; 	go version; 		Write-Host 'Removing ...'; 	Remove-Item go.zip -Force; 		Write-Host 'Complete.';
# Wed, 15 Nov 2017 03:21:28 GMT
WORKDIR C:\gopath
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
	-	`sha256:a4bd6cd94ee2a374930b7554f113d83a6d2d7c4fc6059acd6f2f60e0f29d2f26`  
		Last Modified: Wed, 15 Nov 2017 10:26:12 GMT  
		Size: 1.2 KB (1195 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:c7881d55c6460ffd480348b47c32558dcf6ad16f19fd42cc84ab88d7a31a7354`  
		Last Modified: Wed, 15 Nov 2017 21:07:24 GMT  
		Size: 1.2 KB (1196 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:756cb1d3ca84e98360315210209122b4d082c4e3421d0a99ddff1160004c11b9`  
		Last Modified: Wed, 15 Nov 2017 21:07:23 GMT  
		Size: 1.2 KB (1201 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:1f310c0ab0f725120b556aeb0e4692d4ebef66cce637bc43b9e1b7df371d064b`  
		Last Modified: Wed, 15 Nov 2017 21:07:24 GMT  
		Size: 1.2 KB (1168 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:4a3addc838ce72cbd7ba84f2e7a578c114e363b5528a5a5fd8b05f3d6d16ad98`  
		Last Modified: Wed, 15 Nov 2017 21:07:22 GMT  
		Size: 1.2 KB (1184 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:350521fd1ecc2a7c2752bdcd895b72b359e4fe71b72132931baf81b47e47e286`  
		Last Modified: Wed, 15 Nov 2017 21:07:35 GMT  
		Size: 29.3 MB (29278749 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:06bfbbfa8893aa7a6a2309941324b101fc1bf557072d147910116c6ff0687e85`  
		Last Modified: Wed, 15 Nov 2017 21:07:19 GMT  
		Size: 1.2 KB (1171 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:87233df14fe4ccb026fe1ae797fd76a455ecdcd8e84ef78d3c3d81b278e6cc37`  
		Last Modified: Wed, 15 Nov 2017 21:07:19 GMT  
		Size: 4.8 MB (4812673 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:fbc860abe330cf5eaed5288eab48f83fdd880d5d1a9313d7c85899aee6a2c3a7`  
		Last Modified: Wed, 15 Nov 2017 21:07:18 GMT  
		Size: 1.2 KB (1168 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:1824c2aee9b7de0611e3e17443c2cf85150738b136e0b19b61c9b08cae57866f`  
		Last Modified: Wed, 15 Nov 2017 21:08:13 GMT  
		Size: 110.3 MB (110307438 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:0582ab124bd326ad8e9a8823bbed61739765697373f651223784ec49e304e52d`  
		Last Modified: Wed, 15 Nov 2017 21:07:17 GMT  
		Size: 1.3 KB (1326 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
