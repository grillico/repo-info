# `ros:lunar-ros-base-stretch`

## Docker Metadata

- Image ID: `sha256:4a34d09eb62ad0dd72d73f44de883176bcbd48d8141c97f06ca3eb8fc4232b78`
- Created: `2017-08-16T01:27:03.528226017Z`
- Virtual Size: ~ 1.09 Gb  
  (total size of all layers on-disk)
- Arch: `linux`/`amd64`
- Entrypoint: `["/ros_entrypoint.sh"]`
- Command: `["bash"]`
- Environment:
  - `PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin`
  - `LANG=C.UTF-8`
  - `LC_ALL=C.UTF-8`
  - `ROS_DISTRO=lunar`

## `dpkg` (`.deb`-based packages)

### `dpkg` source package: `acl=2.2.52-3`

Binary Packages:

- `libacl1:amd64=2.2.52-3+b1`

Licenses: (parsed from: `/usr/share/doc/libacl1/copyright`)

- `GPL`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris acl=2.2.52-3
'http://deb.debian.org/debian/pool/main/a/acl/acl_2.2.52-3.dsc' acl_2.2.52-3.dsc 2025 SHA256:82e344b9ab176559a85630b74ee5a68d678d7f24b6fe8139f2fd9fcf38a48095
'http://deb.debian.org/debian/pool/main/a/acl/acl_2.2.52.orig.tar.bz2' acl_2.2.52.orig.tar.bz2 312128 SHA256:59d05b38af76baf2eddccbf08c7968a17451cc785ffecc657fcb46ce32b2631d
'http://deb.debian.org/debian/pool/main/a/acl/acl_2.2.52-3.debian.tar.xz' acl_2.2.52-3.debian.tar.xz 8740 SHA256:fc3f1178d18288993fc4ce4853b7f9dcdf0bd1fd26e4f69349a4e4e5916d1fa8
```

Likely also available for browsing at:

- https://sources.debian.net/src/acl/2.2.52-3/
- https://sources.debian.net/src/acl/2.2.52-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `adduser=3.115`

Binary Packages:

- `adduser=3.115`

Licenses: (parsed from: `/usr/share/doc/adduser/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris adduser=3.115
'http://deb.debian.org/debian/pool/main/a/adduser/adduser_3.115.dsc' adduser_3.115.dsc 1701 SHA256:754698aa19d7521080ecacc8033baa20cfa4a963021de6061c68ffa6ee15e9a1
'http://deb.debian.org/debian/pool/main/a/adduser/adduser_3.115.tar.xz' adduser_3.115.tar.xz 213620 SHA256:e7288281d4d1eec2948ba3687452ca33a8224d40c98d321bc3fbaefcf6d4c0db
```

Likely also available for browsing at:

- https://sources.debian.net/src/adduser/3.115/
- https://sources.debian.net/src/adduser/3.115/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `apr-util=1.5.4-3`

Binary Packages:

- `libaprutil1:amd64=1.5.4-3`
- `libaprutil1-dev=1.5.4-3`

Licenses: (parsed from: `/usr/share/doc/libaprutil1/copyright`, `/usr/share/doc/libaprutil1-dev/copyright`)

- `Apache-2.0`

Source:

```console
$ apt-get source -qq --print-uris apr-util=1.5.4-3
'http://deb.debian.org/debian/pool/main/a/apr-util/apr-util_1.5.4-3.dsc' apr-util_1.5.4-3.dsc 2646 SHA256:352bbbdf8d4e18014614d5a92da11b599cd04bb30ee03d9f04f26a75626371c7
'http://deb.debian.org/debian/pool/main/a/apr-util/apr-util_1.5.4.orig.tar.bz2' apr-util_1.5.4.orig.tar.bz2 694427 SHA256:a6cf327189ca0df2fb9d5633d7326c460fe2b61684745fd7963e79a6dd0dc82e
'http://deb.debian.org/debian/pool/main/a/apr-util/apr-util_1.5.4-3.debian.tar.xz' apr-util_1.5.4-3.debian.tar.xz 212220 SHA256:c5e7bfcdafb16104e324ddb6825b94577a57a5b77b809dc0330e38ecab030efa
```

Likely also available for browsing at:

- https://sources.debian.net/src/apr-util/1.5.4-3/
- https://sources.debian.net/src/apr-util/1.5.4-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `apr=1.5.2-5`

Binary Packages:

- `libapr1:amd64=1.5.2-5`
- `libapr1-dev=1.5.2-5`

Licenses: (parsed from: `/usr/share/doc/libapr1/copyright`, `/usr/share/doc/libapr1-dev/copyright`)

- `Apache-2.0`

Source:

```console
$ apt-get source -qq --print-uris apr=1.5.2-5
'http://deb.debian.org/debian/pool/main/a/apr/apr_1.5.2-5.dsc' apr_1.5.2-5.dsc 2115 SHA256:b58bb3209c8a28bff47666de6a9bf32292303fdc2433c9fafb15f2a9e6c16ca6
'http://deb.debian.org/debian/pool/main/a/apr/apr_1.5.2.orig.tar.bz2' apr_1.5.2.orig.tar.bz2 826885 SHA256:7d03ed29c22a7152be45b8e50431063736df9e1daa1ddf93f6a547ba7a28f67a
'http://deb.debian.org/debian/pool/main/a/apr/apr_1.5.2-5.debian.tar.xz' apr_1.5.2-5.debian.tar.xz 212856 SHA256:5b253cd3acc284241c3cb4a84d9d16f9c5c7775c8f7a26b3a0068ff174bacf76
```

Likely also available for browsing at:

- https://sources.debian.net/src/apr/1.5.2-5/
- https://sources.debian.net/src/apr/1.5.2-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `apt=1.4.7`

Binary Packages:

- `apt=1.4.7`
- `libapt-pkg5.0:amd64=1.4.7`

Licenses: (parsed from: `/usr/share/doc/apt/copyright`, `/usr/share/doc/libapt-pkg5.0/copyright`)

- `GPL-2`
- `GPLv2+`

Source:

```console
$ apt-get source -qq --print-uris apt=1.4.7
'http://deb.debian.org/debian/pool/main/a/apt/apt_1.4.7.dsc' apt_1.4.7.dsc 2549 SHA256:0e707ac8c40944f6da17a99494fe860b8fdbfc33f0ed115b78c4b6bf623d8a1e
'http://deb.debian.org/debian/pool/main/a/apt/apt_1.4.7.tar.xz' apt_1.4.7.tar.xz 2078852 SHA256:ea2a2e8e08daf8ea11aeaa86928d943a42ce53989165a30cc828838d470b7719
```

Likely also available for browsing at:

- https://sources.debian.net/src/apt/1.4.7/
- https://sources.debian.net/src/apt/1.4.7/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `attr=1:2.4.47-2`

Binary Packages:

- `libattr1:amd64=1:2.4.47-2+b2`

Licenses: (parsed from: `/usr/share/doc/libattr1/copyright`)

- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris attr=1:2.4.47-2
'http://deb.debian.org/debian/pool/main/a/attr/attr_2.4.47-2.dsc' attr_2.4.47-2.dsc 2027 SHA256:ee842d6d62d473acf02b494c432cf33128fa46455a09d3172c77c252449fa1a6
'http://deb.debian.org/debian/pool/main/a/attr/attr_2.4.47.orig.tar.bz2' attr_2.4.47.orig.tar.bz2 281877 SHA256:6c1208035757f5ce9b516402dd45b8299a53ae4d69ad2c352116f9cb8d7bc274
'http://deb.debian.org/debian/pool/main/a/attr/attr_2.4.47-2.debian.tar.xz' attr_2.4.47-2.debian.tar.xz 8096 SHA256:f65909562def601b1556393f5656032c058dc574ba622414ad3eb80c7b05a42a
```

Likely also available for browsing at:

- https://sources.debian.net/src/attr/1:2.4.47-2/
- https://sources.debian.net/src/attr/1:2.4.47-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `audit=1:2.6.7-2`

Binary Packages:

- `libaudit-common=1:2.6.7-2`
- `libaudit1:amd64=1:2.6.7-2`

Licenses: (parsed from: `/usr/share/doc/libaudit-common/copyright`, `/usr/share/doc/libaudit1/copyright`)

- `GPL-1`
- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris audit=1:2.6.7-2
'http://deb.debian.org/debian/pool/main/a/audit/audit_2.6.7-2.dsc' audit_2.6.7-2.dsc 2485 SHA256:3cc48a56a06f29cff62d35267471d1775a5b201cd947385566fc8f8d49bc1280
'http://deb.debian.org/debian/pool/main/a/audit/audit_2.6.7.orig.tar.gz' audit_2.6.7.orig.tar.gz 1080848 SHA256:8923917332daa7833bbc0c1d9eb012167093fbad000da4a9630fb3356aff8cdc
'http://deb.debian.org/debian/pool/main/a/audit/audit_2.6.7-2.debian.tar.xz' audit_2.6.7-2.debian.tar.xz 18820 SHA256:04b40b6ae73625c6a27a9949b28c751a83c97220f59a712b2ea9c03f5cab0fcf
```

Likely also available for browsing at:

- https://sources.debian.net/src/audit/1:2.6.7-2/
- https://sources.debian.net/src/audit/1:2.6.7-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `autotools-dev=20161112.1`

Binary Packages:

- `autotools-dev=20161112.1`

Licenses: (parsed from: `/usr/share/doc/autotools-dev/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris autotools-dev=20161112.1
'http://deb.debian.org/debian/pool/main/a/autotools-dev/autotools-dev_20161112.1.dsc' autotools-dev_20161112.1.dsc 1641 SHA256:2d55f69103b6d15043541c396ac3abd4e0d1b1d2c13a4d137f3fea277fccb21c
'http://deb.debian.org/debian/pool/main/a/autotools-dev/autotools-dev_20161112.1.tar.xz' autotools-dev_20161112.1.tar.xz 65304 SHA256:7c9405da28bbb4fc1d6d6ab9229920760b9120e5619c57cebfe594a555fd9894
```

Likely also available for browsing at:

- https://sources.debian.net/src/autotools-dev/20161112.1/
- https://sources.debian.net/src/autotools-dev/20161112.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `base-files=9.9+deb9u1`

Binary Packages:

- `base-files=9.9+deb9u1`

Licenses: (parsed from: `/usr/share/doc/base-files/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris base-files=9.9+deb9u1
'http://deb.debian.org/debian/pool/main/b/base-files/base-files_9.9+deb9u1.dsc' base-files_9.9+deb9u1.dsc 1095 SHA256:bed73a7714a0b9cf275cce1948c8f215facefc0ffc48f9598d12ddfc62ec2c02
'http://deb.debian.org/debian/pool/main/b/base-files/base-files_9.9+deb9u1.tar.xz' base-files_9.9+deb9u1.tar.xz 62876 SHA256:cb0c2f396761865d4fe427c3fd89700174546e05e958922329cf7ec70c0b0f2f
```

Likely also available for browsing at:

- https://sources.debian.net/src/base-files/9.9+deb9u1/
- https://sources.debian.net/src/base-files/9.9+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `base-passwd=3.5.43`

Binary Packages:

- `base-passwd=3.5.43`

Licenses: (parsed from: `/usr/share/doc/base-passwd/copyright`)

- `GPL-2`
- `PD`

Source:

```console
$ apt-get source -qq --print-uris base-passwd=3.5.43
'http://deb.debian.org/debian/pool/main/b/base-passwd/base-passwd_3.5.43.dsc' base-passwd_3.5.43.dsc 1749 SHA256:174a03d0df0d0f36cc186592e36472339632de094d60f9fcab370e1101a2430d
'http://deb.debian.org/debian/pool/main/b/base-passwd/base-passwd_3.5.43.tar.xz' base-passwd_3.5.43.tar.xz 52596 SHA256:7768d10e2c08469cc81342e391e059f0426afdb6eb74a3102beef59ac45ab994
```

Likely also available for browsing at:

- https://sources.debian.net/src/base-passwd/3.5.43/
- https://sources.debian.net/src/base-passwd/3.5.43/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `bash=4.4-5`

Binary Packages:

- `bash=4.4-5`

Licenses: (parsed from: `/usr/share/doc/bash/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris bash=4.4-5
'http://deb.debian.org/debian/pool/main/b/bash/bash_4.4-5.dsc' bash_4.4-5.dsc 2251 SHA256:1605c608c48f3d866e23a3d6989d23c1d910d58b2a64eee13ad0efd2d98d4b06
'http://deb.debian.org/debian/pool/main/b/bash/bash_4.4.orig.tar.xz' bash_4.4.orig.tar.xz 4878580 SHA256:819ebb6a23799e9e4ca56ac579778c46902005bd5ade4f131ed293d9f77108e7
'http://deb.debian.org/debian/pool/main/b/bash/bash_4.4-5.debian.tar.xz' bash_4.4-5.debian.tar.xz 65640 SHA256:e01cc0f49941d81bee4e81f3eeefede280a91ad9365947234f29f1cb783f9dd8
```

Likely also available for browsing at:

- https://sources.debian.net/src/bash/4.4-5/
- https://sources.debian.net/src/bash/4.4-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `binfmt-support=2.1.6-2`

Binary Packages:

- `binfmt-support=2.1.6-2`

Licenses: (parsed from: `/usr/share/doc/binfmt-support/copyright`)

- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris binfmt-support=2.1.6-2
'http://deb.debian.org/debian/pool/main/b/binfmt-support/binfmt-support_2.1.6-2.dsc' binfmt-support_2.1.6-2.dsc 2041 SHA256:20286e5237f743385d0f19a0d512b18b3dd9f00650aa8241ccee111845b0b16d
'http://deb.debian.org/debian/pool/main/b/binfmt-support/binfmt-support_2.1.6.orig.tar.gz' binfmt-support_2.1.6.orig.tar.gz 687013 SHA256:0fa539e48fecee30bf8dc45b7d592db23ec1b4550bd2ed21086b50d7f1e216a8
'http://deb.debian.org/debian/pool/main/b/binfmt-support/binfmt-support_2.1.6-2.debian.tar.xz' binfmt-support_2.1.6-2.debian.tar.xz 202504 SHA256:279733c6f239490d92d3424236cabe1a39a29264c5591b46b99557641c76d720
```

Likely also available for browsing at:

- https://sources.debian.net/src/binfmt-support/2.1.6-2/
- https://sources.debian.net/src/binfmt-support/2.1.6-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `binutils=2.28-5`

Binary Packages:

- `binutils=2.28-5`

Licenses: (parsed from: `/usr/share/doc/binutils/copyright`)

- `GFDL`
- `GPL`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris binutils=2.28-5
'http://deb.debian.org/debian/pool/main/b/binutils/binutils_2.28-5.dsc' binutils_2.28-5.dsc 4380 SHA256:a835d9d6e2d102a4c04c07259c7a2810c11935d70f43fdb31c5b01c4c01da380
'http://deb.debian.org/debian/pool/main/b/binutils/binutils_2.28.orig.tar.gz' binutils_2.28.orig.tar.gz 37814356 SHA256:db29588b0214fa69baa1a9351122cd6d0f081f2e675e6ad2aefc316ddeaf327a
'http://deb.debian.org/debian/pool/main/b/binutils/binutils_2.28-5.diff.gz' binutils_2.28-5.diff.gz 129501 SHA256:7cb92a4ca5b3afdd1c6a735ff7876b7751f83aaa887d6eb5cf0ec919bf850a35
```

Likely also available for browsing at:

- https://sources.debian.net/src/binutils/2.28-5/
- https://sources.debian.net/src/binutils/2.28-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `boost-defaults=1.62.0.1`

Binary Packages:

- `libboost-all-dev=1.62.0.1`
- `libboost-atomic-dev:amd64=1.62.0.1`
- `libboost-chrono-dev:amd64=1.62.0.1`
- `libboost-context-dev:amd64=1.62.0.1`
- `libboost-coroutine-dev:amd64=1.62.0.1`
- `libboost-date-time-dev:amd64=1.62.0.1`
- `libboost-dev:amd64=1.62.0.1`
- `libboost-exception-dev:amd64=1.62.0.1`
- `libboost-fiber-dev:amd64=1.62.0.1`
- `libboost-filesystem-dev:amd64=1.62.0.1`
- `libboost-graph-dev:amd64=1.62.0.1`
- `libboost-graph-parallel-dev=1.62.0.1`
- `libboost-iostreams-dev:amd64=1.62.0.1`
- `libboost-locale-dev:amd64=1.62.0.1`
- `libboost-log-dev=1.62.0.1`
- `libboost-math-dev:amd64=1.62.0.1`
- `libboost-mpi-dev=1.62.0.1`
- `libboost-mpi-python-dev=1.62.0.1`
- `libboost-program-options-dev:amd64=1.62.0.1`
- `libboost-python-dev=1.62.0.1`
- `libboost-random-dev:amd64=1.62.0.1`
- `libboost-regex-dev:amd64=1.62.0.1`
- `libboost-serialization-dev:amd64=1.62.0.1`
- `libboost-signals-dev:amd64=1.62.0.1`
- `libboost-system-dev:amd64=1.62.0.1`
- `libboost-test-dev:amd64=1.62.0.1`
- `libboost-thread-dev:amd64=1.62.0.1`
- `libboost-timer-dev:amd64=1.62.0.1`
- `libboost-tools-dev=1.62.0.1`
- `libboost-type-erasure-dev:amd64=1.62.0.1`
- `libboost-wave-dev:amd64=1.62.0.1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris boost-defaults=1.62.0.1
'http://deb.debian.org/debian/pool/main/b/boost-defaults/boost-defaults_1.62.0.1.dsc' boost-defaults_1.62.0.1.dsc 3699 SHA256:69103bc389bac08d02ae8de9eca30a6e06b50a5d238f7ed1316c135f022b555d
'http://deb.debian.org/debian/pool/main/b/boost-defaults/boost-defaults_1.62.0.1.tar.gz' boost-defaults_1.62.0.1.tar.gz 11656 SHA256:ac1337e04b9a0c84a09007f30d522f82a8a3be2580940ecfc17e7d41da13d0fc
```

Likely also available for browsing at:

- https://sources.debian.net/src/boost-defaults/1.62.0.1/
- https://sources.debian.net/src/boost-defaults/1.62.0.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `boost1.62=1.62.0+dfsg-4`

Binary Packages:

- `libboost-atomic1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-atomic1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-chrono1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-chrono1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-context1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-context1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-coroutine1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-coroutine1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-date-time1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-date-time1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-exception1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-fiber1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-fiber1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-filesystem1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-filesystem1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-graph-parallel1.62-dev=1.62.0+dfsg-4`
- `libboost-graph-parallel1.62.0=1.62.0+dfsg-4`
- `libboost-graph1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-graph1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-iostreams1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-iostreams1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-locale1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-locale1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-log1.62-dev=1.62.0+dfsg-4`
- `libboost-log1.62.0=1.62.0+dfsg-4`
- `libboost-math1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-math1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-mpi-python1.62-dev=1.62.0+dfsg-4`
- `libboost-mpi-python1.62.0=1.62.0+dfsg-4`
- `libboost-mpi1.62-dev=1.62.0+dfsg-4`
- `libboost-mpi1.62.0=1.62.0+dfsg-4`
- `libboost-program-options1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-program-options1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-python1.62-dev=1.62.0+dfsg-4`
- `libboost-python1.62.0=1.62.0+dfsg-4`
- `libboost-random1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-random1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-regex1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-regex1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-serialization1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-serialization1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-signals1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-signals1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-system1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-system1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-test1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-test1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-thread1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-thread1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-timer1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-timer1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-type-erasure1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-type-erasure1.62.0:amd64=1.62.0+dfsg-4`
- `libboost-wave1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost-wave1.62.0:amd64=1.62.0+dfsg-4`
- `libboost1.62-dev:amd64=1.62.0+dfsg-4`
- `libboost1.62-tools-dev=1.62.0+dfsg-4`

Licenses: (parsed from: `/usr/share/doc/libboost-atomic1.62-dev/copyright`, `/usr/share/doc/libboost-atomic1.62.0/copyright`, `/usr/share/doc/libboost-chrono1.62-dev/copyright`, `/usr/share/doc/libboost-chrono1.62.0/copyright`, `/usr/share/doc/libboost-context1.62-dev/copyright`, `/usr/share/doc/libboost-context1.62.0/copyright`, `/usr/share/doc/libboost-coroutine1.62-dev/copyright`, `/usr/share/doc/libboost-coroutine1.62.0/copyright`, `/usr/share/doc/libboost-date-time1.62-dev/copyright`, `/usr/share/doc/libboost-date-time1.62.0/copyright`, `/usr/share/doc/libboost-exception1.62-dev/copyright`, `/usr/share/doc/libboost-fiber1.62-dev/copyright`, `/usr/share/doc/libboost-fiber1.62.0/copyright`, `/usr/share/doc/libboost-filesystem1.62-dev/copyright`, `/usr/share/doc/libboost-filesystem1.62.0/copyright`, `/usr/share/doc/libboost-graph-parallel1.62-dev/copyright`, `/usr/share/doc/libboost-graph-parallel1.62.0/copyright`, `/usr/share/doc/libboost-graph1.62-dev/copyright`, `/usr/share/doc/libboost-graph1.62.0/copyright`, `/usr/share/doc/libboost-iostreams1.62-dev/copyright`, `/usr/share/doc/libboost-iostreams1.62.0/copyright`, `/usr/share/doc/libboost-locale1.62-dev/copyright`, `/usr/share/doc/libboost-locale1.62.0/copyright`, `/usr/share/doc/libboost-log1.62-dev/copyright`, `/usr/share/doc/libboost-log1.62.0/copyright`, `/usr/share/doc/libboost-math1.62-dev/copyright`, `/usr/share/doc/libboost-math1.62.0/copyright`, `/usr/share/doc/libboost-mpi-python1.62-dev/copyright`, `/usr/share/doc/libboost-mpi-python1.62.0/copyright`, `/usr/share/doc/libboost-mpi1.62-dev/copyright`, `/usr/share/doc/libboost-mpi1.62.0/copyright`, `/usr/share/doc/libboost-program-options1.62-dev/copyright`, `/usr/share/doc/libboost-program-options1.62.0/copyright`, `/usr/share/doc/libboost-python1.62-dev/copyright`, `/usr/share/doc/libboost-python1.62.0/copyright`, `/usr/share/doc/libboost-random1.62-dev/copyright`, `/usr/share/doc/libboost-random1.62.0/copyright`, `/usr/share/doc/libboost-regex1.62-dev/copyright`, `/usr/share/doc/libboost-regex1.62.0/copyright`, `/usr/share/doc/libboost-serialization1.62-dev/copyright`, `/usr/share/doc/libboost-serialization1.62.0/copyright`, `/usr/share/doc/libboost-signals1.62-dev/copyright`, `/usr/share/doc/libboost-signals1.62.0/copyright`, `/usr/share/doc/libboost-system1.62-dev/copyright`, `/usr/share/doc/libboost-system1.62.0/copyright`, `/usr/share/doc/libboost-test1.62-dev/copyright`, `/usr/share/doc/libboost-test1.62.0/copyright`, `/usr/share/doc/libboost-thread1.62-dev/copyright`, `/usr/share/doc/libboost-thread1.62.0/copyright`, `/usr/share/doc/libboost-timer1.62-dev/copyright`, `/usr/share/doc/libboost-timer1.62.0/copyright`, `/usr/share/doc/libboost-type-erasure1.62-dev/copyright`, `/usr/share/doc/libboost-type-erasure1.62.0/copyright`, `/usr/share/doc/libboost-wave1.62-dev/copyright`, `/usr/share/doc/libboost-wave1.62.0/copyright`, `/usr/share/doc/libboost1.62-dev/copyright`, `/usr/share/doc/libboost1.62-tools-dev/copyright`)

- `Boost`
- `bjam`
- `boostbook`

Source:

```console
$ apt-get source -qq --print-uris boost1.62=1.62.0+dfsg-4
'http://deb.debian.org/debian/pool/main/b/boost1.62/boost1.62_1.62.0+dfsg-4.dsc' boost1.62_1.62.0+dfsg-4.dsc 7244 SHA256:fb3ff976a0a52a693eb0ec0d3f0a33919ed6280a0a573f5d542f53b67b8dd9fc
'http://deb.debian.org/debian/pool/main/b/boost1.62/boost1.62_1.62.0+dfsg.orig.tar.bz2' boost1.62_1.62.0+dfsg.orig.tar.bz2 83837238 SHA256:203e8f9670988d57b277e4205a19336b4fba39497159ec5252ffa1e9b6158d03
'http://deb.debian.org/debian/pool/main/b/boost1.62/boost1.62_1.62.0+dfsg-4.debian.tar.xz' boost1.62_1.62.0+dfsg-4.debian.tar.xz 106484 SHA256:3eaf28f6e211bcbce50580a4a59cb52aaa0185530b2ce9fc4c6447945b661ae1
```

Likely also available for browsing at:

- https://sources.debian.net/src/boost1.62/1.62.0+dfsg-4/
- https://sources.debian.net/src/boost1.62/1.62.0+dfsg-4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `bzip2=1.0.6-8.1`

Binary Packages:

- `bzip2=1.0.6-8.1`
- `bzip2-doc=1.0.6-8.1`
- `libbz2-1.0:amd64=1.0.6-8.1`
- `libbz2-dev:amd64=1.0.6-8.1`

Licenses: (parsed from: `/usr/share/doc/bzip2/copyright`, `/usr/share/doc/bzip2-doc/copyright`, `/usr/share/doc/libbz2-1.0/copyright`, `/usr/share/doc/libbz2-dev/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris bzip2=1.0.6-8.1
'http://deb.debian.org/debian/pool/main/b/bzip2/bzip2_1.0.6-8.1.dsc' bzip2_1.0.6-8.1.dsc 2082 SHA256:d80deed11a1419ad090cb486dd2335850fd8719b809c32002dea04b485f55dbd
'http://deb.debian.org/debian/pool/main/b/bzip2/bzip2_1.0.6.orig.tar.bz2' bzip2_1.0.6.orig.tar.bz2 708737 SHA256:d70a9ccd8bdf47e302d96c69fecd54925f45d9c7b966bb4ef5f56b770960afa7
'http://deb.debian.org/debian/pool/main/b/bzip2/bzip2_1.0.6-8.1.debian.tar.bz2' bzip2_1.0.6-8.1.debian.tar.bz2 59875 SHA256:bdbe7bf29e014e44d79bb7c733fe63cae990ab50882a4a07867cf69c61ad72b7
```

Likely also available for browsing at:

- https://sources.debian.net/src/bzip2/1.0.6-8.1/
- https://sources.debian.net/src/bzip2/1.0.6-8.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `bzr=2.7.0+bzr6619-7`

Binary Packages:

- `bzr=2.7.0+bzr6619-7`
- `python-bzrlib=2.7.0+bzr6619-7`

Licenses: (parsed from: `/usr/share/doc/bzr/copyright`, `/usr/share/doc/python-bzrlib/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris bzr=2.7.0+bzr6619-7
'http://deb.debian.org/debian/pool/main/b/bzr/bzr_2.7.0+bzr6619-7.dsc' bzr_2.7.0+bzr6619-7.dsc 2505 SHA256:105c05289b628417719d5b4f485224fd28b5c757456ecc978930d6b2030f1c81
'http://deb.debian.org/debian/pool/main/b/bzr/bzr_2.7.0+bzr6619.orig.tar.gz' bzr_2.7.0+bzr6619.orig.tar.gz 10945598 SHA256:a0192999245457fbd564702518bc96453ac0f9b38ea031a466679839b346fa14
'http://deb.debian.org/debian/pool/main/b/bzr/bzr_2.7.0+bzr6619-7.debian.tar.xz' bzr_2.7.0+bzr6619-7.debian.tar.xz 68144 SHA256:166dbbe925bd56773613990e81c95b3c30a54c1b55709a63916e48334e04d05e
```

Likely also available for browsing at:

- https://sources.debian.net/src/bzr/2.7.0+bzr6619-7/
- https://sources.debian.net/src/bzr/2.7.0+bzr6619-7/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ca-certificates=20161130+nmu1`

Binary Packages:

- `ca-certificates=20161130+nmu1`

Licenses: (parsed from: `/usr/share/doc/ca-certificates/copyright`)

- `GPL-2`
- `GPL-2+`
- `MPL-2.0`

Source:

```console
$ apt-get source -qq --print-uris ca-certificates=20161130+nmu1
'http://deb.debian.org/debian/pool/main/c/ca-certificates/ca-certificates_20161130+nmu1.dsc' ca-certificates_20161130+nmu1.dsc 1886 SHA256:09e8d33c479827b070719170a9a98de7c1d4e9c7973ed8556321d08d8ae27494
'http://deb.debian.org/debian/pool/main/c/ca-certificates/ca-certificates_20161130+nmu1.tar.xz' ca-certificates_20161130+nmu1.tar.xz 298648 SHA256:77f9aca431e3122bf04aa0ffd989b723d906db4d1c106e3290e463d73c177f0e
```

Likely also available for browsing at:

- https://sources.debian.net/src/ca-certificates/20161130+nmu1/
- https://sources.debian.net/src/ca-certificates/20161130+nmu1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `cdebconf=0.227`

Binary Packages:

- `libdebconfclient0:amd64=0.227`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris cdebconf=0.227
'http://deb.debian.org/debian/pool/main/c/cdebconf/cdebconf_0.227.dsc' cdebconf_0.227.dsc 2662 SHA256:23531e6cbf4acb4edc5a2c3eda7a5095b82c396d801ade72d669b6fcf2c5aaa2
'http://deb.debian.org/debian/pool/main/c/cdebconf/cdebconf_0.227.tar.xz' cdebconf_0.227.tar.xz 272716 SHA256:df2092bb5d4fe76c318adfd1cc756f78b48a668704b6e71e161143e7c782da58
```

Likely also available for browsing at:

- https://sources.debian.net/src/cdebconf/0.227/
- https://sources.debian.net/src/cdebconf/0.227/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `cmake=3.7.2-1`

Binary Packages:

- `cmake=3.7.2-1`
- `cmake-data=3.7.2-1`

Licenses: (parsed from: `/usr/share/doc/cmake/copyright`, `/usr/share/doc/cmake-data/copyright`)

- `Apache-2.0`
- `BSD-2-clause`
- `BSD-3-clause`
- `BSD-4-clause`
- `GPL-2`
- `GPL-2+with_exception`
- `GPL-3`
- `GPL-3+with_exception`
- `ISC`
- `MIT-like`
- `zlib`

Source:

```console
$ apt-get source -qq --print-uris cmake=3.7.2-1
'http://deb.debian.org/debian/pool/main/c/cmake/cmake_3.7.2-1.dsc' cmake_3.7.2-1.dsc 2989 SHA256:f7a2c2c800a1b43f087f16c9def44cd2a59e00c00ec0321421a910dc5526d32a
'http://deb.debian.org/debian/pool/main/c/cmake/cmake_3.7.2.orig.tar.gz' cmake_3.7.2.orig.tar.gz 7361593 SHA256:dc1246c4e6d168ea4d6e042cfba577c1acd65feea27e56f5ff37df920c30cae0
'http://deb.debian.org/debian/pool/main/c/cmake/cmake_3.7.2-1.debian.tar.xz' cmake_3.7.2-1.debian.tar.xz 31872 SHA256:bb89cd5f40e67004931c978143eee41051303a0bc393853bab7c959a0fec9a5d
```

Likely also available for browsing at:

- https://sources.debian.net/src/cmake/3.7.2-1/
- https://sources.debian.net/src/cmake/3.7.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `configobj=5.0.6-2`

Binary Packages:

- `python-configobj=5.0.6-2`

Licenses: (parsed from: `/usr/share/doc/python-configobj/copyright`)

- `BSD-3-clause`

Source:

```console
$ apt-get source -qq --print-uris configobj=5.0.6-2
'http://deb.debian.org/debian/pool/main/c/configobj/configobj_5.0.6-2.dsc' configobj_5.0.6-2.dsc 2381 SHA256:9bb8577128460ff33326d3d90b8454376c83f4d41b1da61aeabdbfcbfb5e0087
'http://deb.debian.org/debian/pool/main/c/configobj/configobj_5.0.6.orig.tar.gz' configobj_5.0.6.orig.tar.gz 143664 SHA256:2e140354efcca6f558ff9ee941b435ae09a617bc071797bef62c8d6ed2033d5e
'http://deb.debian.org/debian/pool/main/c/configobj/configobj_5.0.6-2.debian.tar.xz' configobj_5.0.6-2.debian.tar.xz 7436 SHA256:dc677cd329b4a3aacebe10c5a169d9d092cc27888c3f3f9203930cacd6a0eab8
```

Likely also available for browsing at:

- https://sources.debian.net/src/configobj/5.0.6-2/
- https://sources.debian.net/src/configobj/5.0.6-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `console-bridge=0.3.2-1`

Binary Packages:

- `libconsole-bridge-dev:amd64=0.3.2-1`
- `libconsole-bridge0.2v5:amd64=0.3.2-1`

Licenses: (parsed from: `/usr/share/doc/libconsole-bridge-dev/copyright`, `/usr/share/doc/libconsole-bridge0.2v5/copyright`)

- `BSD-3-clause`

Source:

```console
$ apt-get source -qq --print-uris console-bridge=0.3.2-1
'http://deb.debian.org/debian/pool/main/c/console-bridge/console-bridge_0.3.2-1.dsc' console-bridge_0.3.2-1.dsc 1947 SHA256:4287ea47563a53e505d1c416b0be23292e367721b5d5541894155c4e76c7206f
'http://deb.debian.org/debian/pool/main/c/console-bridge/console-bridge_0.3.2.orig.tar.gz' console-bridge_0.3.2.orig.tar.gz 231243 SHA256:fd12e48c672cb9c5d516d90429c4a7ad605859583fc23d98258c3fa7a12d89f4
'http://deb.debian.org/debian/pool/main/c/console-bridge/console-bridge_0.3.2-1.debian.tar.xz' console-bridge_0.3.2-1.debian.tar.xz 4016 SHA256:e399cdf7fcbead93301e1061aac0460ed49f85c58f6911b120776a7e3cf02ad0
```

Likely also available for browsing at:

- https://sources.debian.net/src/console-bridge/0.3.2-1/
- https://sources.debian.net/src/console-bridge/0.3.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `coreutils=8.26-3`

Binary Packages:

- `coreutils=8.26-3`

Licenses: (parsed from: `/usr/share/doc/coreutils/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris coreutils=8.26-3
'http://deb.debian.org/debian/pool/main/c/coreutils/coreutils_8.26-3.dsc' coreutils_8.26-3.dsc 1955 SHA256:f62ab642e46e02c470cc045316643de530a0be50446151a5e449ca12da6485c4
'http://deb.debian.org/debian/pool/main/c/coreutils/coreutils_8.26.orig.tar.xz' coreutils_8.26.orig.tar.xz 5810244 SHA256:155e94d748f8e2bc327c66e0cbebdb8d6ab265d2f37c3c928f7bf6c3beba9a8e
'http://deb.debian.org/debian/pool/main/c/coreutils/coreutils_8.26-3.debian.tar.xz' coreutils_8.26-3.debian.tar.xz 22392 SHA256:cef6a15eb95d9e7bc992bca95010bc5ea9e25e98d8f4f668a698eee534d14b93
```

Likely also available for browsing at:

- https://sources.debian.net/src/coreutils/8.26-3/
- https://sources.debian.net/src/coreutils/8.26-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `curl=7.52.1-5`

Binary Packages:

- `libcurl3:amd64=7.52.1-5`
- `libcurl3-gnutls:amd64=7.52.1-5`

Licenses: (parsed from: `/usr/share/doc/libcurl3/copyright`, `/usr/share/doc/libcurl3-gnutls/copyright`)

- `BSD-3-Clause`
- `BSD-4-Clause`
- `ISC`
- `curl`
- `other`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris curl=7.52.1-5
'http://deb.debian.org/debian/pool/main/c/curl/curl_7.52.1-5.dsc' curl_7.52.1-5.dsc 2765 SHA256:40e5e7c680d0246e12bdebf4f84949412c7846d95708c688df9dd7e77119960e
'http://deb.debian.org/debian/pool/main/c/curl/curl_7.52.1.orig.tar.gz' curl_7.52.1.orig.tar.gz 3504621 SHA256:a8984e8b20880b621f61a62d95ff3c0763a3152093a9f9ce4287cfd614add6ae
'http://deb.debian.org/debian/pool/main/c/curl/curl_7.52.1-5.debian.tar.xz' curl_7.52.1-5.debian.tar.xz 33004 SHA256:67e9388c5562edbdd63fa31a892d446bd7dee18207a62ec367bc925f6ce50fcf
```

Likely also available for browsing at:

- https://sources.debian.net/src/curl/7.52.1-5/
- https://sources.debian.net/src/curl/7.52.1-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `cyrus-sasl2=2.1.27~101-g0780600+dfsg-3`

Binary Packages:

- `libsasl2-2:amd64=2.1.27~101-g0780600+dfsg-3`
- `libsasl2-modules-db:amd64=2.1.27~101-g0780600+dfsg-3`

Licenses: (parsed from: `/usr/share/doc/libsasl2-2/copyright`, `/usr/share/doc/libsasl2-modules-db/copyright`)

- `BSD-4-clause`
- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris cyrus-sasl2=2.1.27~101-g0780600+dfsg-3
'http://deb.debian.org/debian/pool/main/c/cyrus-sasl2/cyrus-sasl2_2.1.27~101-g0780600+dfsg-3.dsc' cyrus-sasl2_2.1.27~101-g0780600+dfsg-3.dsc 3176 SHA256:abc0b2b0e8757195689821a724037c2017f8d06d63d357e1663d679226ef71d4
'http://deb.debian.org/debian/pool/main/c/cyrus-sasl2/cyrus-sasl2_2.1.27~101-g0780600+dfsg.orig.tar.xz' cyrus-sasl2_2.1.27~101-g0780600+dfsg.orig.tar.xz 1143888 SHA256:69f34971f768e7ee6a6b647ec2d16a5a72a854ecd4602b019d5f79ba61063fdc
'http://deb.debian.org/debian/pool/main/c/cyrus-sasl2/cyrus-sasl2_2.1.27~101-g0780600+dfsg-3.debian.tar.xz' cyrus-sasl2_2.1.27~101-g0780600+dfsg-3.debian.tar.xz 94664 SHA256:5094c002044588381e417c112f0f85d33242651f2739783b4dbd673321e7a386
```

Likely also available for browsing at:

- https://sources.debian.net/src/cyrus-sasl2/2.1.27~101-g0780600+dfsg-3/
- https://sources.debian.net/src/cyrus-sasl2/2.1.27~101-g0780600+dfsg-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `dash=0.5.8-2.4`

Binary Packages:

- `dash=0.5.8-2.4`

Licenses: (parsed from: `/usr/share/doc/dash/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris dash=0.5.8-2.4
'http://deb.debian.org/debian/pool/main/d/dash/dash_0.5.8-2.4.dsc' dash_0.5.8-2.4.dsc 1461 SHA256:c83f68c3727e9fd3691117d1f67a2bd049ae2411d2137d50ea6d36122cec6482
'http://deb.debian.org/debian/pool/main/d/dash/dash_0.5.8.orig.tar.gz' dash_0.5.8.orig.tar.gz 223028 SHA256:c6db3a237747b02d20382a761397563d813b306c020ae28ce25a1c3915fac60f
'http://deb.debian.org/debian/pool/main/d/dash/dash_0.5.8-2.4.diff.gz' dash_0.5.8-2.4.diff.gz 44058 SHA256:230717c04af659a6a09b2c39158d9167fdd3392a6716c0ff36fe40dff1ca8b9d
```

Likely also available for browsing at:

- https://sources.debian.net/src/dash/0.5.8-2.4/
- https://sources.debian.net/src/dash/0.5.8-2.4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `db5.3=5.3.28-12`

Binary Packages:

- `libdb5.3:amd64=5.3.28-12+b1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris db5.3=5.3.28-12
'http://deb.debian.org/debian/pool/main/d/db5.3/db5.3_5.3.28-12.dsc' db5.3_5.3.28-12.dsc 3199 SHA256:1c4d6149f83a798e69f6d8e7444711d963c31d649284357135ea33b319c71bba
'http://deb.debian.org/debian/pool/main/d/db5.3/db5.3_5.3.28.orig.tar.xz' db5.3_5.3.28.orig.tar.xz 24154920 SHA256:e1f85c8b6ebd0ed3ca72fa0ae97b65006f6d0bd0cd6f4ac24bed103cb5497bf5
'http://deb.debian.org/debian/pool/main/d/db5.3/db5.3_5.3.28-12.debian.tar.xz' db5.3_5.3.28-12.debian.tar.xz 27812 SHA256:7907d8ad4c408857a71782436283a7ab67d7fe0f38ae15782f08077bdfd55c03
```

Likely also available for browsing at:

- https://sources.debian.net/src/db5.3/5.3.28-12/
- https://sources.debian.net/src/db5.3/5.3.28-12/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `debconf=1.5.61`

Binary Packages:

- `debconf=1.5.61`

Licenses: (parsed from: `/usr/share/doc/debconf/copyright`)

- `BSD-2-clause`

Source:

```console
$ apt-get source -qq --print-uris debconf=1.5.61
'http://deb.debian.org/debian/pool/main/d/debconf/debconf_1.5.61.dsc' debconf_1.5.61.dsc 1932 SHA256:a350712c205bf21f045c80f4a64e24cef27e35e38fd51080c79076178c63ef1b
'http://deb.debian.org/debian/pool/main/d/debconf/debconf_1.5.61.tar.xz' debconf_1.5.61.tar.xz 570372 SHA256:7622a3fe231b46e6255a83b3d153159c10be6bc17b2152ab3937b8928bf87e10
```

Likely also available for browsing at:

- https://sources.debian.net/src/debconf/1.5.61/
- https://sources.debian.net/src/debconf/1.5.61/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `debian-archive-keyring=2017.5`

Binary Packages:

- `debian-archive-keyring=2017.5`

Licenses: (parsed from: `/usr/share/doc/debian-archive-keyring/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris debian-archive-keyring=2017.5
'http://deb.debian.org/debian/pool/main/d/debian-archive-keyring/debian-archive-keyring_2017.5.dsc' debian-archive-keyring_2017.5.dsc 1597 SHA256:202c8424b79747e7a3d74b1e3d6f8748b211eb6ee1f2cb9c56f3c28ad9bc4f02
'http://deb.debian.org/debian/pool/main/d/debian-archive-keyring/debian-archive-keyring_2017.5.tar.xz' debian-archive-keyring_2017.5.tar.xz 79324 SHA256:6e06a47c79948d7a2f6b5bcfbf1f615293da329226bc9d7ad692cb67d2f4b731
```

Likely also available for browsing at:

- https://sources.debian.net/src/debian-archive-keyring/2017.5/
- https://sources.debian.net/src/debian-archive-keyring/2017.5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `debianutils=4.8.1.1`

Binary Packages:

- `debianutils=4.8.1.1`

Licenses: (parsed from: `/usr/share/doc/debianutils/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris debianutils=4.8.1.1
'http://deb.debian.org/debian/pool/main/d/debianutils/debianutils_4.8.1.1.dsc' debianutils_4.8.1.1.dsc 1739 SHA256:506d5e6c18e38831eb45ab1ecc35dd8cc3e931b0fe7367136fb7d42520130a84
'http://deb.debian.org/debian/pool/main/d/debianutils/debianutils_4.8.1.1.tar.xz' debianutils_4.8.1.1.tar.xz 156256 SHA256:06446cd4c0d309fd31a0682c5c2f07f7613fb867f769414b9cc51f155ad73172
```

Likely also available for browsing at:

- https://sources.debian.net/src/debianutils/4.8.1.1/
- https://sources.debian.net/src/debianutils/4.8.1.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `defusedxml=0.4.1-2`

Binary Packages:

- `python-defusedxml=0.4.1-2`

Licenses: (parsed from: `/usr/share/doc/python-defusedxml/copyright`)

- `Python`

Source:

```console
$ apt-get source -qq --print-uris defusedxml=0.4.1-2
'http://deb.debian.org/debian/pool/main/d/defusedxml/defusedxml_0.4.1-2.dsc' defusedxml_0.4.1-2.dsc 2147 SHA256:5843f36d18be86abd329ed5bfdc417d99eb1c38f8f3a0c816d883189b0424393
'http://deb.debian.org/debian/pool/main/d/defusedxml/defusedxml_0.4.1.orig.tar.gz' defusedxml_0.4.1.orig.tar.gz 48889 SHA256:cd551d5a518b745407635bb85116eb813818ecaf182e773c35b36239fc3f2478
'http://deb.debian.org/debian/pool/main/d/defusedxml/defusedxml_0.4.1-2.debian.tar.xz' defusedxml_0.4.1-2.debian.tar.xz 15488 SHA256:c7b08d2c42dea7edf5b6295dad2b2f1e8b0b3b6ff16da27c4e9df5a52bea95d8
```

Likely also available for browsing at:

- https://sources.debian.net/src/defusedxml/0.4.1-2/
- https://sources.debian.net/src/defusedxml/0.4.1-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `dh-python=2.20170125`

Binary Packages:

- `dh-python=2.20170125`

Licenses: (parsed from: `/usr/share/doc/dh-python/copyright`)

- `Expat`

Source:

```console
$ apt-get source -qq --print-uris dh-python=2.20170125
'http://deb.debian.org/debian/pool/main/d/dh-python/dh-python_2.20170125.dsc' dh-python_2.20170125.dsc 1908 SHA256:ef4f2951cea36ae4aac29126a1017505f98b595432fb5bdac0f21b4b4d72c1b4
'http://deb.debian.org/debian/pool/main/d/dh-python/dh-python_2.20170125.tar.xz' dh-python_2.20170125.tar.xz 91332 SHA256:2e09c162ee2442a03511b7ebe83896e1e3c1df79ce97a22d2f8a8b4cfec9f1e3
```

Likely also available for browsing at:

- https://sources.debian.net/src/dh-python/2.20170125/
- https://sources.debian.net/src/dh-python/2.20170125/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `diffutils=1:3.5-3`

Binary Packages:

- `diffutils=1:3.5-3`

Licenses: (parsed from: `/usr/share/doc/diffutils/copyright`)

- `GFDL`
- `GPL`

Source:

```console
$ apt-get source -qq --print-uris diffutils=1:3.5-3
'http://deb.debian.org/debian/pool/main/d/diffutils/diffutils_3.5-3.dsc' diffutils_3.5-3.dsc 1453 SHA256:8b8e4d9d48ab35fd2c5759a3d0854e7d85c33b3fa09a185c20865793090feff9
'http://deb.debian.org/debian/pool/main/d/diffutils/diffutils_3.5.orig.tar.xz' diffutils_3.5.orig.tar.xz 1360996 SHA256:dad398ccd5b9faca6b0ab219a036453f62a602a56203ac659b43e889bec35533
'http://deb.debian.org/debian/pool/main/d/diffutils/diffutils_3.5-3.debian.tar.xz' diffutils_3.5-3.debian.tar.xz 10796 SHA256:5c8464482951de1dcf3c1c53643cd7d0939cd8f7568a7ef84982d368c5cb6695
```

Likely also available for browsing at:

- https://sources.debian.net/src/diffutils/1:3.5-3/
- https://sources.debian.net/src/diffutils/1:3.5-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `distro-info-data=0.36`

Binary Packages:

- `distro-info-data=0.36`

Licenses: (parsed from: `/usr/share/doc/distro-info-data/copyright`)

- `ISC`

Source:

```console
$ apt-get source -qq --print-uris distro-info-data=0.36
'http://deb.debian.org/debian/pool/main/d/distro-info-data/distro-info-data_0.36.dsc' distro-info-data_0.36.dsc 1326 SHA256:4c36e2480fbaaec733774403048de675eaa7237cbce451a4fbbb1b4b411e67d1
'http://deb.debian.org/debian/pool/main/d/distro-info-data/distro-info-data_0.36.tar.xz' distro-info-data_0.36.tar.xz 6424 SHA256:a1cb1ff9f13da5d06f0c9049d94f5d431c90b5e08cf8c374a77d3a648f37abb0
```

Likely also available for browsing at:

- https://sources.debian.net/src/distro-info-data/0.36/
- https://sources.debian.net/src/distro-info-data/0.36/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `dpkg=1.18.24`

Binary Packages:

- `dpkg=1.18.24`
- `libdpkg-perl=1.18.24`

Licenses: (parsed from: `/usr/share/doc/dpkg/copyright`, `/usr/share/doc/libdpkg-perl/copyright`)

- `BSD-2-clause`
- `GPL-2`
- `GPL-2+`
- `public-domain-md5`
- `public-domain-s-s-d`

Source:

```console
$ apt-get source -qq --print-uris dpkg=1.18.24
'http://deb.debian.org/debian/pool/main/d/dpkg/dpkg_1.18.24.dsc' dpkg_1.18.24.dsc 2032 SHA256:9f1560a0d237ec570f98f8aacfd1cbdd372371cce40e4c7ee4a31315b0c40823
'http://deb.debian.org/debian/pool/main/d/dpkg/dpkg_1.18.24.tar.xz' dpkg_1.18.24.tar.xz 4530444 SHA256:d853081d3e06bfd46a227056e591f094e42e78fa8a5793b0093bad30b710d7b4
```

Likely also available for browsing at:

- https://sources.debian.net/src/dpkg/1.18.24/
- https://sources.debian.net/src/dpkg/1.18.24/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `e2fsprogs=1.43.4-2`

Binary Packages:

- `e2fslibs:amd64=1.43.4-2`
- `e2fsprogs=1.43.4-2`
- `libcomerr2:amd64=1.43.4-2`
- `libss2:amd64=1.43.4-2`

Licenses: (parsed from: `/usr/share/doc/e2fslibs/copyright`, `/usr/share/doc/e2fsprogs/copyright`, `/usr/share/doc/libcomerr2/copyright`, `/usr/share/doc/libss2/copyright`)

- `GPL-2`
- `LGPL-2`

Source:

```console
$ apt-get source -qq --print-uris e2fsprogs=1.43.4-2
'http://deb.debian.org/debian/pool/main/e/e2fsprogs/e2fsprogs_1.43.4-2.dsc' e2fsprogs_1.43.4-2.dsc 2043 SHA256:e6f6b8dddeb97cc81c3aa7aa826305e1f9c9cd1c3066b2b916e558682fdc7f70
'http://deb.debian.org/debian/pool/main/e/e2fsprogs/e2fsprogs_1.43.4.orig.tar.gz' e2fsprogs_1.43.4.orig.tar.gz 7552218 SHA256:484ab0bc1bc07c64267b18cfe7871b6b975bf0a705c5a4563001f035071cdc7c
'http://deb.debian.org/debian/pool/main/e/e2fsprogs/e2fsprogs_1.43.4-2.debian.tar.xz' e2fsprogs_1.43.4-2.debian.tar.xz 76444 SHA256:e1713f9e686a71a9d6f119cd178c4ebea502a7c2b43901cc41bcdb61b142b1c8
```

Likely also available for browsing at:

- https://sources.debian.net/src/e2fsprogs/1.43.4-2/
- https://sources.debian.net/src/e2fsprogs/1.43.4-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `elfutils=0.168-1`

Binary Packages:

- `libelf1:amd64=0.168-1`

Licenses: (parsed from: `/usr/share/doc/libelf1/copyright`)

- `GPL-2`
- `GPL-3`
- `LGPL-`

Source:

```console
$ apt-get source -qq --print-uris elfutils=0.168-1
'http://deb.debian.org/debian/pool/main/e/elfutils/elfutils_0.168-1.dsc' elfutils_0.168-1.dsc 2549 SHA256:b29e03a3d515d9accd52019ff7c75762ae5e61285453518ff90d538e9878ad7f
'http://deb.debian.org/debian/pool/main/e/elfutils/elfutils_0.168.orig.tar.bz2' elfutils_0.168.orig.tar.bz2 6840399 SHA256:b88d07893ba1373c7dd69a7855974706d05377766568a7d9002706d5de72c276
'http://deb.debian.org/debian/pool/main/e/elfutils/elfutils_0.168.orig.tar.bz2.asc' elfutils_0.168.orig.tar.bz2.asc 473 SHA256:f455fc014b59a0d80ab921935d20f26e64f411a424d4be29ec5bf3a1378f3002
'http://deb.debian.org/debian/pool/main/e/elfutils/elfutils_0.168-1.debian.tar.xz' elfutils_0.168-1.debian.tar.xz 39964 SHA256:5517922b1025d32903759c46f9a1f656e3e367c5ea036dc54b32cbbe68a5f300
```

Likely also available for browsing at:

- https://sources.debian.net/src/elfutils/0.168-1/
- https://sources.debian.net/src/elfutils/0.168-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `empy=3.3.2-1`

Binary Packages:

- `python-empy=3.3.2-1`

Licenses: (parsed from: `/usr/share/doc/python-empy/copyright`)

- `GPL`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris empy=3.3.2-1
'http://deb.debian.org/debian/pool/main/e/empy/empy_3.3.2-1.dsc' empy_3.3.2-1.dsc 2090 SHA256:beb9456c5e5241572cbcbef5dfe5f45b5056d8b83eac5789310386ec64e58a21
'http://deb.debian.org/debian/pool/main/e/empy/empy_3.3.2.orig.tar.gz' empy_3.3.2.orig.tar.gz 138168 SHA256:99f016af2770c48ab57a65df7aae251360dc69a1514c15851458a71d4ddfea9c
'http://deb.debian.org/debian/pool/main/e/empy/empy_3.3.2-1.debian.tar.xz' empy_3.3.2-1.debian.tar.xz 4576 SHA256:8919a16c09a5c1f99900fb79eabe1010c06d8528816ab90bf0f84157fc54b592
```

Likely also available for browsing at:

- https://sources.debian.net/src/empy/3.3.2-1/
- https://sources.debian.net/src/empy/3.3.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `enum34=1.1.6-1`

Binary Packages:

- `python-enum34=1.1.6-1`

Licenses: (parsed from: `/usr/share/doc/python-enum34/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris enum34=1.1.6-1
'http://deb.debian.org/debian/pool/main/e/enum34/enum34_1.1.6-1.dsc' enum34_1.1.6-1.dsc 2197 SHA256:69a10f087cf28afb7a62e36c226eef8d857eaef6efb0e0559a3b65a7705f8e46
'http://deb.debian.org/debian/pool/main/e/enum34/enum34_1.1.6.orig.tar.gz' enum34_1.1.6.orig.tar.gz 40048 SHA256:8ad8c4783bf61ded74527bffb48ed9b54166685e4230386a9ed9b1279e2df5b1
'http://deb.debian.org/debian/pool/main/e/enum34/enum34_1.1.6-1.debian.tar.xz' enum34_1.1.6-1.debian.tar.xz 3900 SHA256:061bff1a8ae8e7147738818ed1de8ff4a9ae1825725d7361bca92cf6eeb34f89
```

Likely also available for browsing at:

- https://sources.debian.net/src/enum34/1.1.6-1/
- https://sources.debian.net/src/enum34/1.1.6-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `expat=2.2.0-2+deb9u1`

Binary Packages:

- `libexpat1:amd64=2.2.0-2+deb9u1`
- `libexpat1-dev:amd64=2.2.0-2+deb9u1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris expat=2.2.0-2+deb9u1
'http://security.debian.org/pool/updates/main/e/expat/expat_2.2.0-2+deb9u1.dsc' expat_2.2.0-2+deb9u1.dsc 2295 SHA256:6d7f96d7148dda2857772b499cbe17d0feb1c016dcf35b1a6da7c846123bd20b
'http://security.debian.org/pool/updates/main/e/expat/expat_2.2.0.orig.tar.bz2' expat_2.2.0.orig.tar.bz2 414352 SHA256:d9e50ff2d19b3538bd2127902a89987474e1a4db8e43a66a4d1a712ab9a504ff
'http://security.debian.org/pool/updates/main/e/expat/expat_2.2.0-2+deb9u1.debian.tar.xz' expat_2.2.0-2+deb9u1.debian.tar.xz 11448 SHA256:d3e171fc4d2e6173945daab7d7df46d640fa23134c9474080f6d1b65d494b0a5
```

Likely also available for browsing at:

- https://sources.debian.net/src/expat/2.2.0-2+deb9u1/
- https://sources.debian.net/src/expat/2.2.0-2+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `explorercanvas=0.r3-4`

Binary Packages:

- `libjs-excanvas=0.r3-4`

Licenses: (parsed from: `/usr/share/doc/libjs-excanvas/copyright`)

- `Apache-2.0`

Source:

```console
$ apt-get source -qq --print-uris explorercanvas=0.r3-4
'http://deb.debian.org/debian/pool/main/e/explorercanvas/explorercanvas_0.r3-4.dsc' explorercanvas_0.r3-4.dsc 2000 SHA256:d168011ed1f110f82b5039a6b070167f1f262d2a35d7fa25a6b5462f73761637
'http://deb.debian.org/debian/pool/main/e/explorercanvas/explorercanvas_0.r3.orig.tar.gz' explorercanvas_0.r3.orig.tar.gz 50748 SHA256:687af8084781b8eb3451fc55c88f6dfddc2b84428d197daf2c4c33fd5c55fed8
'http://deb.debian.org/debian/pool/main/e/explorercanvas/explorercanvas_0.r3-4.debian.tar.xz' explorercanvas_0.r3-4.debian.tar.xz 2040 SHA256:afcaa3e229d9b423988fc30439aeee1599c9dac8ad94430309404f9cf9f0c11f
```

Likely also available for browsing at:

- https://sources.debian.net/src/explorercanvas/0.r3-4/
- https://sources.debian.net/src/explorercanvas/0.r3-4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `file=1:5.30-1`

Binary Packages:

- `file=1:5.30-1`
- `libmagic-mgc=1:5.30-1`
- `libmagic1:amd64=1:5.30-1`

Licenses: (parsed from: `/usr/share/doc/file/copyright`, `/usr/share/doc/libmagic-mgc/copyright`, `/usr/share/doc/libmagic1/copyright`)

- `BSD-2-Clause-alike`
- `BSD-2-Clause-netbsd`
- `BSD-2-Clause-regents`
- `MIT-Old-Style-with-legal-disclaimer-2`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris file=1:5.30-1
'http://deb.debian.org/debian/pool/main/f/file/file_5.30-1.dsc' file_5.30-1.dsc 2124 SHA256:685de7e2b71f8cbc22675638be6bb59aa6224d11a8ee90447062950598abebe2
'http://deb.debian.org/debian/pool/main/f/file/file_5.30.orig.tar.xz' file_5.30.orig.tar.xz 578628 SHA256:813feaa00da67897b652aa2f0bdeba46f1a265223071a3ea0591476b4e1b0291
'http://deb.debian.org/debian/pool/main/f/file/file_5.30-1.debian.tar.xz' file_5.30-1.debian.tar.xz 39192 SHA256:0b838e0467d6e0d738395f8a21e20040f8b3b114abf5d3e2329f954f7c11666a
```

Likely also available for browsing at:

- https://sources.debian.net/src/file/1:5.30-1/
- https://sources.debian.net/src/file/1:5.30-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `findutils=4.6.0+git+20161106-2`

Binary Packages:

- `findutils=4.6.0+git+20161106-2`

Licenses: (parsed from: `/usr/share/doc/findutils/copyright`)

- `GFDL-1.3`
- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris findutils=4.6.0+git+20161106-2
'http://deb.debian.org/debian/pool/main/f/findutils/findutils_4.6.0+git+20161106-2.dsc' findutils_4.6.0+git+20161106-2.dsc 2220 SHA256:f92d95f03e56357bb72e897f4d8b363995f280cfdf6dedfabdec3164f3a7651a
'http://deb.debian.org/debian/pool/main/f/findutils/findutils_4.6.0+git+20161106.orig.tar.xz' findutils_4.6.0+git+20161106.orig.tar.xz 1828956 SHA256:96a3aa120d7300863f39fe56ccb6674d8cde4730b485f4f81083c1a6d33097e3
'http://deb.debian.org/debian/pool/main/f/findutils/findutils_4.6.0+git+20161106-2.debian.tar.xz' findutils_4.6.0+git+20161106-2.debian.tar.xz 26812 SHA256:aca885ac24582f5c393dbbfa362264712ee4922da0ff7aa1fc602e629c89b71b
```

Likely also available for browsing at:

- https://sources.debian.net/src/findutils/4.6.0+git+20161106-2/
- https://sources.debian.net/src/findutils/4.6.0+git+20161106-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gcc-6=6.3.0-18`

Binary Packages:

- `cpp-6=6.3.0-18`
- `gcc-6=6.3.0-18`
- `gcc-6-base:amd64=6.3.0-18`
- `libasan3:amd64=6.3.0-18`
- `libatomic1:amd64=6.3.0-18`
- `libcc1-0:amd64=6.3.0-18`
- `libcilkrts5:amd64=6.3.0-18`
- `libgcc-6-dev:amd64=6.3.0-18`
- `libgcc1:amd64=1:6.3.0-18`
- `libgfortran3:amd64=6.3.0-18`
- `libgomp1:amd64=6.3.0-18`
- `libitm1:amd64=6.3.0-18`
- `liblsan0:amd64=6.3.0-18`
- `libmpx2:amd64=6.3.0-18`
- `libquadmath0:amd64=6.3.0-18`
- `libstdc++-6-dev:amd64=6.3.0-18`
- `libstdc++6:amd64=6.3.0-18`
- `libtsan0:amd64=6.3.0-18`
- `libubsan0:amd64=6.3.0-18`

Licenses: (parsed from: `/usr/share/doc/cpp-6/copyright`, `/usr/share/doc/gcc-6/copyright`, `/usr/share/doc/gcc-6-base/copyright`, `/usr/share/doc/libasan3/copyright`, `/usr/share/doc/libatomic1/copyright`, `/usr/share/doc/libcc1-0/copyright`, `/usr/share/doc/libcilkrts5/copyright`, `/usr/share/doc/libgcc-6-dev/copyright`, `/usr/share/doc/libgcc1/copyright`, `/usr/share/doc/libgfortran3/copyright`, `/usr/share/doc/libgomp1/copyright`, `/usr/share/doc/libitm1/copyright`, `/usr/share/doc/liblsan0/copyright`, `/usr/share/doc/libmpx2/copyright`, `/usr/share/doc/libquadmath0/copyright`, `/usr/share/doc/libstdc++-6-dev/copyright`, `/usr/share/doc/libstdc++6/copyright`, `/usr/share/doc/libtsan0/copyright`, `/usr/share/doc/libubsan0/copyright`)

- `Artistic`
- `GFDL-1.2`
- `GPL`
- `GPL-2`
- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris gcc-6=6.3.0-18
'http://deb.debian.org/debian/pool/main/g/gcc-6/gcc-6_6.3.0-18.dsc' gcc-6_6.3.0-18.dsc 27145 SHA256:faa23e7b7ce387d19532df421d8538218f973075c3b92b37f95811d7677ae80e
'http://deb.debian.org/debian/pool/main/g/gcc-6/gcc-6_6.3.0.orig.tar.gz' gcc-6_6.3.0.orig.tar.gz 81587460 SHA256:04552f04baf6974fb7521191859fb54717385ad659afd822b2995b66ee4e4151
'http://deb.debian.org/debian/pool/main/g/gcc-6/gcc-6_6.3.0-18.diff.gz' gcc-6_6.3.0-18.diff.gz 2045830 SHA256:7e76d64b79c0b6bed356ae752a2017746d4b069bc78624da0c94b8169f1f51cc
```

Likely also available for browsing at:

- https://sources.debian.net/src/gcc-6/6.3.0-18/
- https://sources.debian.net/src/gcc-6/6.3.0-18/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gcc-defaults=1.168`

Binary Packages:

- `cpp=4:6.3.0-4`
- `gcc=4:6.3.0-4`

Licenses: (parsed from: `/usr/share/doc/cpp/copyright`, `/usr/share/doc/gcc/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris gcc-defaults=1.168
'http://deb.debian.org/debian/pool/main/g/gcc-defaults/gcc-defaults_1.168.dsc' gcc-defaults_1.168.dsc 13173 SHA256:05a2a34278108aec64227a63cb61d9562bca9380f8539562e7e42023dca2d1c8
'http://deb.debian.org/debian/pool/main/g/gcc-defaults/gcc-defaults_1.168.tar.gz' gcc-defaults_1.168.tar.gz 69321 SHA256:4ecc5edafbf47d43c8b872e36c9a87c95691bed94eaa6e8f55adfc8fd64e5587
```

Likely also available for browsing at:

- https://sources.debian.net/src/gcc-defaults/1.168/
- https://sources.debian.net/src/gcc-defaults/1.168/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gdbm=1.8.3-14`

Binary Packages:

- `libgdbm3:amd64=1.8.3-14`

Licenses: (parsed from: `/usr/share/doc/libgdbm3/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris gdbm=1.8.3-14
'http://deb.debian.org/debian/pool/main/g/gdbm/gdbm_1.8.3-14.dsc' gdbm_1.8.3-14.dsc 1841 SHA256:312d3d28e287d287ee66e8ae3f25769676b1680ec1adc8c0815b5e9808405b13
'http://deb.debian.org/debian/pool/main/g/gdbm/gdbm_1.8.3.orig.tar.bz2' gdbm_1.8.3.orig.tar.bz2 172796 SHA256:1d5995b6e9e6be4ff62c8126d019f184a083dd8e6f75f6c74b9fe023b5b9440e
'http://deb.debian.org/debian/pool/main/g/gdbm/gdbm_1.8.3-14.debian.tar.xz' gdbm_1.8.3-14.debian.tar.xz 15308 SHA256:1c0570dd53947ea5980111f51b67356d647c4f21c502443b02397041dde0bf31
```

Likely also available for browsing at:

- https://sources.debian.net/src/gdbm/1.8.3-14/
- https://sources.debian.net/src/gdbm/1.8.3-14/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `git=1:2.11.0-3+deb9u1`

Binary Packages:

- `git=1:2.11.0-3+deb9u1`
- `git-core=1:2.11.0-3+deb9u1`
- `git-man=1:2.11.0-3+deb9u1`

Licenses: (parsed from: `/usr/share/doc/git/copyright`, `/usr/share/doc/git-core/copyright`, `/usr/share/doc/git-man/copyright`)

- `Apache-2.0`
- `Artistic`
- `Artistic-1`
- `BSD-2-clause`
- `Boost`
- `EDL-1.0`
- `Expat`
- `GPL`
- `GPL-1+`
- `GPL-2`
- `GPL-2+`
- `ISC`
- `LGPL-2`
- `LGPL-2+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `dlmalloc`
- `mingw-runtime`

Source:

```console
$ apt-get source -qq --print-uris git=1:2.11.0-3+deb9u1
'http://security.debian.org/pool/updates/main/g/git/git_2.11.0-3+deb9u1.dsc' git_2.11.0-3+deb9u1.dsc 2901 SHA256:1b2244ce374d402ae6c4389be8e19d7189bc075f7790798dc8159901a4684a36
'http://security.debian.org/pool/updates/main/g/git/git_2.11.0.orig.tar.xz' git_2.11.0.orig.tar.xz 4197984 SHA256:7e7e8d69d494892373b87007674be5820a4bc1ef596a0117d03ea3169119fd0b
'http://security.debian.org/pool/updates/main/g/git/git_2.11.0-3+deb9u1.debian.tar.xz' git_2.11.0-3+deb9u1.debian.tar.xz 523448 SHA256:c6f95ed3a3a1804c1ee17e554d42c1a0203d16dd9a30647a798128e9f242cc3b
```

Likely also available for browsing at:

- https://sources.debian.net/src/git/1:2.11.0-3+deb9u1/
- https://sources.debian.net/src/git/1:2.11.0-3+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `glib2.0=2.50.3-2`

Binary Packages:

- `libglib2.0-0:amd64=2.50.3-2`
- `libglib2.0-data=2.50.3-2`

Licenses: (parsed from: `/usr/share/doc/libglib2.0-0/copyright`, `/usr/share/doc/libglib2.0-data/copyright`)

- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris glib2.0=2.50.3-2
'http://deb.debian.org/debian/pool/main/g/glib2.0/glib2.0_2.50.3-2.dsc' glib2.0_2.50.3-2.dsc 3302 SHA256:9c8e79d22e5a11ebbb69389018478c79aa39dc01f6d1fee4f164ad17752a33c9
'http://deb.debian.org/debian/pool/main/g/glib2.0/glib2.0_2.50.3.orig.tar.xz' glib2.0_2.50.3.orig.tar.xz 7589284 SHA256:82ee94bf4c01459b6b00cb9db0545c2237921e3060c0b74cff13fbc020cfd999
'http://deb.debian.org/debian/pool/main/g/glib2.0/glib2.0_2.50.3-2.debian.tar.xz' glib2.0_2.50.3-2.debian.tar.xz 70936 SHA256:dab54226c828a99eb3accf59d471efceafcc16c25c7482cf99972553f98b6512
```

Likely also available for browsing at:

- https://sources.debian.net/src/glib2.0/2.50.3-2/
- https://sources.debian.net/src/glib2.0/2.50.3-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `glibc=2.24-11+deb9u1`

Binary Packages:

- `libc-bin=2.24-11+deb9u1`
- `libc-dev-bin=2.24-11+deb9u1`
- `libc6:amd64=2.24-11+deb9u1`
- `libc6-dev:amd64=2.24-11+deb9u1`
- `multiarch-support=2.24-11+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libc-bin/copyright`, `/usr/share/doc/libc-dev-bin/copyright`, `/usr/share/doc/libc6/copyright`, `/usr/share/doc/libc6-dev/copyright`, `/usr/share/doc/multiarch-support/copyright`)

- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris glibc=2.24-11+deb9u1
'http://deb.debian.org/debian/pool/main/g/glibc/glibc_2.24-11+deb9u1.dsc' glibc_2.24-11+deb9u1.dsc 8383 SHA256:9ae850c83adbb766c62e381633680c9d73f82744db004967717bf3105cfcb204
'http://deb.debian.org/debian/pool/main/g/glibc/glibc_2.24.orig.tar.xz' glibc_2.24.orig.tar.xz 13921912 SHA256:ed71e8afd2b270f7947a2cea2457a31e1ca4fac08e2731d80edd7ec1730ec84f
'http://deb.debian.org/debian/pool/main/g/glibc/glibc_2.24-11+deb9u1.debian.tar.xz' glibc_2.24-11+deb9u1.debian.tar.xz 991860 SHA256:d16b5a5de7a1d6e0316e811d431a991ffd64f47a021eec4f36393f05d0f0578d
```

Likely also available for browsing at:

- https://sources.debian.net/src/glibc/2.24-11+deb9u1/
- https://sources.debian.net/src/glibc/2.24-11+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gmp=2:6.1.2+dfsg-1`

Binary Packages:

- `libgmp10:amd64=2:6.1.2+dfsg-1`

Licenses: (parsed from: `/usr/share/doc/libgmp10/copyright`)

- `GPL`
- `GPL-2`
- `GPL-3`
- `LGPL-3`

Source:

```console
$ apt-get source -qq --print-uris gmp=2:6.1.2+dfsg-1
'http://deb.debian.org/debian/pool/main/g/gmp/gmp_6.1.2+dfsg-1.dsc' gmp_6.1.2+dfsg-1.dsc 2183 SHA256:3a53f6c74c9b2465c1c61446aa9bdc6182fdec8b04075849d4cbf224a73b6fbe
'http://deb.debian.org/debian/pool/main/g/gmp/gmp_6.1.2+dfsg.orig.tar.xz' gmp_6.1.2+dfsg.orig.tar.xz 1804424 SHA256:18016f718f621e7641ddd4e57f8e140391c5183252e5998263ffff59198a65b7
'http://deb.debian.org/debian/pool/main/g/gmp/gmp_6.1.2+dfsg-1.debian.tar.xz' gmp_6.1.2+dfsg-1.debian.tar.xz 20652 SHA256:79e73f74197e7628b2f0c02edf01b6eea3716c13152044ed8e0e0ee4178394df
```

Likely also available for browsing at:

- https://sources.debian.net/src/gmp/2:6.1.2+dfsg-1/
- https://sources.debian.net/src/gmp/2:6.1.2+dfsg-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gnupg2=2.1.18-6`

Binary Packages:

- `dirmngr=2.1.18-6`
- `gnupg=2.1.18-6`
- `gnupg-agent=2.1.18-6`
- `gnupg2=2.1.18-6`
- `gpgv=2.1.18-6`

Licenses: (parsed from: `/usr/share/doc/dirmngr/copyright`, `/usr/share/doc/gnupg/copyright`, `/usr/share/doc/gnupg-agent/copyright`, `/usr/share/doc/gnupg2/copyright`, `/usr/share/doc/gpgv/copyright`)

- `BSD-3-clause`
- `Expat`
- `GPL-3`
- `GPL-3+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `LGPL-3`
- `LGPL-3+`
- `RFC-Reference`
- `TinySCHEME`
- `permissive`

Source:

```console
$ apt-get source -qq --print-uris gnupg2=2.1.18-6
'http://deb.debian.org/debian/pool/main/g/gnupg2/gnupg2_2.1.18-6.dsc' gnupg2_2.1.18-6.dsc 3148 SHA256:a7b69e22c8de6637ce4e267907ac13bd5144c1abf010ad33d8f48b9c9839bbe8
'http://deb.debian.org/debian/pool/main/g/gnupg2/gnupg2_2.1.18.orig.tar.bz2' gnupg2_2.1.18.orig.tar.bz2 6308666 SHA256:d04c6fab7e5562ce4b915b22020e34d4c1a256847690cf149842264fc7cef994
'http://deb.debian.org/debian/pool/main/g/gnupg2/gnupg2_2.1.18-6.debian.tar.bz2' gnupg2_2.1.18-6.debian.tar.bz2 67292 SHA256:fc8a74741a0383afcc8abef63a9449750c99051eb8b6e841e5aae62a2976969f
```

Likely also available for browsing at:

- https://sources.debian.net/src/gnupg2/2.1.18-6/
- https://sources.debian.net/src/gnupg2/2.1.18-6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gnutls28=3.5.8-5+deb9u2`

Binary Packages:

- `libgnutls30:amd64=3.5.8-5+deb9u2`

Licenses: (parsed from: `/usr/share/doc/libgnutls30/copyright`)

- `CC0 license`
- `GFDL-1.3`
- `GPL`
- `GPL-3`
- `LGPL`
- `LGPL-3`
- `LGPL2.1`
- `The MIT License (MIT)`
- `The main library is licensed under GNU Lesser`

Source:

```console
$ apt-get source -qq --print-uris gnutls28=3.5.8-5+deb9u2
'http://deb.debian.org/debian/pool/main/g/gnutls28/gnutls28_3.5.8-5+deb9u2.dsc' gnutls28_3.5.8-5+deb9u2.dsc 3286 SHA256:7e9f5175859130a1bb2768b8ed46fd5f8f3f36145b5e7bf8c422cc91aa6920db
'http://deb.debian.org/debian/pool/main/g/gnutls28/gnutls28_3.5.8.orig.tar.xz' gnutls28_3.5.8.orig.tar.xz 7264448 SHA256:0e97f243ae72b70307d684b84c7fe679385aa7a7a0e37e5be810193dcc17d4ff
'http://deb.debian.org/debian/pool/main/g/gnutls28/gnutls28_3.5.8.orig.tar.xz.asc' gnutls28_3.5.8.orig.tar.xz.asc 287 SHA256:417da9db564a841128edb2dc2c98465a5749541f7d71492cb7c4905a0bfeac82
'http://deb.debian.org/debian/pool/main/g/gnutls28/gnutls28_3.5.8-5+deb9u2.debian.tar.xz' gnutls28_3.5.8-5+deb9u2.debian.tar.xz 107164 SHA256:afcc9cf4f33f0e84751d770631a4915c70309fc9c5e04344d06a86c66b58b0c8
```

Likely also available for browsing at:

- https://sources.debian.net/src/gnutls28/3.5.8-5+deb9u2/
- https://sources.debian.net/src/gnutls28/3.5.8-5+deb9u2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `googletest=1.8.0-6`

Binary Packages:

- `googletest:amd64=1.8.0-6`
- `libgtest-dev:amd64=1.8.0-6`

Licenses: (parsed from: `/usr/share/doc/googletest/copyright`, `/usr/share/doc/libgtest-dev/copyright`)

- `Apache`
- `BSD-C3`
- `GAP`

Source:

```console
$ apt-get source -qq --print-uris googletest=1.8.0-6
'http://deb.debian.org/debian/pool/main/g/googletest/googletest_1.8.0-6.dsc' googletest_1.8.0-6.dsc 2077 SHA256:80407dd39851eee21860f05b4f3d88e9c3fb905d3aa33c4a19496ddc33da66d4
'http://deb.debian.org/debian/pool/main/g/googletest/googletest_1.8.0.orig.tar.gz' googletest_1.8.0.orig.tar.gz 1281617 SHA256:58a6f4277ca2bc8565222b3bbd58a177609e9c488e8a72649359ba51450db7d8
'http://deb.debian.org/debian/pool/main/g/googletest/googletest_1.8.0-6.debian.tar.xz' googletest_1.8.0-6.debian.tar.xz 8492 SHA256:0b11f825aae0c84d1b0be43ffc3e6b288d2c3b064f94ac5f241a72493a51b253
```

Likely also available for browsing at:

- https://sources.debian.net/src/googletest/1.8.0-6/
- https://sources.debian.net/src/googletest/1.8.0-6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gpm=1.20.4-6.2`

Binary Packages:

- `libgpm2:amd64=1.20.4-6.2+b1`

Licenses: (parsed from: `/usr/share/doc/libgpm2/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris gpm=1.20.4-6.2
'http://deb.debian.org/debian/pool/main/g/gpm/gpm_1.20.4-6.2.dsc' gpm_1.20.4-6.2.dsc 1812 SHA256:9c81da20a6ec92d139ea758c38cb8fbacc818d1e06082396f69c2e594ab38de5
'http://deb.debian.org/debian/pool/main/g/gpm/gpm_1.20.4.orig.tar.gz' gpm_1.20.4.orig.tar.gz 1347133 SHA256:d6c87cd0f2c32e2c3435c444728f2ae60324fda60dedda783ea0f24f363e576c
'http://deb.debian.org/debian/pool/main/g/gpm/gpm_1.20.4-6.2.diff.gz' gpm_1.20.4-6.2.diff.gz 95710 SHA256:05f5303e31e9131cdd64a4c2409ac07f8886eac0d852839d0e464df7528773d2
```

Likely also available for browsing at:

- https://sources.debian.net/src/gpm/1.20.4-6.2/
- https://sources.debian.net/src/gpm/1.20.4-6.2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `grep=2.27-2`

Binary Packages:

- `grep=2.27-2`

Licenses: (parsed from: `/usr/share/doc/grep/copyright`)

- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris grep=2.27-2
'http://deb.debian.org/debian/pool/main/g/grep/grep_2.27-2.dsc' grep_2.27-2.dsc 2053 SHA256:c048a1ad8c39877c2fb0279887c8ea93e59591788fdb08e2f75249ebdcecdea7
'http://deb.debian.org/debian/pool/main/g/grep/grep_2.27.orig.tar.xz' grep_2.27.orig.tar.xz 1360388 SHA256:ad4cc44d23074a1c3a8baae8fbafff2a8c60f38a9a6108f985eef6fbee6dcaeb
'http://deb.debian.org/debian/pool/main/g/grep/grep_2.27-2.debian.tar.bz2' grep_2.27-2.debian.tar.bz2 112728 SHA256:445eaf71811df5ca18242fb5adc417d35e349e49810201977bf7086746b967f4
```

Likely also available for browsing at:

- https://sources.debian.net/src/grep/2.27-2/
- https://sources.debian.net/src/grep/2.27-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `gzip=1.6-5`

Binary Packages:

- `gzip=1.6-5+b1`

Licenses: (parsed from: `/usr/share/doc/gzip/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris gzip=1.6-5
'http://deb.debian.org/debian/pool/main/g/gzip/gzip_1.6-5.dsc' gzip_1.6-5.dsc 1867 SHA256:922751ee5fc426d623e824c55f7822fa60f26f35b5389b37c8b15feff639608c
'http://deb.debian.org/debian/pool/main/g/gzip/gzip_1.6.orig.tar.gz' gzip_1.6.orig.tar.gz 1074924 SHA256:97eb83b763d9e5ad35f351fe5517e6b71521d7aac7acf3e3cacdb6b1496d8f7e
'http://deb.debian.org/debian/pool/main/g/gzip/gzip_1.6-5.debian.tar.xz' gzip_1.6-5.debian.tar.xz 14684 SHA256:ac5282c32083ff58fc01317ee402b687b3806555aa1d4e80a62bb0f2ad93167e
```

Likely also available for browsing at:

- https://sources.debian.net/src/gzip/1.6-5/
- https://sources.debian.net/src/gzip/1.6-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `hostname=3.18`

Binary Packages:

- `hostname=3.18+b1`

Licenses: (parsed from: `/usr/share/doc/hostname/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris hostname=3.18
'http://deb.debian.org/debian/pool/main/h/hostname/hostname_3.18.dsc' hostname_3.18.dsc 1446 SHA256:4d3d5c8ded08ffc2ebfb39817ba1994b5fc1966652b132ff3e16389b70af28d7
'http://deb.debian.org/debian/pool/main/h/hostname/hostname_3.18.tar.gz' hostname_3.18.tar.gz 13732 SHA256:5cc3ec120967b8f911e86b9561b53977bcc77191c84fe9c607177ccd09f8d207
```

Likely also available for browsing at:

- https://sources.debian.net/src/hostname/3.18/
- https://sources.debian.net/src/hostname/3.18/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `hwloc=1.11.5-1`

Binary Packages:

- `libhwloc-dev:amd64=1.11.5-1`
- `libhwloc-plugins=1.11.5-1`
- `libhwloc5:amd64=1.11.5-1`

Licenses: (parsed from: `/usr/share/doc/libhwloc-dev/copyright`, `/usr/share/doc/libhwloc-plugins/copyright`, `/usr/share/doc/libhwloc5/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris hwloc=1.11.5-1
'http://deb.debian.org/debian/pool/main/h/hwloc/hwloc_1.11.5-1.dsc' hwloc_1.11.5-1.dsc 2640 SHA256:fcd6723ec31e4fd8f212e3b3d1748c651d0980455aa9b844fbf062310f2d97d7
'http://deb.debian.org/debian/pool/main/h/hwloc/hwloc_1.11.5.orig.tar.bz2' hwloc_1.11.5.orig.tar.bz2 4135369 SHA256:95d80286dfe658a3f79e2ac90698782bb36e5504f4bac1bba2394ba14dbbad24
'http://deb.debian.org/debian/pool/main/h/hwloc/hwloc_1.11.5-1.debian.tar.bz2' hwloc_1.11.5-1.debian.tar.bz2 10054 SHA256:391f8fc277ee9532ec68d2d8d151cc3b5701023b1922eccbf364f41f0d3f498a
```

Likely also available for browsing at:

- https://sources.debian.net/src/hwloc/1.11.5-1/
- https://sources.debian.net/src/hwloc/1.11.5-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `icu=57.1-6`

Binary Packages:

- `icu-devtools=57.1-6`
- `libicu-dev=57.1-6`
- `libicu57:amd64=57.1-6`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris icu=57.1-6
'http://deb.debian.org/debian/pool/main/i/icu/icu_57.1-6.dsc' icu_57.1-6.dsc 2105 SHA256:6d3979c7e13e23d4de31e0ff3b83c34e4824e4982cfed9887b21ab6b6c272e6b
'http://deb.debian.org/debian/pool/main/i/icu/icu_57.1.orig.tar.gz' icu_57.1.orig.tar.gz 22360664 SHA256:ff8c67cb65949b1e7808f2359f2b80f722697048e90e7cfc382ec1fe229e9581
'http://deb.debian.org/debian/pool/main/i/icu/icu_57.1-6.debian.tar.xz' icu_57.1-6.debian.tar.xz 32768 SHA256:9c1239e6c395aa44880617a8f67f1f9936a9536ad0c85b8c0ceedf4c0bf40819
```

Likely also available for browsing at:

- https://sources.debian.net/src/icu/57.1-6/
- https://sources.debian.net/src/icu/57.1-6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `inetutils=2:1.9.4-2`

Binary Packages:

- `inetutils-ping=2:1.9.4-2+b1`

Licenses: (parsed from: `/usr/share/doc/inetutils-ping/copyright`)

- `BSD-3-clause`
- `GFDL-1.3`
- `GFDL-1.3+`
- `GPL-3`
- `GPL-3+`
- `MIT`
- `Wietse`

Source:

```console
$ apt-get source -qq --print-uris inetutils=2:1.9.4-2
'http://deb.debian.org/debian/pool/main/i/inetutils/inetutils_1.9.4-2.dsc' inetutils_1.9.4-2.dsc 2662 SHA256:bd38f1018bbb697b6e27235a804f742a7bcd5fffb736479e8084f5214ed45669
'http://deb.debian.org/debian/pool/main/i/inetutils/inetutils_1.9.4.orig.tar.xz' inetutils_1.9.4.orig.tar.xz 1364408 SHA256:849d96f136effdef69548a940e3e0ec0624fc0c81265296987986a0dd36ded37
'http://deb.debian.org/debian/pool/main/i/inetutils/inetutils_1.9.4-2.debian.tar.xz' inetutils_1.9.4-2.debian.tar.xz 77188 SHA256:1b67e9197c4205b36e7b05e07eedaf44f9b3971f03ab83b7fed279a692d93a98
```

Likely also available for browsing at:

- https://sources.debian.net/src/inetutils/2:1.9.4-2/
- https://sources.debian.net/src/inetutils/2:1.9.4-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `infinipath-psm=3.3+19.g67c0807.open-3`

Binary Packages:

- `libpsm-infinipath1=3.3+19.g67c0807.open-3`

Licenses: (parsed from: `/usr/share/doc/libpsm-infinipath1/copyright`)

- `BSD-2-clause`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris infinipath-psm=3.3+19.g67c0807.open-3
'http://deb.debian.org/debian/pool/main/i/infinipath-psm/infinipath-psm_3.3+19.g67c0807.open-3.dsc' infinipath-psm_3.3+19.g67c0807.open-3.dsc 2416 SHA256:711ad1f4e7802cf6f54509e26d4d62708da3662aecd5d49cd5ca0f5f3d64d906
'http://deb.debian.org/debian/pool/main/i/infinipath-psm/infinipath-psm_3.3+19.g67c0807.open.orig.tar.gz' infinipath-psm_3.3+19.g67c0807.open.orig.tar.gz 383298 SHA256:c31f7c8eee0624e424fe77b725a92933c7716051cee271c087e06d0720c506aa
'http://deb.debian.org/debian/pool/main/i/infinipath-psm/infinipath-psm_3.3+19.g67c0807.open-3.debian.tar.xz' infinipath-psm_3.3+19.g67c0807.open-3.debian.tar.xz 8712 SHA256:5523dfed687f97613ae4b995b89bd16053b19dba6c81d82966a514e0de456db5
```

Likely also available for browsing at:

- https://sources.debian.net/src/infinipath-psm/3.3+19.g67c0807.open-3/
- https://sources.debian.net/src/infinipath-psm/3.3+19.g67c0807.open-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `init-system-helpers=1.48`

Binary Packages:

- `init-system-helpers=1.48`

Licenses: (parsed from: `/usr/share/doc/init-system-helpers/copyright`)

- `BSD-3-clause`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris init-system-helpers=1.48
'http://deb.debian.org/debian/pool/main/i/init-system-helpers/init-system-helpers_1.48.dsc' init-system-helpers_1.48.dsc 1916 SHA256:aefcef5270cfae3380f9dfd98336de20580086dbdc65c0dfd7fe1c10f0722bd0
'http://deb.debian.org/debian/pool/main/i/init-system-helpers/init-system-helpers_1.48.tar.xz' init-system-helpers_1.48.tar.xz 43384 SHA256:20b4ff9df037cfa64d6c9637e383cb09135cb97114d932032160cdfaf01d08b8
```

Likely also available for browsing at:

- https://sources.debian.net/src/init-system-helpers/1.48/
- https://sources.debian.net/src/init-system-helpers/1.48/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `iproute2=4.9.0-1`

Binary Packages:

- `iproute2=4.9.0-1`

Licenses: (parsed from: `/usr/share/doc/iproute2/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris iproute2=4.9.0-1
'http://deb.debian.org/debian/pool/main/i/iproute2/iproute2_4.9.0-1.dsc' iproute2_4.9.0-1.dsc 2397 SHA256:30ead60a56ff3d3a2ba61079790292952d66b5a74b1685133b7a69ef14a82e2e
'http://deb.debian.org/debian/pool/main/i/iproute2/iproute2_4.9.0.orig.tar.xz' iproute2_4.9.0.orig.tar.xz 613032 SHA256:c0f30f043f7767cc1b2cd2197b08d4e9b2392c95823fabe30bbce308c30116c4
'http://deb.debian.org/debian/pool/main/i/iproute2/iproute2_4.9.0-1.debian.tar.xz' iproute2_4.9.0-1.debian.tar.xz 26752 SHA256:1926348d3c8c9e90f7826f5d409d5dc17a2cbf5d247206f1bc4b9a584c672be2
```

Likely also available for browsing at:

- https://sources.debian.net/src/iproute2/4.9.0-1/
- https://sources.debian.net/src/iproute2/4.9.0-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `isl=0.18-1`

Binary Packages:

- `libisl15:amd64=0.18-1`

Licenses: (parsed from: `/usr/share/doc/libisl15/copyright`)

- `BSD-2-clause`
- `LGPL-2`
- `LGPL-2.1+`
- `MIT`

Source:

```console
$ apt-get source -qq --print-uris isl=0.18-1
'http://deb.debian.org/debian/pool/main/i/isl/isl_0.18-1.dsc' isl_0.18-1.dsc 1882 SHA256:aed8295d019805686fd795652d930b1440bc0ae3be4373332d97784645d7c583
'http://deb.debian.org/debian/pool/main/i/isl/isl_0.18.orig.tar.xz' isl_0.18.orig.tar.xz 1475708 SHA256:0f35051cc030b87c673ac1f187de40e386a1482a0cfdf2c552dd6031b307ddc4
'http://deb.debian.org/debian/pool/main/i/isl/isl_0.18-1.debian.tar.xz' isl_0.18-1.debian.tar.xz 21860 SHA256:eac951311a871bb6d7886c98068290f771aaf78616516855b472d2500b84f53c
```

Likely also available for browsing at:

- https://sources.debian.net/src/isl/0.18-1/
- https://sources.debian.net/src/isl/0.18-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `keyutils=1.5.9-9`

Binary Packages:

- `libkeyutils1:amd64=1.5.9-9`

Licenses: (parsed from: `/usr/share/doc/libkeyutils1/copyright`)

- `GPL-2`
- `GPL-2+`
- `LGPL-2`
- `LGPL-2+`

Source:

```console
$ apt-get source -qq --print-uris keyutils=1.5.9-9
'http://deb.debian.org/debian/pool/main/k/keyutils/keyutils_1.5.9-9.dsc' keyutils_1.5.9-9.dsc 2033 SHA256:5fe3b2578a7ec662b7f495b11b7d861c3ee68c9550d4dec20c10ff4f3b3ca3dd
'http://deb.debian.org/debian/pool/main/k/keyutils/keyutils_1.5.9.orig.tar.bz2' keyutils_1.5.9.orig.tar.bz2 74683 SHA256:4da2c5552c688b65ab14d4fd40fbdf720c8b396d8ece643e040cf6e707e083ae
'http://deb.debian.org/debian/pool/main/k/keyutils/keyutils_1.5.9-9.debian.tar.xz' keyutils_1.5.9-9.debian.tar.xz 17588 SHA256:2e9db3f51d902a4d8fa4bef3b914353f9f83ed53b9003f24b5fc44748f4d6d80
```

Likely also available for browsing at:

- https://sources.debian.net/src/keyutils/1.5.9-9/
- https://sources.debian.net/src/keyutils/1.5.9-9/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `krb5=1.15-1`

Binary Packages:

- `libgssapi-krb5-2:amd64=1.15-1`
- `libk5crypto3:amd64=1.15-1`
- `libkrb5-3:amd64=1.15-1`
- `libkrb5support0:amd64=1.15-1`

Licenses: (parsed from: `/usr/share/doc/libgssapi-krb5-2/copyright`, `/usr/share/doc/libk5crypto3/copyright`, `/usr/share/doc/libkrb5-3/copyright`, `/usr/share/doc/libkrb5support0/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris krb5=1.15-1
'http://deb.debian.org/debian/pool/main/k/krb5/krb5_1.15-1.dsc' krb5_1.15-1.dsc 3282 SHA256:ec2a3211b949480f2419dd4731e8213635d7dfcbe1658d1000cea8fa950599aa
'http://deb.debian.org/debian/pool/main/k/krb5/krb5_1.15.orig.tar.gz' krb5_1.15.orig.tar.gz 9327157 SHA256:fd34752774c808ab4f6f864f935c49945f5a56b62240b1ad4ab1af7b4ded127c
'http://deb.debian.org/debian/pool/main/k/krb5/krb5_1.15-1.debian.tar.xz' krb5_1.15-1.debian.tar.xz 141624 SHA256:ddad4ec3d024b1164d1726c767ed8ea4900454793f5a2ce53a5cf7a123c5b4e7
```

Likely also available for browsing at:

- https://sources.debian.net/src/krb5/1.15-1/
- https://sources.debian.net/src/krb5/1.15-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `lapack=3.7.0-2`

Binary Packages:

- `libblas-common=3.7.0-2`
- `libblas3=3.7.0-2`
- `liblapack3=3.7.0-2`

Licenses: (parsed from: `/usr/share/doc/libblas-common/copyright`, `/usr/share/doc/libblas3/copyright`, `/usr/share/doc/liblapack3/copyright`)

- `BSD-3-clause`
- `BSD-3-clause-intel`

Source:

```console
$ apt-get source -qq --print-uris lapack=3.7.0-2
'http://deb.debian.org/debian/pool/main/l/lapack/lapack_3.7.0-2.dsc' lapack_3.7.0-2.dsc 2900 SHA256:8e6a856bbf932f19456de2bad5b2955ae0ccb36e740d38afe011444be10fac9f
'http://deb.debian.org/debian/pool/main/l/lapack/lapack_3.7.0.orig.tar.gz' lapack_3.7.0.orig.tar.gz 7359812 SHA256:ed967e4307e986474ab02eb810eed1d1adc73f5e1e3bc78fb009f6fe766db3be
'http://deb.debian.org/debian/pool/main/l/lapack/lapack_3.7.0-2.debian.tar.xz' lapack_3.7.0-2.debian.tar.xz 21100 SHA256:bc423933dd01b179bee02649675f5b87f669945530b291aeb95229f5e8d51035
```

Likely also available for browsing at:

- https://sources.debian.net/src/lapack/3.7.0-2/
- https://sources.debian.net/src/lapack/3.7.0-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libarchive=3.2.2-2`

Binary Packages:

- `libarchive13:amd64=3.2.2-2`

Licenses: (parsed from: `/usr/share/doc/libarchive13/copyright`)

- `Apache-2.0`
- `BSD-1-clause-UCB`
- `BSD-124-clause-UCB`
- `BSD-2-clause`
- `BSD-3-clause-UCB`
- `BSD-4-clause-UCB`
- `Expat`
- `PD`

Source:

```console
$ apt-get source -qq --print-uris libarchive=3.2.2-2
'http://deb.debian.org/debian/pool/main/liba/libarchive/libarchive_3.2.2-2.dsc' libarchive_3.2.2-2.dsc 2482 SHA256:9b99d67a8c48e3b806c3e7cccbc7c65d9c638057e836427d2f287c1f882de826
'http://deb.debian.org/debian/pool/main/liba/libarchive/libarchive_3.2.2.orig.tar.gz' libarchive_3.2.2.orig.tar.gz 5458241 SHA256:691c194ee132d1f0f7a42541f091db811bc2e56f7107e9121be2bc8c04f1060f
'http://deb.debian.org/debian/pool/main/liba/libarchive/libarchive_3.2.2-2.debian.tar.xz' libarchive_3.2.2-2.debian.tar.xz 15220 SHA256:92e91195aabea4dfce3d26a38ff385922fe79051f3a7196ce350b44c592a967d
```

Likely also available for browsing at:

- https://sources.debian.net/src/libarchive/3.2.2-2/
- https://sources.debian.net/src/libarchive/3.2.2-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libassuan=2.4.3-2`

Binary Packages:

- `libassuan0:amd64=2.4.3-2`

Licenses: (parsed from: `/usr/share/doc/libassuan0/copyright`)

- `GAP`
- `GAP~FSF`
- `GPL-2`
- `GPL-2+`
- `GPL-2+ with libtool exception`
- `GPL-3`
- `GPL-3+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `LGPL-3`
- `LGPL-3+`

Source:

```console
$ apt-get source -qq --print-uris libassuan=2.4.3-2
'http://deb.debian.org/debian/pool/main/liba/libassuan/libassuan_2.4.3-2.dsc' libassuan_2.4.3-2.dsc 2412 SHA256:fc057ff6bd548161cd978f7847682928222d31db96bd94d7ec0fc84b176bbcc7
'http://deb.debian.org/debian/pool/main/liba/libassuan/libassuan_2.4.3.orig.tar.bz2' libassuan_2.4.3.orig.tar.bz2 559867 SHA256:22843a3bdb256f59be49842abf24da76700354293a066d82ade8134bb5aa2b71
'http://deb.debian.org/debian/pool/main/liba/libassuan/libassuan_2.4.3-2.debian.tar.xz' libassuan_2.4.3-2.debian.tar.xz 15076 SHA256:16dd66909cf3b79c71d5169f35d94be64d079d882f027577c00c23bff3148012
```

Likely also available for browsing at:

- https://sources.debian.net/src/libassuan/2.4.3-2/
- https://sources.debian.net/src/libassuan/2.4.3-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libcap-ng=0.7.7-3`

Binary Packages:

- `libcap-ng0:amd64=0.7.7-3+b1`

Licenses: (parsed from: `/usr/share/doc/libcap-ng0/copyright`)

- `GPL-2`
- `GPL-3`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libcap-ng=0.7.7-3
'http://deb.debian.org/debian/pool/main/libc/libcap-ng/libcap-ng_0.7.7-3.dsc' libcap-ng_0.7.7-3.dsc 1722 SHA256:6f5262f0ed2792c135e9b6bf7d30461cc3015249832f381505d21b9217a67685
'http://deb.debian.org/debian/pool/main/libc/libcap-ng/libcap-ng_0.7.7.orig.tar.gz' libcap-ng_0.7.7.orig.tar.gz 420178 SHA256:615549ce39b333f6b78baee0c0b4ef18bc726c6bf1cca123dfd89dd963f6d06b
'http://deb.debian.org/debian/pool/main/libc/libcap-ng/libcap-ng_0.7.7-3.debian.tar.xz' libcap-ng_0.7.7-3.debian.tar.xz 5248 SHA256:b7a0846dbd0451903bcbbe3a2696341f4e6000ebd64bed259c7fbf9dfc818363
```

Likely also available for browsing at:

- https://sources.debian.net/src/libcap-ng/0.7.7-3/
- https://sources.debian.net/src/libcap-ng/0.7.7-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `liberror-perl=0.17024-1`

Binary Packages:

- `liberror-perl=0.17024-1`

Licenses: (parsed from: `/usr/share/doc/liberror-perl/copyright`)

- `Artistic`
- `GPL-1`
- `GPL-1+`
- `MIT/X11`

Source:

```console
$ apt-get source -qq --print-uris liberror-perl=0.17024-1
'http://deb.debian.org/debian/pool/main/libe/liberror-perl/liberror-perl_0.17024-1.dsc' liberror-perl_0.17024-1.dsc 2193 SHA256:3d269abc34facfde4e4caf5d2eac38dbce07739d3fe2167ff982140af513d17e
'http://deb.debian.org/debian/pool/main/libe/liberror-perl/liberror-perl_0.17024.orig.tar.gz' liberror-perl_0.17024.orig.tar.gz 31269 SHA256:074db7c783a67b0667eca64a4f6a0c3de94998afc92c01d6453163eb04b9150d
'http://deb.debian.org/debian/pool/main/libe/liberror-perl/liberror-perl_0.17024-1.debian.tar.xz' liberror-perl_0.17024-1.debian.tar.xz 4028 SHA256:7b490f3655df007a1153883608161822036837eaf49f7d6014d3a096be4a65cb
```

Likely also available for browsing at:

- https://sources.debian.net/src/liberror-perl/0.17024-1/
- https://sources.debian.net/src/liberror-perl/0.17024-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libfabric=1.4.0-1`

Binary Packages:

- `libfabric1=1.4.0-1`

Licenses: (parsed from: `/usr/share/doc/libfabric1/copyright`)

- `BSD-2-clause`
- `Expat`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris libfabric=1.4.0-1
'http://deb.debian.org/debian/pool/main/libf/libfabric/libfabric_1.4.0-1.dsc' libfabric_1.4.0-1.dsc 2225 SHA256:de1b931feca012c8c479a677fc885abc22d30bcfd7e29c95d85b020bb7fa6d00
'http://deb.debian.org/debian/pool/main/libf/libfabric/libfabric_1.4.0.orig.tar.gz' libfabric_1.4.0.orig.tar.gz 1273062 SHA256:d18fffa7c79a0a262df80218af4e88832750552328518329364380a7b056950a
'http://deb.debian.org/debian/pool/main/libf/libfabric/libfabric_1.4.0-1.debian.tar.xz' libfabric_1.4.0-1.debian.tar.xz 4296 SHA256:ebfed6df68de162b30f75abefa3d3012a761e621aa83a07a999f69aebc329965
```

Likely also available for browsing at:

- https://sources.debian.net/src/libfabric/1.4.0-1/
- https://sources.debian.net/src/libfabric/1.4.0-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libffi=3.2.1-6`

Binary Packages:

- `libffi6:amd64=3.2.1-6`

Licenses: (parsed from: `/usr/share/doc/libffi6/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris libffi=3.2.1-6
'http://deb.debian.org/debian/pool/main/libf/libffi/libffi_3.2.1-6.dsc' libffi_3.2.1-6.dsc 1923 SHA256:f901298b078c7d7f3f75459b5ff74cc804f6f2cfd65ed619d2082d5f77089954
'http://deb.debian.org/debian/pool/main/libf/libffi/libffi_3.2.1.orig.tar.gz' libffi_3.2.1.orig.tar.gz 940837 SHA256:d06ebb8e1d9a22d19e38d63fdb83954253f39bedc5d46232a05645685722ca37
'http://deb.debian.org/debian/pool/main/libf/libffi/libffi_3.2.1-6.debian.tar.xz' libffi_3.2.1-6.debian.tar.xz 11252 SHA256:477709fa90f8c7631fa226a48cdf38737c9f195f3686f62aa76714bcffaee512
```

Likely also available for browsing at:

- https://sources.debian.net/src/libffi/3.2.1-6/
- https://sources.debian.net/src/libffi/3.2.1-6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libfile-fcntllock-perl=0.22-3`

Binary Packages:

- `libfile-fcntllock-perl=0.22-3+b2`

Licenses: (parsed from: `/usr/share/doc/libfile-fcntllock-perl/copyright`)

- `Artistic`
- `GPL-1`
- `GPL-1+`

Source:

```console
$ apt-get source -qq --print-uris libfile-fcntllock-perl=0.22-3
'http://deb.debian.org/debian/pool/main/libf/libfile-fcntllock-perl/libfile-fcntllock-perl_0.22-3.dsc' libfile-fcntllock-perl_0.22-3.dsc 2249 SHA256:dc57910fcce4130880aef85acbdb06650f6f1db67be65f6312c48e6ea5929ce9
'http://deb.debian.org/debian/pool/main/libf/libfile-fcntllock-perl/libfile-fcntllock-perl_0.22.orig.tar.gz' libfile-fcntllock-perl_0.22.orig.tar.gz 16994 SHA256:9a9abb2efff93ab73741a128d3f700e525273546c15d04e7c51c704ab09dbcdf
'http://deb.debian.org/debian/pool/main/libf/libfile-fcntllock-perl/libfile-fcntllock-perl_0.22-3.debian.tar.xz' libfile-fcntllock-perl_0.22-3.debian.tar.xz 2412 SHA256:dffb00f7f546a9eb9d47206143f0dfd1d982281d5b2b7f37f1812c9f8c2bffd8
```

Likely also available for browsing at:

- https://sources.debian.net/src/libfile-fcntllock-perl/0.22-3/
- https://sources.debian.net/src/libfile-fcntllock-perl/0.22-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libgcrypt20=1.7.6-2+deb9u1`

Binary Packages:

- `libgcrypt20:amd64=1.7.6-2+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libgcrypt20/copyright`)

- `GPL-2`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris libgcrypt20=1.7.6-2+deb9u1
'http://deb.debian.org/debian/pool/main/libg/libgcrypt20/libgcrypt20_1.7.6-2+deb9u1.dsc' libgcrypt20_1.7.6-2+deb9u1.dsc 2942 SHA256:b83c76db58ec1e27257df872e342d2045a476819549252e0ffeb03ed2cbe570c
'http://deb.debian.org/debian/pool/main/libg/libgcrypt20/libgcrypt20_1.7.6.orig.tar.bz2' libgcrypt20_1.7.6.orig.tar.bz2 2897695 SHA256:626aafee84af9d2ce253d2c143dc1c0902dda045780cc241f39970fc60be05bc
'http://deb.debian.org/debian/pool/main/libg/libgcrypt20/libgcrypt20_1.7.6.orig.tar.bz2.asc' libgcrypt20_1.7.6.orig.tar.bz2.asc 310 SHA256:91ad5a0efafb0edc63c083f733ce476b2a0da663aea5118126aa63825d314e00
'http://deb.debian.org/debian/pool/main/libg/libgcrypt20/libgcrypt20_1.7.6-2+deb9u1.debian.tar.xz' libgcrypt20_1.7.6-2+deb9u1.debian.tar.xz 30308 SHA256:df274675ca3dce4dcbf9ec58e75fdf279a492f4fc91aa2f2d52d368ee9c0ed82
```

Likely also available for browsing at:

- https://sources.debian.net/src/libgcrypt20/1.7.6-2+deb9u1/
- https://sources.debian.net/src/libgcrypt20/1.7.6-2+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libgpg-error=1.26-2`

Binary Packages:

- `libgpg-error0:amd64=1.26-2`

Licenses: (parsed from: `/usr/share/doc/libgpg-error0/copyright`)

- `GPL-2.1+`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libgpg-error=1.26-2
'http://deb.debian.org/debian/pool/main/libg/libgpg-error/libgpg-error_1.26-2.dsc' libgpg-error_1.26-2.dsc 2454 SHA256:ea53df72d922f224cf0bb69df5a20100a2a5826e890741277425269d70eade20
'http://deb.debian.org/debian/pool/main/libg/libgpg-error/libgpg-error_1.26.orig.tar.bz2' libgpg-error_1.26.orig.tar.bz2 798096 SHA256:4c4bcbc90116932e3acd37b37812d8653b1b189c1904985898e860af818aee69
'http://deb.debian.org/debian/pool/main/libg/libgpg-error/libgpg-error_1.26-2.debian.tar.xz' libgpg-error_1.26-2.debian.tar.xz 12740 SHA256:20a73d5bcc4f523ae16b9279698c01b37dd5cffd2b7dc317c65923aa115ca46c
```

Likely also available for browsing at:

- https://sources.debian.net/src/libgpg-error/1.26-2/
- https://sources.debian.net/src/libgpg-error/1.26-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libibverbs=1.2.1-2`

Binary Packages:

- `libibverbs-dev=1.2.1-2`
- `libibverbs1=1.2.1-2`

Licenses: (parsed from: `/usr/share/doc/libibverbs-dev/copyright`, `/usr/share/doc/libibverbs1/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris libibverbs=1.2.1-2
'http://deb.debian.org/debian/pool/main/libi/libibverbs/libibverbs_1.2.1-2.dsc' libibverbs_1.2.1-2.dsc 2241 SHA256:b423f783b240aeec616f4be98fc2d97310d3afb9ee75651c33585d577674090e
'http://deb.debian.org/debian/pool/main/libi/libibverbs/libibverbs_1.2.1.orig.tar.gz' libibverbs_1.2.1.orig.tar.gz 456666 SHA256:c352a7f24e9a9d30ea74faa35d1b721d78d770506a0c03732e3132b7c85ac330
'http://deb.debian.org/debian/pool/main/libi/libibverbs/libibverbs_1.2.1-2.debian.tar.xz' libibverbs_1.2.1-2.debian.tar.xz 6240 SHA256:97d740db2ab169c74cac5b35d9fa0bed06069333758a5f5e9f7a9fa0540a57eb
```

Likely also available for browsing at:

- https://sources.debian.net/src/libibverbs/1.2.1-2/
- https://sources.debian.net/src/libibverbs/1.2.1-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libidn2-0=0.16-1`

Binary Packages:

- `libidn2-0:amd64=0.16-1`

Licenses: (parsed from: `/usr/share/doc/libidn2-0/copyright`)

- `GPL-2+`
- `GPL-3`
- `GPL-3+`
- `LGPL-3+`
- `Unicode`

Source:

```console
$ apt-get source -qq --print-uris libidn2-0=0.16-1
'http://deb.debian.org/debian/pool/main/libi/libidn2-0/libidn2-0_0.16-1.dsc' libidn2-0_0.16-1.dsc 1786 SHA256:d806657d36a5836ab08ccc5488372d7b95c03e10964b1c692b0948e6805bc84e
'http://deb.debian.org/debian/pool/main/libi/libidn2-0/libidn2-0_0.16.orig.tar.gz' libidn2-0_0.16.orig.tar.gz 1494295 SHA256:2fad9efff4082ae2143f69df76339ca99379e0e0f4231455f5d3d9d2089c688f
'http://deb.debian.org/debian/pool/main/libi/libidn2-0/libidn2-0_0.16-1.debian.tar.xz' libidn2-0_0.16-1.debian.tar.xz 57392 SHA256:9b643e5a5bd9f3eff52cd5508b1f15f44fe32bca4c1a6c3aa04ebad59d16272d
```

Likely also available for browsing at:

- https://sources.debian.net/src/libidn2-0/0.16-1/
- https://sources.debian.net/src/libidn2-0/0.16-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libidn=1.33-1`

Binary Packages:

- `libidn11:amd64=1.33-1`

Licenses: (parsed from: `/usr/share/doc/libidn11/copyright`)

- `GAP`
- `GFDL-1.3`
- `GFDL-1.3+`
- `GPL-2`
- `GPL-2+`
- `GPL-3`
- `GPL-3+`
- `LGPL-2`
- `LGPL-2.1`
- `LGPL-2.1+`
- `LGPL-3`
- `LGPL-3+`

Source:

```console
$ apt-get source -qq --print-uris libidn=1.33-1
'http://deb.debian.org/debian/pool/main/libi/libidn/libidn_1.33-1.dsc' libidn_1.33-1.dsc 1848 SHA256:f076f7dddc45717542a48123d7dddb638beebe8521f5fba29f2d148fdcf12bf0
'http://deb.debian.org/debian/pool/main/libi/libidn/libidn_1.33.orig.tar.gz' libidn_1.33.orig.tar.gz 3501056 SHA256:44a7aab635bb721ceef6beecc4d49dfd19478325e1b47f3196f7d2acc4930e19
'http://deb.debian.org/debian/pool/main/libi/libidn/libidn_1.33-1.debian.tar.xz' libidn_1.33-1.debian.tar.xz 60264 SHA256:a50ee1e2598670ca1166d218e546c4cc031c658188b1193b73d98175d4405ef0
```

Likely also available for browsing at:

- https://sources.debian.net/src/libidn/1.33-1/
- https://sources.debian.net/src/libidn/1.33-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libjsoncpp=1.7.4-3`

Binary Packages:

- `libjsoncpp1:amd64=1.7.4-3`

Licenses: (parsed from: `/usr/share/doc/libjsoncpp1/copyright`)

- `Expat_or_PublicDomain_or_DualExpatPD`
- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris libjsoncpp=1.7.4-3
'http://deb.debian.org/debian/pool/main/libj/libjsoncpp/libjsoncpp_1.7.4-3.dsc' libjsoncpp_1.7.4-3.dsc 2137 SHA256:8f8d17cb824b288e140988e489b953f7ca084b094a06cc39867a4af1faf1f421
'http://deb.debian.org/debian/pool/main/libj/libjsoncpp/libjsoncpp_1.7.4.orig.tar.gz' libjsoncpp_1.7.4.orig.tar.gz 205752 SHA256:10dcd0677e80727e572a1e462193e51a5fde3e023b99e144b2ee1a469835f769
'http://deb.debian.org/debian/pool/main/libj/libjsoncpp/libjsoncpp_1.7.4-3.debian.tar.xz' libjsoncpp_1.7.4-3.debian.tar.xz 7828 SHA256:4d99ab057737a02512e75404315ee0b723823f6caed4401c25e46925c4c8857e
```

Likely also available for browsing at:

- https://sources.debian.net/src/libjsoncpp/1.7.4-3/
- https://sources.debian.net/src/libjsoncpp/1.7.4-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libksba=1.3.5-2`

Binary Packages:

- `libksba8:amd64=1.3.5-2`

Licenses: (parsed from: `/usr/share/doc/libksba8/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris libksba=1.3.5-2
'http://deb.debian.org/debian/pool/main/libk/libksba/libksba_1.3.5-2.dsc' libksba_1.3.5-2.dsc 2526 SHA256:4fd08fd129f97ab1df86c220b88b7b2c6e4e04aa90bfd3ae364d18022256bef8
'http://deb.debian.org/debian/pool/main/libk/libksba/libksba_1.3.5.orig.tar.bz2' libksba_1.3.5.orig.tar.bz2 620649 SHA256:41444fd7a6ff73a79ad9728f985e71c9ba8cd3e5e53358e70d5f066d35c1a340
'http://deb.debian.org/debian/pool/main/libk/libksba/libksba_1.3.5.orig.tar.bz2.asc' libksba_1.3.5.orig.tar.bz2.asc 287 SHA256:a954b03144ee882c838853da24fd7b6868b78df72a18c71079217d968698a76f
'http://deb.debian.org/debian/pool/main/libk/libksba/libksba_1.3.5-2.debian.tar.xz' libksba_1.3.5-2.debian.tar.xz 13852 SHA256:98c985bff973be1aecc702fa15887ff1e5b8de481d1dc3e99423a587754eaabd
```

Likely also available for browsing at:

- https://sources.debian.net/src/libksba/1.3.5-2/
- https://sources.debian.net/src/libksba/1.3.5-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `liblocale-gettext-perl=1.07-3`

Binary Packages:

- `liblocale-gettext-perl=1.07-3+b1`

Licenses: (parsed from: `/usr/share/doc/liblocale-gettext-perl/copyright`)

- `Artistic`
- `GPL-1`
- `GPL-1+`

Source:

```console
$ apt-get source -qq --print-uris liblocale-gettext-perl=1.07-3
'http://deb.debian.org/debian/pool/main/libl/liblocale-gettext-perl/liblocale-gettext-perl_1.07-3.dsc' liblocale-gettext-perl_1.07-3.dsc 2174 SHA256:d123ae22d270522ebe9a425f2f0dd7743b79518a462589521d2d8f0b5e1ee728
'http://deb.debian.org/debian/pool/main/libl/liblocale-gettext-perl/liblocale-gettext-perl_1.07.orig.tar.gz' liblocale-gettext-perl_1.07.orig.tar.gz 8651 SHA256:909d47954697e7c04218f972915b787bd1244d75e3bd01620bc167d5bbc49c15
'http://deb.debian.org/debian/pool/main/libl/liblocale-gettext-perl/liblocale-gettext-perl_1.07-3.debian.tar.xz' liblocale-gettext-perl_1.07-3.debian.tar.xz 5504 SHA256:90ed1d26a14da585e6a7890bbf7393f14eed7cc4bbce0a70d4264823869b86ac
```

Likely also available for browsing at:

- https://sources.debian.net/src/liblocale-gettext-perl/1.07-3/
- https://sources.debian.net/src/liblocale-gettext-perl/1.07-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libmnl=1.0.4-2`

Binary Packages:

- `libmnl0:amd64=1.0.4-2`

Licenses: (parsed from: `/usr/share/doc/libmnl0/copyright`)

- `GPL-2`
- `GPL-2+`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libmnl=1.0.4-2
'http://deb.debian.org/debian/pool/main/libm/libmnl/libmnl_1.0.4-2.dsc' libmnl_1.0.4-2.dsc 1994 SHA256:131106bb7eb4a94fa8e8c135f92c38068d0b42681f166eb159137f171c568630
'http://deb.debian.org/debian/pool/main/libm/libmnl/libmnl_1.0.4.orig.tar.bz2' libmnl_1.0.4.orig.tar.bz2 301270 SHA256:171f89699f286a5854b72b91d06e8f8e3683064c5901fb09d954a9ab6f551f81
'http://deb.debian.org/debian/pool/main/libm/libmnl/libmnl_1.0.4-2.debian.tar.xz' libmnl_1.0.4-2.debian.tar.xz 7512 SHA256:208d62777081ffe6d7dffde0d7370cefb03fe0a6a0486a1b50f6b7b8e9a5b068
```

Likely also available for browsing at:

- https://sources.debian.net/src/libmnl/1.0.4-2/
- https://sources.debian.net/src/libmnl/1.0.4-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libnl3=3.2.27-2`

Binary Packages:

- `libnl-3-200:amd64=3.2.27-2`
- `libnl-route-3-200:amd64=3.2.27-2`

Licenses: (parsed from: `/usr/share/doc/libnl-3-200/copyright`, `/usr/share/doc/libnl-route-3-200/copyright`)

- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libnl3=3.2.27-2
'http://deb.debian.org/debian/pool/main/libn/libnl3/libnl3_3.2.27-2.dsc' libnl3_3.2.27-2.dsc 2735 SHA256:fc5d08f7ef2bf88f445bd4e85695a96dca86cfa522ed4cdc3009e1e995a4cd9b
'http://deb.debian.org/debian/pool/main/libn/libnl3/libnl3_3.2.27.orig.tar.gz' libnl3_3.2.27.orig.tar.gz 905330 SHA256:4bbbf92b3c78a90f423cf96260bf419a28b75db8cced47051217a56795f58ec6
'http://deb.debian.org/debian/pool/main/libn/libnl3/libnl3_3.2.27-2.debian.tar.xz' libnl3_3.2.27-2.debian.tar.xz 19288 SHA256:3ce543debcf41d71767fa7e7bafeb9dab330aef693543a49d97dc0c4c3076e10
```

Likely also available for browsing at:

- https://sources.debian.net/src/libnl3/3.2.27-2/
- https://sources.debian.net/src/libnl3/3.2.27-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libpciaccess=0.13.4-1`

Binary Packages:

- `libpciaccess0:amd64=0.13.4-1+b2`

Licenses: (parsed from: `/usr/share/doc/libpciaccess0/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris libpciaccess=0.13.4-1
'http://deb.debian.org/debian/pool/main/libp/libpciaccess/libpciaccess_0.13.4-1.dsc' libpciaccess_0.13.4-1.dsc 2060 SHA256:c7413e1b3804ae83667d0144eabb5bcba046a16c12f20f94d861edb71a9f67e8
'http://deb.debian.org/debian/pool/main/libp/libpciaccess/libpciaccess_0.13.4.orig.tar.gz' libpciaccess_0.13.4.orig.tar.gz 440390 SHA256:74d92bda448e6fdb64fee4e0091255f48d625d07146a121653022ed3a0ca1f2f
'http://deb.debian.org/debian/pool/main/libp/libpciaccess/libpciaccess_0.13.4-1.diff.gz' libpciaccess_0.13.4-1.diff.gz 24145 SHA256:72e06952d417e15ee23766815f8f10555c2504189f9420a3b6df0be25e972650
```

Likely also available for browsing at:

- https://sources.debian.net/src/libpciaccess/0.13.4-1/
- https://sources.debian.net/src/libpciaccess/0.13.4-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libpipeline=1.4.1-2`

Binary Packages:

- `libpipeline1:amd64=1.4.1-2`

Licenses: (parsed from: `/usr/share/doc/libpipeline1/copyright`)

- `GPL-2`
- `GPL-2+`
- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris libpipeline=1.4.1-2
'http://deb.debian.org/debian/pool/main/libp/libpipeline/libpipeline_1.4.1-2.dsc' libpipeline_1.4.1-2.dsc 2109 SHA256:6c9f780b8e0d3f9e82964d35c8d750266140ddacae3b676d2413752c680f4702
'http://deb.debian.org/debian/pool/main/libp/libpipeline/libpipeline_1.4.1.orig.tar.gz' libpipeline_1.4.1.orig.tar.gz 805172 SHA256:da46d7b20163aadb9db2faae483f734e9096a7550c84b94029abeab62dd1b9ee
'http://deb.debian.org/debian/pool/main/libp/libpipeline/libpipeline_1.4.1-2.debian.tar.xz' libpipeline_1.4.1-2.debian.tar.xz 197384 SHA256:dbd0c3af6d12cf2adeef06529394c42c4082822f0f75d914c59d61db4a400089
```

Likely also available for browsing at:

- https://sources.debian.net/src/libpipeline/1.4.1-2/
- https://sources.debian.net/src/libpipeline/1.4.1-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libpsl=0.17.0-3`

Binary Packages:

- `libpsl5:amd64=0.17.0-3`

Licenses: (parsed from: `/usr/share/doc/libpsl5/copyright`)

- `Chromium`
- `MIT`

Source:

```console
$ apt-get source -qq --print-uris libpsl=0.17.0-3
'http://deb.debian.org/debian/pool/main/libp/libpsl/libpsl_0.17.0-3.dsc' libpsl_0.17.0-3.dsc 2224 SHA256:20a4c84ba8348ed3839dd79fdafc230f7a0463a68f5af6a2b81b81ba33f77501
'http://deb.debian.org/debian/pool/main/libp/libpsl/libpsl_0.17.0.orig.tar.gz' libpsl_0.17.0.orig.tar.gz 49087 SHA256:7731e28393e1b4ca363eaffecd6c7570023a7c18c017b45d683ac7d2ba1f0bd1
'http://deb.debian.org/debian/pool/main/libp/libpsl/libpsl_0.17.0-3.debian.tar.xz' libpsl_0.17.0-3.debian.tar.xz 8516 SHA256:d0bd2abdaccadf2603f566e119b949a02523177199455e01c13a9c9deac1e6c3
```

Likely also available for browsing at:

- https://sources.debian.net/src/libpsl/0.17.0-3/
- https://sources.debian.net/src/libpsl/0.17.0-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `librdmacm=1.1.0-2`

Binary Packages:

- `librdmacm1=1.1.0-2`

Licenses: (parsed from: `/usr/share/doc/librdmacm1/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris librdmacm=1.1.0-2
'http://deb.debian.org/debian/pool/main/libr/librdmacm/librdmacm_1.1.0-2.dsc' librdmacm_1.1.0-2.dsc 2221 SHA256:24806e5a4b135da922a2dd65196c89c4e36a81444953858f45827c8f219ba8ed
'http://deb.debian.org/debian/pool/main/libr/librdmacm/librdmacm_1.1.0.orig.tar.gz' librdmacm_1.1.0.orig.tar.gz 406442 SHA256:8f10848d4810585d6d70b443abc876c1db8df5e9b8b07e095c7e6eaf4ac380c5
'http://deb.debian.org/debian/pool/main/libr/librdmacm/librdmacm_1.1.0-2.debian.tar.xz' librdmacm_1.1.0-2.debian.tar.xz 6684 SHA256:79adac19f4faf738d53dd5bb800e25a9f24241cb7de16a8064aa36abb2d86030
```

Likely also available for browsing at:

- https://sources.debian.net/src/librdmacm/1.1.0-2/
- https://sources.debian.net/src/librdmacm/1.1.0-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libselinux=2.6-3`

Binary Packages:

- `libselinux1:amd64=2.6-3+b1`

Licenses: (parsed from: `/usr/share/doc/libselinux1/copyright`)

- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libselinux=2.6-3
'http://deb.debian.org/debian/pool/main/libs/libselinux/libselinux_2.6-3.dsc' libselinux_2.6-3.dsc 2217 SHA256:91bb53feba8031bfc7b0110fc4e0e1dae4a8e2906f4a524f83252a95ae0e639c
'http://deb.debian.org/debian/pool/main/libs/libselinux/libselinux_2.6.orig.tar.gz' libselinux_2.6.orig.tar.gz 203119 SHA256:4ea2dde50665c202253ba5caac7738370ea0337c47b251ba981c60d24e1a118a
'http://deb.debian.org/debian/pool/main/libs/libselinux/libselinux_2.6-3.debian.tar.xz' libselinux_2.6-3.debian.tar.xz 24396 SHA256:5a06841565e7907bc0dae9f8ed5940d040316192bd9662df59c79af7c212a171
```

Likely also available for browsing at:

- https://sources.debian.net/src/libselinux/2.6-3/
- https://sources.debian.net/src/libselinux/2.6-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libsemanage=2.6-2`

Binary Packages:

- `libsemanage-common=2.6-2`
- `libsemanage1:amd64=2.6-2`

Licenses: (parsed from: `/usr/share/doc/libsemanage-common/copyright`, `/usr/share/doc/libsemanage1/copyright`)

- `GPL`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris libsemanage=2.6-2
'http://deb.debian.org/debian/pool/main/libs/libsemanage/libsemanage_2.6-2.dsc' libsemanage_2.6-2.dsc 2338 SHA256:2806bf3591dc7eb4c80d647a9e65df13d03657cfa6e049de1035165e0d8484d0
'http://deb.debian.org/debian/pool/main/libs/libsemanage/libsemanage_2.6.orig.tar.gz' libsemanage_2.6.orig.tar.gz 155897 SHA256:4f81541047290b751f2ffb926fcd381c186f22db18d9fe671b0b4a6a54e8cfce
'http://deb.debian.org/debian/pool/main/libs/libsemanage/libsemanage_2.6-2.debian.tar.xz' libsemanage_2.6-2.debian.tar.xz 17088 SHA256:3d1c4c5ea5d4f27a521b64ba3fc499c8b662257ffec773706501f466032db8cf
```

Likely also available for browsing at:

- https://sources.debian.net/src/libsemanage/2.6-2/
- https://sources.debian.net/src/libsemanage/2.6-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libsepol=2.6-2`

Binary Packages:

- `libsepol1:amd64=2.6-2`

Licenses: (parsed from: `/usr/share/doc/libsepol1/copyright`)

- `GPL`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris libsepol=2.6-2
'http://deb.debian.org/debian/pool/main/libs/libsepol/libsepol_2.6-2.dsc' libsepol_2.6-2.dsc 1814 SHA256:197ddaf44a5139d7ca6c12ce6b29fca0589f72c59ac588a7fa39d11b2e65778a
'http://deb.debian.org/debian/pool/main/libs/libsepol/libsepol_2.6.orig.tar.gz' libsepol_2.6.orig.tar.gz 442549 SHA256:d856d6506054f52abeaa3543ea2f2344595a3dc05d0d873ed7f724f7a16b1874
'http://deb.debian.org/debian/pool/main/libs/libsepol/libsepol_2.6-2.debian.tar.xz' libsepol_2.6-2.debian.tar.xz 14320 SHA256:d7a1022d03eb53a8d30262e06f14f691e553b3db684ca0f3549cd17b93fb7465
```

Likely also available for browsing at:

- https://sources.debian.net/src/libsepol/2.6-2/
- https://sources.debian.net/src/libsepol/2.6-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libssh2=1.7.0-1`

Binary Packages:

- `libssh2-1:amd64=1.7.0-1`

Licenses: (parsed from: `/usr/share/doc/libssh2-1/copyright`)

- `BSD3`

Source:

```console
$ apt-get source -qq --print-uris libssh2=1.7.0-1
'http://deb.debian.org/debian/pool/main/libs/libssh2/libssh2_1.7.0-1.dsc' libssh2_1.7.0-1.dsc 1828 SHA256:4f2880ce02d40c4904f750687424e9f2c1aa68a4632da9866e08c809a69f7425
'http://deb.debian.org/debian/pool/main/libs/libssh2/libssh2_1.7.0.orig.tar.gz' libssh2_1.7.0.orig.tar.gz 811714 SHA256:e4561fd43a50539a8c2ceb37841691baf03ecb7daf043766da1b112e4280d584
'http://deb.debian.org/debian/pool/main/libs/libssh2/libssh2_1.7.0-1.debian.tar.xz' libssh2_1.7.0-1.debian.tar.xz 6396 SHA256:2f4fb78f0d6d33492ef63e04a0d007f03e56466542c0b8271bbcdcb530f31f8e
```

Likely also available for browsing at:

- https://sources.debian.net/src/libssh2/1.7.0-1/
- https://sources.debian.net/src/libssh2/1.7.0-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libtasn1-6=4.10-1.1`

Binary Packages:

- `libtasn1-6:amd64=4.10-1.1`

Licenses: (parsed from: `/usr/share/doc/libtasn1-6/copyright`)

- `GFDL-1.3`
- `GPL-3`
- `LGPL`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris libtasn1-6=4.10-1.1
'http://deb.debian.org/debian/pool/main/libt/libtasn1-6/libtasn1-6_4.10-1.1.dsc' libtasn1-6_4.10-1.1.dsc 2586 SHA256:1ace0b64d79a7c79d00d9f7719ce56c5274fbfd253681f01b303badb09242c1b
'http://deb.debian.org/debian/pool/main/libt/libtasn1-6/libtasn1-6_4.10.orig.tar.gz' libtasn1-6_4.10.orig.tar.gz 1887057 SHA256:681a4d9a0d259f2125713f2e5766c5809f151b3a1392fd91390f780b4b8f5a02
'http://deb.debian.org/debian/pool/main/libt/libtasn1-6/libtasn1-6_4.10-1.1.debian.tar.xz' libtasn1-6_4.10-1.1.debian.tar.xz 58400 SHA256:275f7e74697ca1ef085dab5e41fe82d0c9ee898d4f6f4cd2873b09099850e939
```

Likely also available for browsing at:

- https://sources.debian.net/src/libtasn1-6/4.10-1.1/
- https://sources.debian.net/src/libtasn1-6/4.10-1.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libtool=2.4.6-2`

Binary Packages:

- `libltdl-dev:amd64=2.4.6-2`
- `libltdl7:amd64=2.4.6-2`
- `libtool=2.4.6-2`

Licenses: (parsed from: `/usr/share/doc/libltdl-dev/copyright`, `/usr/share/doc/libltdl7/copyright`, `/usr/share/doc/libtool/copyright`)

- `GFDL`
- `GPL`

Source:

```console
$ apt-get source -qq --print-uris libtool=2.4.6-2
'http://deb.debian.org/debian/pool/main/libt/libtool/libtool_2.4.6-2.dsc' libtool_2.4.6-2.dsc 2324 SHA256:caa2b9d5c32e491388d0627e2f808b6cb2f260dd1b0b9fdafc9bff957f05bb29
'http://deb.debian.org/debian/pool/main/libt/libtool/libtool_2.4.6.orig.tar.xz' libtool_2.4.6.orig.tar.xz 973080 SHA256:7c87a8c2c8c0fc9cd5019e402bed4292462d00a718a7cd5f11218153bf28b26f
'http://deb.debian.org/debian/pool/main/libt/libtool/libtool_2.4.6.orig.tar.xz.asc' libtool_2.4.6.orig.tar.xz.asc 380 SHA256:ab68ebc45d60128a71fc36167cd29dcf3c3d6d639fd28663905ebaf3e2f43d6a
'http://deb.debian.org/debian/pool/main/libt/libtool/libtool_2.4.6-2.debian.tar.xz' libtool_2.4.6-2.debian.tar.xz 36024 SHA256:6227fb1240a90ef06855567e71ee96e4950dd53c4399348f36c1ec39367cd8ea
```

Likely also available for browsing at:

- https://sources.debian.net/src/libtool/2.4.6-2/
- https://sources.debian.net/src/libtool/2.4.6-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libunistring=0.9.6+really0.9.3-0.1`

Binary Packages:

- `libunistring0:amd64=0.9.6+really0.9.3-0.1`

Licenses: (parsed from: `/usr/share/doc/libunistring0/copyright`)

- `GFDL-1.2`
- `GFDL-1.2+`
- `GPL-2`
- `GPL-2+`
- `GPL-2+ with exception`
- `GPL-3`
- `GPL-3+`
- `LGPL-3`
- `LGPL-3+`
- `MIT`

Source:

```console
$ apt-get source -qq --print-uris libunistring=0.9.6+really0.9.3-0.1
'http://deb.debian.org/debian/pool/main/libu/libunistring/libunistring_0.9.6+really0.9.3-0.1.dsc' libunistring_0.9.6+really0.9.3-0.1.dsc 2109 SHA256:bf73a89a416333268ac9b457a06d1d92e5402c4f392187ad30e6146ffd3600ae
'http://deb.debian.org/debian/pool/main/libu/libunistring/libunistring_0.9.6+really0.9.3.orig.tar.gz' libunistring_0.9.6+really0.9.3.orig.tar.gz 2555215 SHA256:610d3ec724fbdaa654afe3cff20b9f4d504be3fd296fded2e0f7f764041006a3
'http://deb.debian.org/debian/pool/main/libu/libunistring/libunistring_0.9.6+really0.9.3-0.1.debian.tar.xz' libunistring_0.9.6+really0.9.3-0.1.debian.tar.xz 35372 SHA256:2d7636b16a56f1ad09748121a2181db4c2687fa83324c2f17bf451ee01b9de93
```

Likely also available for browsing at:

- https://sources.debian.net/src/libunistring/0.9.6+really0.9.3-0.1/
- https://sources.debian.net/src/libunistring/0.9.6+really0.9.3-0.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libuv1=1.9.1-3`

Binary Packages:

- `libuv1:amd64=1.9.1-3`

Licenses: (parsed from: `/usr/share/doc/libuv1/copyright`)

- `BSD-1-clause`
- `BSD-2-clause`
- `BSD-3-clause`
- `Expat`
- `ISC`

Source:

```console
$ apt-get source -qq --print-uris libuv1=1.9.1-3
'http://deb.debian.org/debian/pool/main/libu/libuv1/libuv1_1.9.1-3.dsc' libuv1_1.9.1-3.dsc 2082 SHA256:2618e5463c68375c02390d53baf26122d4b8ee2052ed6d9cbbced8db69d85eaa
'http://deb.debian.org/debian/pool/main/libu/libuv1/libuv1_1.9.1.orig.tar.gz' libuv1_1.9.1.orig.tar.gz 1054443 SHA256:e83953782c916d7822ef0b94e8115ce5756fab5300cca173f0de5f5b0e0ae928
'http://deb.debian.org/debian/pool/main/libu/libuv1/libuv1_1.9.1-3.debian.tar.xz' libuv1_1.9.1-3.debian.tar.xz 24284 SHA256:a3f12bd335d0feb87eda7d015ec613de3782565c1b6ee20126bf8151aebc6d1a
```

Likely also available for browsing at:

- https://sources.debian.net/src/libuv1/1.9.1-3/
- https://sources.debian.net/src/libuv1/1.9.1-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libxml2=2.9.4+dfsg1-2.2`

Binary Packages:

- `libxml2:amd64=2.9.4+dfsg1-2.2`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris libxml2=2.9.4+dfsg1-2.2
'http://deb.debian.org/debian/pool/main/libx/libxml2/libxml2_2.9.4+dfsg1-2.2.dsc' libxml2_2.9.4+dfsg1-2.2.dsc 2891 SHA256:748bf3236c22911a89bc3b50268626b9aafe4557114aad21684493e5dc30156c
'http://deb.debian.org/debian/pool/main/libx/libxml2/libxml2_2.9.4+dfsg1.orig.tar.xz' libxml2_2.9.4+dfsg1.orig.tar.xz 2446412 SHA256:a74ad55e346aa0b2b41903e66d21f8f3d2a736b3f41e32496376861ab484184e
'http://deb.debian.org/debian/pool/main/libx/libxml2/libxml2_2.9.4+dfsg1-2.2.debian.tar.xz' libxml2_2.9.4+dfsg1-2.2.debian.tar.xz 28936 SHA256:c038bba02a56164cef7728509ba3c8f1856018573769ee9ffcc48c565e90bdc9
```

Likely also available for browsing at:

- https://sources.debian.net/src/libxml2/2.9.4+dfsg1-2.2/
- https://sources.debian.net/src/libxml2/2.9.4+dfsg1-2.2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `libyaml=0.1.7-2`

Binary Packages:

- `libyaml-0-2:amd64=0.1.7-2`

Licenses: (parsed from: `/usr/share/doc/libyaml-0-2/copyright`)

- `Expat`
- `permissive`

Source:

```console
$ apt-get source -qq --print-uris libyaml=0.1.7-2
'http://deb.debian.org/debian/pool/main/liby/libyaml/libyaml_0.1.7-2.dsc' libyaml_0.1.7-2.dsc 1820 SHA256:f2e599adcf8336c4be374987112a0c823b4609dc0f5a944e5827651241d91645
'http://deb.debian.org/debian/pool/main/liby/libyaml/libyaml_0.1.7.orig.tar.gz' libyaml_0.1.7.orig.tar.gz 527518 SHA256:8088e457264a98ba451a90b8661fcb4f9d6f478f7265d48322a196cec2480729
'http://deb.debian.org/debian/pool/main/liby/libyaml/libyaml_0.1.7-2.debian.tar.xz' libyaml_0.1.7-2.debian.tar.xz 4016 SHA256:6fc7065491dd6f86b46e6f231ae8ab60f8aafbef2dcf4721598644024485b801
```

Likely also available for browsing at:

- https://sources.debian.net/src/libyaml/0.1.7-2/
- https://sources.debian.net/src/libyaml/0.1.7-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `linux=4.9.30-2+deb9u3`

Binary Packages:

- `linux-libc-dev:amd64=4.9.30-2+deb9u3`

Licenses: (parsed from: `/usr/share/doc/linux-libc-dev/copyright`)

- `CRYPTOGAMS`
- `GPL-2`
- `LGPL-2.1`
- `Unicode-data`
- `Xen-interface`

Source:

```console
$ apt-get source -qq --print-uris linux=4.9.30-2+deb9u3
'http://security.debian.org/pool/updates/main/l/linux/linux_4.9.30-2+deb9u3.dsc' linux_4.9.30-2+deb9u3.dsc 123291 SHA256:f0314677ff16908f08dca68651c310bd2ae92ac6449ef2b0fcdb18a6750f3387
'http://security.debian.org/pool/updates/main/l/linux/linux_4.9.30.orig.tar.xz' linux_4.9.30.orig.tar.xz 94471128 SHA256:4a5afc3589825f514c5908e8421e81695648dad62357343494c3dd07edb29306
'http://security.debian.org/pool/updates/main/l/linux/linux_4.9.30-2+deb9u3.debian.tar.xz' linux_4.9.30-2+deb9u3.debian.tar.xz 3061100 SHA256:80e070be2e76dbc601de552dad4ece87e5a8d26d61648a2948a94d6e2cc90cef
```

Likely also available for browsing at:

- https://sources.debian.net/src/linux/4.9.30-2+deb9u3/
- https://sources.debian.net/src/linux/4.9.30-2+deb9u3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `lksctp-tools=1.0.17+dfsg-1`

Binary Packages:

- `libsctp-dev=1.0.17+dfsg-1+b1`
- `libsctp1:amd64=1.0.17+dfsg-1+b1`

Licenses: (parsed from: `/usr/share/doc/libsctp-dev/copyright`, `/usr/share/doc/libsctp1/copyright`)

- `BSD-3-clause`
- `GPL-2`
- `GPL-2.0+`
- `LGPL-2.1`
- `LGPL-2.1+`

Source:

```console
$ apt-get source -qq --print-uris lksctp-tools=1.0.17+dfsg-1
'http://deb.debian.org/debian/pool/main/l/lksctp-tools/lksctp-tools_1.0.17+dfsg-1.dsc' lksctp-tools_1.0.17+dfsg-1.dsc 2037 SHA256:61f7e3ee65bd03bc48c68053ea24025d42493e0bed3973c92f321281eddc8bc4
'http://deb.debian.org/debian/pool/main/l/lksctp-tools/lksctp-tools_1.0.17+dfsg.orig.tar.gz' lksctp-tools_1.0.17+dfsg.orig.tar.gz 556428 SHA256:f7c537bc08bf57a8eddf49b232f19920e51b0e4ca55e7d47377ce64546d04e1d
'http://deb.debian.org/debian/pool/main/l/lksctp-tools/lksctp-tools_1.0.17+dfsg-1.debian.tar.xz' lksctp-tools_1.0.17+dfsg-1.debian.tar.xz 9340 SHA256:2b199789d7770f9b795210b17b07e3275d678d9f747cd459153cd91c794a172c
```

Likely also available for browsing at:

- https://sources.debian.net/src/lksctp-tools/1.0.17+dfsg-1/
- https://sources.debian.net/src/lksctp-tools/1.0.17+dfsg-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `log4cxx=0.10.0-12`

Binary Packages:

- `liblog4cxx-dev:amd64=0.10.0-12`
- `liblog4cxx10-dev:amd64=0.10.0-12`
- `liblog4cxx10v5:amd64=0.10.0-12`

Licenses: (parsed from: `/usr/share/doc/liblog4cxx-dev/copyright`, `/usr/share/doc/liblog4cxx10-dev/copyright`, `/usr/share/doc/liblog4cxx10v5/copyright`)

- `Apache-2.0`

Source:

```console
$ apt-get source -qq --print-uris log4cxx=0.10.0-12
'http://deb.debian.org/debian/pool/main/l/log4cxx/log4cxx_0.10.0-12.dsc' log4cxx_0.10.0-12.dsc 2225 SHA256:931fd9662382a2bde906aa58c2f0d6b5195a180a45637f51ee593161aca8bbf3
'http://deb.debian.org/debian/pool/main/l/log4cxx/log4cxx_0.10.0.orig.tar.gz' log4cxx_0.10.0.orig.tar.gz 1667425 SHA256:0de0396220a9566a580166e66b39674cb40efd2176f52ad2c65486c99c920c8c
'http://deb.debian.org/debian/pool/main/l/log4cxx/log4cxx_0.10.0-12.debian.tar.xz' log4cxx_0.10.0-12.debian.tar.xz 14568 SHA256:5579ce0c0827d9aa84af40d594bbd1cfe99ed1e7be6c505139d1bb5f00e0cd71
```

Likely also available for browsing at:

- https://sources.debian.net/src/log4cxx/0.10.0-12/
- https://sources.debian.net/src/log4cxx/0.10.0-12/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `lsb=9.20161125`

Binary Packages:

- `lsb-base=9.20161125`
- `lsb-release=9.20161125`

Licenses: (parsed from: `/usr/share/doc/lsb-base/copyright`, `/usr/share/doc/lsb-release/copyright`)

- `BSD-3-clause`
- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris lsb=9.20161125
'http://deb.debian.org/debian/pool/main/l/lsb/lsb_9.20161125.dsc' lsb_9.20161125.dsc 1697 SHA256:f2dd58084b1beabe966136cfd2e1b355002c1fb1635a6db5ef159b09ed94864f
'http://deb.debian.org/debian/pool/main/l/lsb/lsb_9.20161125.tar.xz' lsb_9.20161125.tar.xz 43096 SHA256:0f9889ff1922da54d1f1538c11a57aa21dc5adf621e6201b18026f6633088bbd
```

Likely also available for browsing at:

- https://sources.debian.net/src/lsb/9.20161125/
- https://sources.debian.net/src/lsb/9.20161125/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `lz4=0.0~r131-2`

Binary Packages:

- `liblz4-1:amd64=0.0~r131-2+b1`
- `liblz4-dev:amd64=0.0~r131-2+b1`

Licenses: (parsed from: `/usr/share/doc/liblz4-1/copyright`, `/usr/share/doc/liblz4-dev/copyright`)

- `BSD-2-clause`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris lz4=0.0~r131-2
'http://deb.debian.org/debian/pool/main/l/lz4/lz4_0.0~r131-2.dsc' lz4_0.0~r131-2.dsc 1973 SHA256:304cf9dddee387377929adf3f2cef0ae19fb2e56b6cc9eab05798845b58bd9b6
'http://deb.debian.org/debian/pool/main/l/lz4/lz4_0.0~r131.orig.tar.gz' lz4_0.0~r131.orig.tar.gz 133784 SHA256:9d4d00614d6b9dec3114b33d1224b6262b99ace24434c53487a0c8fd0b18cfed
'http://deb.debian.org/debian/pool/main/l/lz4/lz4_0.0~r131-2.debian.tar.xz' lz4_0.0~r131-2.debian.tar.xz 4936 SHA256:966df055dd8fa7f292c283452b43a5d2d2047d542fe49e97025006e69525e224
```

Likely also available for browsing at:

- https://sources.debian.net/src/lz4/0.0~r131-2/
- https://sources.debian.net/src/lz4/0.0~r131-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `lzo2=2.08-1.2`

Binary Packages:

- `liblzo2-2:amd64=2.08-1.2+b2`

Licenses: (parsed from: `/usr/share/doc/liblzo2-2/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris lzo2=2.08-1.2
'http://deb.debian.org/debian/pool/main/l/lzo2/lzo2_2.08-1.2.dsc' lzo2_2.08-1.2.dsc 1804 SHA256:09eabe81d6f631a29cc603843b27ab914704726a1400a2219cf83b1da4e72892
'http://deb.debian.org/debian/pool/main/l/lzo2/lzo2_2.08.orig.tar.gz' lzo2_2.08.orig.tar.gz 589045 SHA256:ac1b3e4dee46febe9fd28737eb7f5692d3232ef1a01da10444394c3d47536614
'http://deb.debian.org/debian/pool/main/l/lzo2/lzo2_2.08-1.2.debian.tar.xz' lzo2_2.08-1.2.debian.tar.xz 5996 SHA256:5a9aa3a2432f5d4f689b24c64ea3daec7646e736da37721388ae88b670dd99bc
```

Likely also available for browsing at:

- https://sources.debian.net/src/lzo2/2.08-1.2/
- https://sources.debian.net/src/lzo2/2.08-1.2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `make-dfsg=4.1-9.1`

Binary Packages:

- `make=4.1-9.1`

Licenses: (parsed from: `/usr/share/doc/make/copyright`)

- `GPL-3`
- `GPL-3+`

Source:

```console
$ apt-get source -qq --print-uris make-dfsg=4.1-9.1
'http://deb.debian.org/debian/pool/main/m/make-dfsg/make-dfsg_4.1-9.1.dsc' make-dfsg_4.1-9.1.dsc 2037 SHA256:3527e91633b0d2830a52f3b85229b2f8bdec5e1e5b77bbff95b20317757ab3a3
'http://deb.debian.org/debian/pool/main/m/make-dfsg/make-dfsg_4.1.orig.tar.gz' make-dfsg_4.1.orig.tar.gz 1350231 SHA256:b3ed04fb6718289e4a430afbe2df6ecba9177aad9f6d09aaf38e5409262ca8a3
'http://deb.debian.org/debian/pool/main/m/make-dfsg/make-dfsg_4.1-9.1.diff.gz' make-dfsg_4.1-9.1.diff.gz 45452 SHA256:ec9d39ed253808378aeb91bb2c34bbd177637ed197682e093c3aadfb97b338a3
```

Likely also available for browsing at:

- https://sources.debian.net/src/make-dfsg/4.1-9.1/
- https://sources.debian.net/src/make-dfsg/4.1-9.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `manpages=4.10-2`

Binary Packages:

- `manpages=4.10-2`
- `manpages-dev=4.10-2`

Licenses: (parsed from: `/usr/share/doc/manpages/copyright`, `/usr/share/doc/manpages-dev/copyright`)

- `BSD-3-clause`
- `BSD-4-clause`
- `Expat`
- `GPL-2`
- `GPL-2+`
- `LDPv1`
- `freely-redistributable`
- `henry-spencer-regex`
- `public-domain`
- `verbatim`

Source:

```console
$ apt-get source -qq --print-uris manpages=4.10-2
'http://deb.debian.org/debian/pool/main/m/manpages/manpages_4.10-2.dsc' manpages_4.10-2.dsc 1955 SHA256:2d718e18327c6ed43e3b832c69a6479aaa6e2f57f8d5fefa1fe6a2d80094bd96
'http://deb.debian.org/debian/pool/main/m/manpages/manpages_4.10.orig.tar.xz' manpages_4.10.orig.tar.xz 1556948 SHA256:7395dfc391d545385a998d23df9accb60f2020451c53940eaf8a07b6ea8a63fa
'http://deb.debian.org/debian/pool/main/m/manpages/manpages_4.10-2.debian.tar.xz' manpages_4.10-2.debian.tar.xz 74260 SHA256:3950cf218d1ae15f9ecf910ee676fa1cf0da07265b78c1e76e9432d365d03728
```

Likely also available for browsing at:

- https://sources.debian.net/src/manpages/4.10-2/
- https://sources.debian.net/src/manpages/4.10-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mariadb-10.1=10.1.23-9+deb9u1`

Binary Packages:

- `libmariadbclient-dev=10.1.23-9+deb9u1`
- `libmariadbclient-dev-compat:amd64=10.1.23-9+deb9u1`
- `libmariadbclient18:amd64=10.1.23-9+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libmariadbclient-dev/copyright`, `/usr/share/doc/libmariadbclient-dev-compat/copyright`, `/usr/share/doc/libmariadbclient18/copyright`)

- `Artistic`
- `BSD-2-clause`
- `BSD-3-clause`
- `GPL-2`
- `GPL-2+`
- `GPL-2+-with-bison-exception`
- `GPL-3`
- `GPL-3+`
- `GPL-3+-with-bison-exception`
- `GPL-verbatim`
- `LGPL`
- `LGPL-2`
- `LGPL-2.1`
- `LGPL-2.1+`
- `MIT/X11`
- `SWsoft`
- `public-domain`
- `unlimited-free-doc`
- `zlib/libpng`

Source:

```console
$ apt-get source -qq --print-uris mariadb-10.1=10.1.23-9+deb9u1
'http://deb.debian.org/debian/pool/main/m/mariadb-10.1/mariadb-10.1_10.1.23-9+deb9u1.dsc' mariadb-10.1_10.1.23-9+deb9u1.dsc 4268 SHA256:aa307c141e20facd0d4680870cdd5d8a3a190c576514c60e9460f069a80b42ce
'http://deb.debian.org/debian/pool/main/m/mariadb-10.1/mariadb-10.1_10.1.23.orig.tar.gz' mariadb-10.1_10.1.23.orig.tar.gz 61772244 SHA256:54d8114e24bfa5e3ebdc7d69e071ad1471912847ea481b227d204f9d644300bf
'http://deb.debian.org/debian/pool/main/m/mariadb-10.1/mariadb-10.1_10.1.23-9+deb9u1.debian.tar.xz' mariadb-10.1_10.1.23-9+deb9u1.debian.tar.xz 221684 SHA256:5705aff3ee8acebca298e3d87f30322dae6714f238162eb4e5266b64a43821cb
```

Likely also available for browsing at:

- https://sources.debian.net/src/mariadb-10.1/10.1.23-9+deb9u1/
- https://sources.debian.net/src/mariadb-10.1/10.1.23-9+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mawk=1.3.3-17`

Binary Packages:

- `mawk=1.3.3-17+b3`

Licenses: (parsed from: `/usr/share/doc/mawk/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris mawk=1.3.3-17
'http://deb.debian.org/debian/pool/main/m/mawk/mawk_1.3.3-17.dsc' mawk_1.3.3-17.dsc 1801 SHA256:f98ce6e153e8ac1faf8165bbf77447a4279313f1c18f6bfeec0c5ce35e4b9c03
'http://deb.debian.org/debian/pool/main/m/mawk/mawk_1.3.3.orig.tar.gz' mawk_1.3.3.orig.tar.gz 209942 SHA256:32649c46063d4ef0777a12ae6e9a26bcc920833d54e1abca7edb8d37481e7485
'http://deb.debian.org/debian/pool/main/m/mawk/mawk_1.3.3-17.diff.gz' mawk_1.3.3-17.diff.gz 63506 SHA256:13cb66b6eb5ee654d5626621d5ef476ede6b0bebac18ce765516de810e58490c
```

Likely also available for browsing at:

- https://sources.debian.net/src/mawk/1.3.3-17/
- https://sources.debian.net/src/mawk/1.3.3-17/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mercurial=4.0-1`

Binary Packages:

- `mercurial=4.0-1`
- `mercurial-common=4.0-1`

Licenses: (parsed from: `/usr/share/doc/mercurial/copyright`, `/usr/share/doc/mercurial-common/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris mercurial=4.0-1
'http://deb.debian.org/debian/pool/main/m/mercurial/mercurial_4.0-1.dsc' mercurial_4.0-1.dsc 2364 SHA256:ff0e5c095bc7968180186caae755a7db258d474fc3cec759c2043ca53770db0f
'http://deb.debian.org/debian/pool/main/m/mercurial/mercurial_4.0.orig.tar.gz' mercurial_4.0.orig.tar.gz 4850316 SHA256:24be080745230840f214d93e9f9fb4e25510f9abbbec2e56fab18543fedc43a7
'http://deb.debian.org/debian/pool/main/m/mercurial/mercurial_4.0-1.debian.tar.xz' mercurial_4.0-1.debian.tar.xz 95148 SHA256:2ebf7404aec85e37a751950678b12df1a6fd7c3b7fa405e87673cb4eaabdf2b8
```

Likely also available for browsing at:

- https://sources.debian.net/src/mercurial/4.0-1/
- https://sources.debian.net/src/mercurial/4.0-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mime-support=3.60`

Binary Packages:

- `mime-support=3.60`

Licenses: (parsed from: `/usr/share/doc/mime-support/copyright`)

- `Bellcore`
- `ad-hoc`

Source:

```console
$ apt-get source -qq --print-uris mime-support=3.60
'http://deb.debian.org/debian/pool/main/m/mime-support/mime-support_3.60.dsc' mime-support_3.60.dsc 1605 SHA256:1c3c61f6943b130ee6518facac394b733661975955b84af640b78fa354d7595d
'http://deb.debian.org/debian/pool/main/m/mime-support/mime-support_3.60.tar.gz' mime-support_3.60.tar.gz 36840 SHA256:f31d81f68dc007f56567cc14fb3b2effbd42d1dd087e414508e14e33d1a6a3a4
```

Likely also available for browsing at:

- https://sources.debian.net/src/mime-support/3.60/
- https://sources.debian.net/src/mime-support/3.60/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mpclib3=1.0.3-1`

Binary Packages:

- `libmpc3:amd64=1.0.3-1+b2`

Licenses: (parsed from: `/usr/share/doc/libmpc3/copyright`)

- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris mpclib3=1.0.3-1
'http://deb.debian.org/debian/pool/main/m/mpclib3/mpclib3_1.0.3-1.dsc' mpclib3_1.0.3-1.dsc 1940 SHA256:4b424e1c6063d48fd0d045b5afe37004346dae267ced0994fa8e11ff41cada45
'http://deb.debian.org/debian/pool/main/m/mpclib3/mpclib3_1.0.3.orig.tar.gz' mpclib3_1.0.3.orig.tar.gz 669925 SHA256:617decc6ea09889fb08ede330917a00b16809b8db88c29c31bfbb49cbf88ecc3
'http://deb.debian.org/debian/pool/main/m/mpclib3/mpclib3_1.0.3-1.diff.gz' mpclib3_1.0.3-1.diff.gz 3684 SHA256:5a3fe9a7eddb4428d42e95f5919cce517f17411acdb2a73013a8f1a2bb246565
```

Likely also available for browsing at:

- https://sources.debian.net/src/mpclib3/1.0.3-1/
- https://sources.debian.net/src/mpclib3/1.0.3-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mpdecimal=2.4.2-1`

Binary Packages:

- `libmpdec2:amd64=2.4.2-1`

Licenses: (parsed from: `/usr/share/doc/libmpdec2/copyright`)

- `BSD`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris mpdecimal=2.4.2-1
'http://deb.debian.org/debian/pool/main/m/mpdecimal/mpdecimal_2.4.2-1.dsc' mpdecimal_2.4.2-1.dsc 1893 SHA256:5bc782829357ebc9f0c12084642319e5ac89784a119433f8bfba7a11008d7c13
'http://deb.debian.org/debian/pool/main/m/mpdecimal/mpdecimal_2.4.2.orig.tar.gz' mpdecimal_2.4.2.orig.tar.gz 2271529 SHA256:83c628b90f009470981cf084c5418329c88b19835d8af3691b930afccb7d79c7
'http://deb.debian.org/debian/pool/main/m/mpdecimal/mpdecimal_2.4.2-1.debian.tar.xz' mpdecimal_2.4.2-1.debian.tar.xz 5172 SHA256:b95fb775fd04a7ad34fa5bd2c222b49ee2dfd7f0e15295dbd3f7fb86a9b0194b
```

Likely also available for browsing at:

- https://sources.debian.net/src/mpdecimal/2.4.2-1/
- https://sources.debian.net/src/mpdecimal/2.4.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mpfr4=3.1.5-1`

Binary Packages:

- `libmpfr4:amd64=3.1.5-1`

Licenses: (parsed from: `/usr/share/doc/libmpfr4/copyright`)

- `GFDL-1.2`
- `LGPL-3`

Source:

```console
$ apt-get source -qq --print-uris mpfr4=3.1.5-1
'http://deb.debian.org/debian/pool/main/m/mpfr4/mpfr4_3.1.5-1.dsc' mpfr4_3.1.5-1.dsc 1971 SHA256:40c1a87b1fc06ca9447f7fb1827fc13a0c557af8541f0bccbb3022b029b73582
'http://deb.debian.org/debian/pool/main/m/mpfr4/mpfr4_3.1.5.orig.tar.xz' mpfr4_3.1.5.orig.tar.xz 1126668 SHA256:015fde82b3979fbe5f83501986d328331ba8ddf008c1ff3da3c238f49ca062bc
'http://deb.debian.org/debian/pool/main/m/mpfr4/mpfr4_3.1.5-1.debian.tar.xz' mpfr4_3.1.5-1.debian.tar.xz 9672 SHA256:e5b0d755ec3b3aea15aab137328f7fe65c6b800a1b897bbf50fa4fd478589bd4
```

Likely also available for browsing at:

- https://sources.debian.net/src/mpfr4/3.1.5-1/
- https://sources.debian.net/src/mpfr4/3.1.5-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mpi-defaults=1.8`

Binary Packages:

- `mpi-default-bin=1.8`
- `mpi-default-dev=1.8`

Licenses: (parsed from: `/usr/share/doc/mpi-default-bin/copyright`, `/usr/share/doc/mpi-default-dev/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris mpi-defaults=1.8
'http://deb.debian.org/debian/pool/main/m/mpi-defaults/mpi-defaults_1.8.dsc' mpi-defaults_1.8.dsc 2681 SHA256:2771b8cc1df0b3f2a252509a53c0cdb8aa255d8c1ab0f8c978458f1621594cbf
'http://deb.debian.org/debian/pool/main/m/mpi-defaults/mpi-defaults_1.8.tar.xz' mpi-defaults_1.8.tar.xz 4644 SHA256:d641683346dead2903347302f3182e91b13414c1c5a2b46e409ec8c9ad2f40be
```

Likely also available for browsing at:

- https://sources.debian.net/src/mpi-defaults/1.8/
- https://sources.debian.net/src/mpi-defaults/1.8/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `mysql-defaults=1.0.2`

Binary Packages:

- `default-libmysqlclient-dev:amd64=1.0.2`
- `mysql-common=5.8+1.0.2`

Licenses: (parsed from: `/usr/share/doc/default-libmysqlclient-dev/copyright`, `/usr/share/doc/mysql-common/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris mysql-defaults=1.0.2
'http://deb.debian.org/debian/pool/main/m/mysql-defaults/mysql-defaults_1.0.2.dsc' mysql-defaults_1.0.2.dsc 2171 SHA256:30859f6b6f589644624b04da33ab86f978df2a37ebdf09da63b8076f664ca189
'http://deb.debian.org/debian/pool/main/m/mysql-defaults/mysql-defaults_1.0.2.tar.xz' mysql-defaults_1.0.2.tar.xz 5424 SHA256:cf5597fbb134f99222d61101d0a7115bc3cc63476f6577d840600727a7b4a38c
```

Likely also available for browsing at:

- https://sources.debian.net/src/mysql-defaults/1.0.2/
- https://sources.debian.net/src/mysql-defaults/1.0.2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ncurses=6.0+20161126-1`

Binary Packages:

- `libncurses5:amd64=6.0+20161126-1`
- `libncursesw5:amd64=6.0+20161126-1`
- `libtinfo5:amd64=6.0+20161126-1`
- `ncurses-base=6.0+20161126-1`
- `ncurses-bin=6.0+20161126-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris ncurses=6.0+20161126-1
'http://deb.debian.org/debian/pool/main/n/ncurses/ncurses_6.0+20161126-1.dsc' ncurses_6.0+20161126-1.dsc 3781 SHA256:362e1e63f99b83d3ef10946bc3caf5618066dc361a79861ee37b2ac12ac77201
'http://deb.debian.org/debian/pool/main/n/ncurses/ncurses_6.0+20161126.orig.tar.gz' ncurses_6.0+20161126.orig.tar.gz 3192242 SHA256:e4b9cf1cfcf5a2db7df1d36402967783ba759246c8ff5a17a85ffd7e79296ec0
'http://deb.debian.org/debian/pool/main/n/ncurses/ncurses_6.0+20161126-1.debian.tar.xz' ncurses_6.0+20161126-1.debian.tar.xz 52608 SHA256:262970bf8159e962f204fa12ce18d59ea631b3d33c43335912f4f2fe85d73003
```

Likely also available for browsing at:

- https://sources.debian.net/src/ncurses/6.0+20161126-1/
- https://sources.debian.net/src/ncurses/6.0+20161126-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `netbase=5.4`

Binary Packages:

- `netbase=5.4`

Licenses: (parsed from: `/usr/share/doc/netbase/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris netbase=5.4
'http://deb.debian.org/debian/pool/main/n/netbase/netbase_5.4.dsc' netbase_5.4.dsc 1326 SHA256:ebe29d45e65b661d64636cbce3840997d8079cf338efbfa347b4c73ed2831b7b
'http://deb.debian.org/debian/pool/main/n/netbase/netbase_5.4.tar.xz' netbase_5.4.tar.xz 31524 SHA256:66ff73d2d162e2d49db43988d8b8cd328cf7fffca042db73397f14c71825e80d
```

Likely also available for browsing at:

- https://sources.debian.net/src/netbase/5.4/
- https://sources.debian.net/src/netbase/5.4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `netifaces=0.10.4-0.1`

Binary Packages:

- `python-netifaces=0.10.4-0.1+b2`

Licenses: (parsed from: `/usr/share/doc/python-netifaces/copyright`)

- `MIT-style`

Source:

```console
$ apt-get source -qq --print-uris netifaces=0.10.4-0.1
'http://deb.debian.org/debian/pool/main/n/netifaces/netifaces_0.10.4-0.1.dsc' netifaces_0.10.4-0.1.dsc 2342 SHA256:14d11e07214c848142b0f59fca0485acddedcf43fbeb61c1a92cb36741396240
'http://deb.debian.org/debian/pool/main/n/netifaces/netifaces_0.10.4.orig.tar.gz' netifaces_0.10.4.orig.tar.gz 22969 SHA256:9656a169cb83da34d732b0eb72b39373d48774aee009a3d1272b7ea2ce109cde
'http://deb.debian.org/debian/pool/main/n/netifaces/netifaces_0.10.4-0.1.debian.tar.xz' netifaces_0.10.4-0.1.debian.tar.xz 8216 SHA256:f46a109b1ed8e812e5491ba87ffd350a6b9545a5497bac17d66125361d5ddea0
```

Likely also available for browsing at:

- https://sources.debian.net/src/netifaces/0.10.4-0.1/
- https://sources.debian.net/src/netifaces/0.10.4-0.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `nettle=3.3-1`

Binary Packages:

- `libhogweed4:amd64=3.3-1+b1`
- `libnettle6:amd64=3.3-1+b1`

Licenses: (parsed from: `/usr/share/doc/libhogweed4/copyright`, `/usr/share/doc/libnettle6/copyright`)

- `GAP`
- `GPL`
- `GPL-2`
- `GPL-2+`
- `GPL-2+ with Autoconf exception`
- `LGPL`
- `LGPL-2`
- `LGPL-2+`
- `LGPL-2.1+`
- `other`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris nettle=3.3-1
'http://deb.debian.org/debian/pool/main/n/nettle/nettle_3.3-1.dsc' nettle_3.3-1.dsc 2043 SHA256:3336bc6e8e5b1acad66afa97a05f934e4d758c614fd468d5650b5a38049f1161
'http://deb.debian.org/debian/pool/main/n/nettle/nettle_3.3.orig.tar.gz' nettle_3.3.orig.tar.gz 1887927 SHA256:46942627d5d0ca11720fec18d81fc38f7ef837ea4197c1f630e71ce0d470b11e
'http://deb.debian.org/debian/pool/main/n/nettle/nettle_3.3-1.debian.tar.xz' nettle_3.3-1.debian.tar.xz 19428 SHA256:42fef549318af6cfdf76336eb348501d09454a1d873a84f66440b9a791a0ff1b
```

Likely also available for browsing at:

- https://sources.debian.net/src/nettle/3.3-1/
- https://sources.debian.net/src/nettle/3.3-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `nghttp2=1.18.1-1`

Binary Packages:

- `libnghttp2-14:amd64=1.18.1-1`

Licenses: (parsed from: `/usr/share/doc/libnghttp2-14/copyright`)

- `BSD-2-clause`
- `Expat`
- `GPL-3`
- `GPL-3+ with autoconf exception`
- `MIT`
- `SIL-OFL-1.1`
- `all-permissive`

Source:

```console
$ apt-get source -qq --print-uris nghttp2=1.18.1-1
'http://deb.debian.org/debian/pool/main/n/nghttp2/nghttp2_1.18.1-1.dsc' nghttp2_1.18.1-1.dsc 2283 SHA256:a473983d2630c5f9df6b1ef439e4eee9fbb4fbe9b61bc1b80289b1ba0a84336d
'http://deb.debian.org/debian/pool/main/n/nghttp2/nghttp2_1.18.1.orig.tar.bz2' nghttp2_1.18.1.orig.tar.bz2 1780766 SHA256:5d8bb930eb90c552ec836c7b1862406b69cafcda5520bf266c8f5d914d9b447c
'http://deb.debian.org/debian/pool/main/n/nghttp2/nghttp2_1.18.1-1.debian.tar.xz' nghttp2_1.18.1-1.debian.tar.xz 11716 SHA256:ffcd8e21b6824b6907466f4d3c481f4a68601f8b0b09545e19c033d14a0d16d5
```

Likely also available for browsing at:

- https://sources.debian.net/src/nghttp2/1.18.1-1/
- https://sources.debian.net/src/nghttp2/1.18.1-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `nose=1.3.7-2`

Binary Packages:

- `python-nose=1.3.7-2`

Licenses: (parsed from: `/usr/share/doc/python-nose/copyright`)

- `Expat`
- `LGPL`
- `LGPL-2`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris nose=1.3.7-2
'http://deb.debian.org/debian/pool/main/n/nose/nose_1.3.7-2.dsc' nose_1.3.7-2.dsc 2321 SHA256:fdf5a4d778fd1881ab520807b6a5fb08364bcfcad96c6877a9f900f0b08814f1
'http://deb.debian.org/debian/pool/main/n/nose/nose_1.3.7.orig.tar.gz' nose_1.3.7.orig.tar.gz 280488 SHA256:f1bffef9cbc82628f6e7d7b40d7e255aefaa1adb6a1b1d26c69a8b79e6208a98
'http://deb.debian.org/debian/pool/main/n/nose/nose_1.3.7-2.debian.tar.xz' nose_1.3.7-2.debian.tar.xz 11840 SHA256:47a6fb71acae705a85ec80cea6bdc21caecb024ad4fa042fdc01c1d3cc85737c
```

Likely also available for browsing at:

- https://sources.debian.net/src/nose/1.3.7-2/
- https://sources.debian.net/src/nose/1.3.7-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `npth=1.3-1`

Binary Packages:

- `libnpth0:amd64=1.3-1`

Licenses: (parsed from: `/usr/share/doc/libnpth0/copyright`)

- `GPL-2`
- `GPL-2+`
- `LGPL-3`
- `LGPL-3+`

Source:

```console
$ apt-get source -qq --print-uris npth=1.3-1
'http://deb.debian.org/debian/pool/main/n/npth/npth_1.3-1.dsc' npth_1.3-1.dsc 1949 SHA256:63e2598a3aebe21ef7969a601906a719e923673e04a4d157b6dde605566079be
'http://deb.debian.org/debian/pool/main/n/npth/npth_1.3.orig.tar.bz2' npth_1.3.orig.tar.bz2 295998 SHA256:bca81940436aed0734eb8d0ff8b179e04cc8c087f5625204419f5f45d736a82a
'http://deb.debian.org/debian/pool/main/n/npth/npth_1.3-1.debian.tar.xz' npth_1.3-1.debian.tar.xz 10324 SHA256:4910e19597aea46841eaffc6df58ecf91d5d059130ecb1442fee9f5f963b229c
```

Likely also available for browsing at:

- https://sources.debian.net/src/npth/1.3-1/
- https://sources.debian.net/src/npth/1.3-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `numactl=2.0.11-2.1`

Binary Packages:

- `libnuma-dev:amd64=2.0.11-2.1`
- `libnuma1:amd64=2.0.11-2.1`

Licenses: (parsed from: `/usr/share/doc/libnuma-dev/copyright`, `/usr/share/doc/libnuma1/copyright`)

- `GPL`
- `LGPL`

Source:

```console
$ apt-get source -qq --print-uris numactl=2.0.11-2.1
'http://deb.debian.org/debian/pool/main/n/numactl/numactl_2.0.11-2.1.dsc' numactl_2.0.11-2.1.dsc 1613 SHA256:3462c9e9a53e1cdbec095092859fdd2448e629a687b6dac511f83708cecbbfe3
'http://deb.debian.org/debian/pool/main/n/numactl/numactl_2.0.11.orig.tar.gz' numactl_2.0.11.orig.tar.gz 408175 SHA256:450c091235f891ee874a8651b179c30f57a1391ca5c4673354740ba65e527861
'http://deb.debian.org/debian/pool/main/n/numactl/numactl_2.0.11-2.1.debian.tar.xz' numactl_2.0.11-2.1.debian.tar.xz 6760 SHA256:1dc86f99e7b2d8d652a2af34b14d66b7a3637316403789a3c10f09b490cf89d8
```

Likely also available for browsing at:

- https://sources.debian.net/src/numactl/2.0.11-2.1/
- https://sources.debian.net/src/numactl/2.0.11-2.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ocl-icd=2.2.11-1`

Binary Packages:

- `ocl-icd-libopencl1:amd64=2.2.11-1`

Licenses: (parsed from: `/usr/share/doc/ocl-icd-libopencl1/copyright`)

- `BSD-2-Clause`

Source:

```console
$ apt-get source -qq --print-uris ocl-icd=2.2.11-1
'http://deb.debian.org/debian/pool/main/o/ocl-icd/ocl-icd_2.2.11-1.dsc' ocl-icd_2.2.11-1.dsc 2105 SHA256:605278590678baadcca07da70bdcd0c172d63d24e4f5127bf61acb86f4def398
'http://deb.debian.org/debian/pool/main/o/ocl-icd/ocl-icd_2.2.11.orig.tar.gz' ocl-icd_2.2.11.orig.tar.gz 455800 SHA256:02fa41da98ae2807e92742196831d320e3fc2f4cb1118d0061d9f51dda867730
'http://deb.debian.org/debian/pool/main/o/ocl-icd/ocl-icd_2.2.11-1.debian.tar.xz' ocl-icd_2.2.11-1.debian.tar.xz 11044 SHA256:5094c0efe515adb27c8547db3cf43a9cfdb9235c97be877678a36bea41de5f77
```

Likely also available for browsing at:

- https://sources.debian.net/src/ocl-icd/2.2.11-1/
- https://sources.debian.net/src/ocl-icd/2.2.11-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `openldap=2.4.44+dfsg-5`

Binary Packages:

- `libldap-2.4-2:amd64=2.4.44+dfsg-5`
- `libldap-common=2.4.44+dfsg-5`
- `libldap2-dev:amd64=2.4.44+dfsg-5`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris openldap=2.4.44+dfsg-5
'http://deb.debian.org/debian/pool/main/o/openldap/openldap_2.4.44+dfsg-5.dsc' openldap_2.4.44+dfsg-5.dsc 2946 SHA256:852cf740c7de619527923f49f2ab095278ebf1fbb0b28df1529ea8e6aa05d99a
'http://deb.debian.org/debian/pool/main/o/openldap/openldap_2.4.44+dfsg.orig.tar.gz' openldap_2.4.44+dfsg.orig.tar.gz 4826590 SHA256:d5187c229bec163c5d97845846e1b87917755f85b04f444c08836384f4bd7ffe
'http://deb.debian.org/debian/pool/main/o/openldap/openldap_2.4.44+dfsg-5.debian.tar.xz' openldap_2.4.44+dfsg-5.debian.tar.xz 163740 SHA256:d7c6de5c192341e43958b9f899fab68198c6592782980c78cd3b15267e20ef34
```

Likely also available for browsing at:

- https://sources.debian.net/src/openldap/2.4.44+dfsg-5/
- https://sources.debian.net/src/openldap/2.4.44+dfsg-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `openmpi=2.0.2-2`

Binary Packages:

- `libopenmpi-dev=2.0.2-2`
- `libopenmpi2:amd64=2.0.2-2`
- `openmpi-bin=2.0.2-2`
- `openmpi-common=2.0.2-2`

Licenses: (parsed from: `/usr/share/doc/libopenmpi-dev/copyright`, `/usr/share/doc/libopenmpi2/copyright`, `/usr/share/doc/openmpi-bin/copyright`, `/usr/share/doc/openmpi-common/copyright`)

- `LGPL-2`

Source:

```console
$ apt-get source -qq --print-uris openmpi=2.0.2-2
'http://deb.debian.org/debian/pool/main/o/openmpi/openmpi_2.0.2-2.dsc' openmpi_2.0.2-2.dsc 2705 SHA256:92aea6318e2cc3f8d628407f71a5de5f96f038d7614d8da68f151f94ecf2bb9c
'http://deb.debian.org/debian/pool/main/o/openmpi/openmpi_2.0.2.orig.tar.xz' openmpi_2.0.2.orig.tar.xz 5425116 SHA256:5c5944b0bf27362f28fcce73fbaa11431ab1a9e65ea15d24398c3c363911659f
'http://deb.debian.org/debian/pool/main/o/openmpi/openmpi_2.0.2-2.debian.tar.xz' openmpi_2.0.2-2.debian.tar.xz 59740 SHA256:80ac5590cc4baff0b0f75c211a47ffa8be75b0c056a791e0abe7d4fb13a66416
```

Likely also available for browsing at:

- https://sources.debian.net/src/openmpi/2.0.2-2/
- https://sources.debian.net/src/openmpi/2.0.2-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `openssl1.0=1.0.2l-2`

Binary Packages:

- `libssl1.0.2:amd64=1.0.2l-2`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris openssl1.0=1.0.2l-2
'http://deb.debian.org/debian/pool/main/o/openssl1.0/openssl1.0_1.0.2l-2.dsc' openssl1.0_1.0.2l-2.dsc 2529 SHA256:51aa8afa8157b209a647f5476e72ba06720c33b8f6e46be79e91a0dc9349efcf
'http://deb.debian.org/debian/pool/main/o/openssl1.0/openssl1.0_1.0.2l.orig.tar.gz' openssl1.0_1.0.2l.orig.tar.gz 5365054 SHA256:ce07195b659e75f4e1db43552860070061f156a98bb37b672b101ba6e3ddf30c
'http://deb.debian.org/debian/pool/main/o/openssl1.0/openssl1.0_1.0.2l.orig.tar.gz.asc' openssl1.0_1.0.2l.orig.tar.gz.asc 455 SHA256:ad459d4de6c30c1889272e38144598847c8ba8e5f0892797543607e8d6d9be5f
'http://deb.debian.org/debian/pool/main/o/openssl1.0/openssl1.0_1.0.2l-2.debian.tar.xz' openssl1.0_1.0.2l-2.debian.tar.xz 75888 SHA256:8e0dc8d55df49bf85cc8a991774fbdf4186886307acc167054355edd7c77ed1e
```

Likely also available for browsing at:

- https://sources.debian.net/src/openssl1.0/1.0.2l-2/
- https://sources.debian.net/src/openssl1.0/1.0.2l-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `openssl=1.1.0f-3`

Binary Packages:

- `libssl-dev:amd64=1.1.0f-3`
- `libssl-doc=1.1.0f-3`
- `libssl1.1:amd64=1.1.0f-3`
- `openssl=1.1.0f-3`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris openssl=1.1.0f-3
'http://deb.debian.org/debian/pool/main/o/openssl/openssl_1.1.0f-3.dsc' openssl_1.1.0f-3.dsc 2583 SHA256:a4d69ed8c10134374d86fee593e85bb5165e6d539ab86294e40532a3ed276642
'http://deb.debian.org/debian/pool/main/o/openssl/openssl_1.1.0f.orig.tar.gz' openssl_1.1.0f.orig.tar.gz 5278176 SHA256:12f746f3f2493b2f39da7ecf63d7ee19c6ac9ec6a4fcd8c229da8a522cb12765
'http://deb.debian.org/debian/pool/main/o/openssl/openssl_1.1.0f.orig.tar.gz.asc' openssl_1.1.0f.orig.tar.gz.asc 455 SHA256:9f2feb0494ebcc1cf152d95a11bc966cb94bc1957d88650285db3966866801b0
'http://deb.debian.org/debian/pool/main/o/openssl/openssl_1.1.0f-3.debian.tar.xz' openssl_1.1.0f-3.debian.tar.xz 54152 SHA256:2b1ca97264b073345375a69ee95e32a9850f0288462bc58e9054dfa769f14806
```

Likely also available for browsing at:

- https://sources.debian.net/src/openssl/1.1.0f-3/
- https://sources.debian.net/src/openssl/1.1.0f-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `p11-kit=0.23.3-2`

Binary Packages:

- `libp11-kit0:amd64=0.23.3-2`

Licenses: (parsed from: `/usr/share/doc/libp11-kit0/copyright`)

- `BSD-3-Clause`
- `ISC`
- `ISC+IBM`
- `permissive-like-automake-output`
- `same-as-rest-of-p11kit`

Source:

```console
$ apt-get source -qq --print-uris p11-kit=0.23.3-2
'http://deb.debian.org/debian/pool/main/p/p11-kit/p11-kit_0.23.3-2.dsc' p11-kit_0.23.3-2.dsc 2452 SHA256:fc8e87147d30de8d33e78adb805530d582655999762129b75097a9824679b0cc
'http://deb.debian.org/debian/pool/main/p/p11-kit/p11-kit_0.23.3.orig.tar.gz' p11-kit_0.23.3.orig.tar.gz 1047441 SHA256:d487f04dba3f9e8256f53034c59c944ca45fd7b8434c095da6a74079644dcd82
'http://deb.debian.org/debian/pool/main/p/p11-kit/p11-kit_0.23.3.orig.tar.gz.asc' p11-kit_0.23.3.orig.tar.gz.asc 543 SHA256:a9268313ad8e6c3dae5f4cf9006d8a773861e567c98786482304b3cc91883647
'http://deb.debian.org/debian/pool/main/p/p11-kit/p11-kit_0.23.3-2.debian.tar.xz' p11-kit_0.23.3-2.debian.tar.xz 19784 SHA256:952f55f8c5e2cdc03c8388b59b0bd77bb53eb8f2c2ca2a686cfc91b52100e257
```

Likely also available for browsing at:

- https://sources.debian.net/src/p11-kit/0.23.3-2/
- https://sources.debian.net/src/p11-kit/0.23.3-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pam=1.1.8-3.6`

Binary Packages:

- `libpam-modules:amd64=1.1.8-3.6`
- `libpam-modules-bin=1.1.8-3.6`
- `libpam-runtime=1.1.8-3.6`
- `libpam0g:amd64=1.1.8-3.6`

Licenses: (parsed from: `/usr/share/doc/libpam-modules/copyright`, `/usr/share/doc/libpam-modules-bin/copyright`, `/usr/share/doc/libpam-runtime/copyright`, `/usr/share/doc/libpam0g/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris pam=1.1.8-3.6
'http://deb.debian.org/debian/pool/main/p/pam/pam_1.1.8-3.6.dsc' pam_1.1.8-3.6.dsc 2572 SHA256:7bd7a3059c6ea5b97f5ce0460cbe20788f21bc59bd31ef5a28d7968f53373f5f
'http://deb.debian.org/debian/pool/main/p/pam/pam_1.1.8.orig.tar.gz' pam_1.1.8.orig.tar.gz 1892765 SHA256:4183409a450708a976eca5af561dbf4f0490141a08e86e4a1e649c7c1b094876
'http://deb.debian.org/debian/pool/main/p/pam/pam_1.1.8-3.6.diff.gz' pam_1.1.8-3.6.diff.gz 139492 SHA256:beba99299941c5648ff412d75ebd3407e4d769f5e5ab1fce6a5f2e58c40341ae
```

Likely also available for browsing at:

- https://sources.debian.net/src/pam/1.1.8-3.6/
- https://sources.debian.net/src/pam/1.1.8-3.6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `paramiko=2.0.0-1`

Binary Packages:

- `python-paramiko=2.0.0-1`

Licenses: (parsed from: `/usr/share/doc/python-paramiko/copyright`)

- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris paramiko=2.0.0-1
'http://deb.debian.org/debian/pool/main/p/paramiko/paramiko_2.0.0-1.dsc' paramiko_2.0.0-1.dsc 2265 SHA256:19338ddf86f63ef5569072693cce98894ee1adfbe60693ae684b28306d41a298
'http://deb.debian.org/debian/pool/main/p/paramiko/paramiko_2.0.0.orig.tar.gz' paramiko_2.0.0.orig.tar.gz 273791 SHA256:acf3866621794d68ce42bd5bcb769b6f9ff7e362cc1064e1b1af4185cdc4ed3b
'http://deb.debian.org/debian/pool/main/p/paramiko/paramiko_2.0.0-1.debian.tar.xz' paramiko_2.0.0-1.debian.tar.xz 5956 SHA256:dc798c025969acb04c0432314a5619419fd33f97e22bdd0582343234a4734576
```

Likely also available for browsing at:

- https://sources.debian.net/src/paramiko/2.0.0-1/
- https://sources.debian.net/src/paramiko/2.0.0-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pcre3=2:8.39-3`

Binary Packages:

- `libpcre16-3:amd64=2:8.39-3`
- `libpcre3:amd64=2:8.39-3`
- `libpcre3-dev:amd64=2:8.39-3`
- `libpcre32-3:amd64=2:8.39-3`
- `libpcrecpp0v5:amd64=2:8.39-3`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris pcre3=2:8.39-3
'http://deb.debian.org/debian/pool/main/p/pcre3/pcre3_8.39-3.dsc' pcre3_8.39-3.dsc 2133 SHA256:3180a023c33b5eb7f0a853bec887be867d00a68da8d119d989909e40c6168fd7
'http://deb.debian.org/debian/pool/main/p/pcre3/pcre3_8.39.orig.tar.bz2' pcre3_8.39.orig.tar.bz2 1560758 SHA256:b858099f82483031ee02092711689e7245586ada49e534a06e678b8ea9549e8b
'http://deb.debian.org/debian/pool/main/p/pcre3/pcre3_8.39-3.debian.tar.gz' pcre3_8.39-3.debian.tar.gz 25025 SHA256:a9f0e1a96b6a017965fe69233e267682c289f2cfeb33b46fb78aedcb8cf2c16a
```

Likely also available for browsing at:

- https://sources.debian.net/src/pcre3/2:8.39-3/
- https://sources.debian.net/src/pcre3/2:8.39-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `perl=5.24.1-3+deb9u1`

Binary Packages:

- `libperl5.24:amd64=5.24.1-3+deb9u1`
- `perl=5.24.1-3+deb9u1`
- `perl-base=5.24.1-3+deb9u1`
- `perl-modules-5.24=5.24.1-3+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libperl5.24/copyright`, `/usr/share/doc/perl/copyright`, `/usr/share/doc/perl-base/copyright`, `/usr/share/doc/perl-modules-5.24/copyright`)

- `Artistic`
- `Artistic,`
- `Artistic-2`
- `BSD-3-clause`
- `BSD-3-clause-GENERIC`
- `BSD-3-clause-with-weird-numbering`
- `BSD-4-clause-POWERDOG`
- `BZIP`
- `CC0-1.0`
- `DONT-CHANGE-THE-GPL`
- `Expat`
- `GPL-1`
- `GPL-1+`
- `GPL-2`
- `GPL-2+`
- `GPL-3+-WITH-BISON-EXCEPTION`
- `HSIEH-BSD`
- `HSIEH-DERIVATIVE`
- `LGPL-2.1`
- `REGCOMP`
- `REGCOMP,`
- `RRA-KEEP-THIS-NOTICE`
- `S2P`
- `SDBM-PUBLIC-DOMAIN`
- `TEXT-TABS`
- `Unicode`
- `ZLIB`

Source:

```console
$ apt-get source -qq --print-uris perl=5.24.1-3+deb9u1
'http://deb.debian.org/debian/pool/main/p/perl/perl_5.24.1-3+deb9u1.dsc' perl_5.24.1-3+deb9u1.dsc 2393 SHA256:543956cb46686a577b7e6a6f3db713b4acb98e254d1f66a159757b7f2bf8ba68
'http://deb.debian.org/debian/pool/main/p/perl/perl_5.24.1.orig.tar.xz' perl_5.24.1.orig.tar.xz 11569284 SHA256:03a77bac4505c270f1890ece75afc7d4b555090b41aa41ea478747e23b2afb3f
'http://deb.debian.org/debian/pool/main/p/perl/perl_5.24.1-3+deb9u1.debian.tar.xz' perl_5.24.1-3+deb9u1.debian.tar.xz 172800 SHA256:928dc211d523b1e058cd2389873f564355c3b9df1ef7efc70f55dff106e5efea
```

Likely also available for browsing at:

- https://sources.debian.net/src/perl/5.24.1-3+deb9u1/
- https://sources.debian.net/src/perl/5.24.1-3+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pinentry=1.0.0-2`

Binary Packages:

- `pinentry-curses=1.0.0-2`

Licenses: (parsed from: `/usr/share/doc/pinentry-curses/copyright`)

- `GPL-2`
- `GPL-2+`
- `LGPL-3`
- `LGPL-3+`
- `X11`

Source:

```console
$ apt-get source -qq --print-uris pinentry=1.0.0-2
'http://deb.debian.org/debian/pool/main/p/pinentry/pinentry_1.0.0-2.dsc' pinentry_1.0.0-2.dsc 2591 SHA256:01349d75a92435037a4f4ad252a42cabe7bef774cb8ac6e8c6e24a4107f06e13
'http://deb.debian.org/debian/pool/main/p/pinentry/pinentry_1.0.0.orig.tar.bz2' pinentry_1.0.0.orig.tar.bz2 436930 SHA256:1672c2edc1feb036075b187c0773787b2afd0544f55025c645a71b4c2f79275a
'http://deb.debian.org/debian/pool/main/p/pinentry/pinentry_1.0.0-2.debian.tar.xz' pinentry_1.0.0-2.debian.tar.xz 16672 SHA256:85e0b03d74a64a08b51f6ffac58a1a07a42499615aa993f367675ef12d0b47fb
```

Likely also available for browsing at:

- https://sources.debian.net/src/pinentry/1.0.0-2/
- https://sources.debian.net/src/pinentry/1.0.0-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pkg-config=0.29-4`

Binary Packages:

- `pkg-config=0.29-4+b1`

Licenses: (parsed from: `/usr/share/doc/pkg-config/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris pkg-config=0.29-4
'http://deb.debian.org/debian/pool/main/p/pkg-config/pkg-config_0.29-4.dsc' pkg-config_0.29-4.dsc 1718 SHA256:6a00ca4f4813c9d531b7f99072e1b6b443a8eea045c97e7d2b9d34f9a960deb5
'http://deb.debian.org/debian/pool/main/p/pkg-config/pkg-config_0.29.orig.tar.gz' pkg-config_0.29.orig.tar.gz 1973875 SHA256:c8507705d2a10c67f385d66ca2aae31e81770cc0734b4191eb8c489e864a006b
'http://deb.debian.org/debian/pool/main/p/pkg-config/pkg-config_0.29-4.diff.gz' pkg-config_0.29-4.diff.gz 7560 SHA256:0c1253e3755942d3bf407d5c6465568e97ee960c8d9829c53cbae8ff26dc3762
```

Likely also available for browsing at:

- https://sources.debian.net/src/pkg-config/0.29-4/
- https://sources.debian.net/src/pkg-config/0.29-4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `poco=1.7.6+dfsg1-5`

Binary Packages:

- `libpoco-dev=1.7.6+dfsg1-5`
- `libpococrypto46=1.7.6+dfsg1-5`
- `libpocodata46=1.7.6+dfsg1-5`
- `libpocodatamysql46=1.7.6+dfsg1-5`
- `libpocodataodbc46=1.7.6+dfsg1-5`
- `libpocodatasqlite46=1.7.6+dfsg1-5`
- `libpocofoundation46=1.7.6+dfsg1-5`
- `libpocomongodb46=1.7.6+dfsg1-5`
- `libpoconet46=1.7.6+dfsg1-5`
- `libpoconetssl46=1.7.6+dfsg1-5`
- `libpocoutil46=1.7.6+dfsg1-5`
- `libpocoxml46=1.7.6+dfsg1-5`
- `libpocozip46=1.7.6+dfsg1-5`

Licenses: (parsed from: `/usr/share/doc/libpoco-dev/copyright`, `/usr/share/doc/libpococrypto46/copyright`, `/usr/share/doc/libpocodata46/copyright`, `/usr/share/doc/libpocodatamysql46/copyright`, `/usr/share/doc/libpocodataodbc46/copyright`, `/usr/share/doc/libpocodatasqlite46/copyright`, `/usr/share/doc/libpocofoundation46/copyright`, `/usr/share/doc/libpocomongodb46/copyright`, `/usr/share/doc/libpoconet46/copyright`, `/usr/share/doc/libpoconetssl46/copyright`, `/usr/share/doc/libpocoutil46/copyright`, `/usr/share/doc/libpocoxml46/copyright`, `/usr/share/doc/libpocozip46/copyright`)

- `BSD-3-clause`
- `BSL-1.0`
- `Expat`
- `MIT`
- `RSA-MD`
- `Zlib`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris poco=1.7.6+dfsg1-5
'http://deb.debian.org/debian/pool/main/p/poco/poco_1.7.6+dfsg1-5.dsc' poco_1.7.6+dfsg1-5.dsc 2874 SHA256:8555a6971bd20fc338ee5ad6d106891ecbbc7c1e5f73b9b9d600934cbd69ed91
'http://deb.debian.org/debian/pool/main/p/poco/poco_1.7.6+dfsg1.orig.tar.bz2' poco_1.7.6+dfsg1.orig.tar.bz2 4249425 SHA256:74ea21d9a937d9f852d5615aa968fcb6208347222fa02dee8b7c623b78b882ab
'http://deb.debian.org/debian/pool/main/p/poco/poco_1.7.6+dfsg1-5.debian.tar.xz' poco_1.7.6+dfsg1-5.debian.tar.xz 14096 SHA256:8c3144b1f52552726f510d56a424ab6f46bee6cfb003b9966bf5d319a8d0f7e2
```

Likely also available for browsing at:

- https://sources.debian.net/src/poco/1.7.6+dfsg1-5/
- https://sources.debian.net/src/poco/1.7.6+dfsg1-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `procps=2:3.3.12-3`

Binary Packages:

- `libprocps6:amd64=2:3.3.12-3`
- `procps=2:3.3.12-3`

Licenses: (parsed from: `/usr/share/doc/libprocps6/copyright`, `/usr/share/doc/procps/copyright`)

- `GPL-2`
- `GPL-2.0+`
- `LGPL-2`
- `LGPL-2.0+`
- `LGPL-2.1`
- `LGPL-2.1+`

Source:

```console
$ apt-get source -qq --print-uris procps=2:3.3.12-3
'http://deb.debian.org/debian/pool/main/p/procps/procps_3.3.12-3.dsc' procps_3.3.12-3.dsc 2118 SHA256:5bff9bf045fb88118e5fe69df1ed1d092c49b258ebae5368222a16900288f12e
'http://deb.debian.org/debian/pool/main/p/procps/procps_3.3.12.orig.tar.xz' procps_3.3.12.orig.tar.xz 840540 SHA256:042fcc93e1850aee4c193c51c03f369293fb64fe47e37b38852be6693d12a3af
'http://deb.debian.org/debian/pool/main/p/procps/procps_3.3.12-3.debian.tar.xz' procps_3.3.12-3.debian.tar.xz 27260 SHA256:5907253fba4f11755b60d7d47ffd8212564d7e2c692dcfffc951e4026c465f9e
```

Likely also available for browsing at:

- https://sources.debian.net/src/procps/2:3.3.12-3/
- https://sources.debian.net/src/procps/2:3.3.12-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `psmisc=22.21-2.1`

Binary Packages:

- `psmisc=22.21-2.1+b2`

Licenses: (parsed from: `/usr/share/doc/psmisc/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris psmisc=22.21-2.1
'http://deb.debian.org/debian/pool/main/p/psmisc/psmisc_22.21-2.1.dsc' psmisc_22.21-2.1.dsc 1348 SHA256:3e1e9615bbaa521b8ef054b26faded392179f1919b62dec901cf820efab65404
'http://deb.debian.org/debian/pool/main/p/psmisc/psmisc_22.21.orig.tar.gz' psmisc_22.21.orig.tar.gz 457702 SHA256:97323cad619210845b696d7d722c383852b2acb5c49b5b0852c4f29c77a8145a
'http://deb.debian.org/debian/pool/main/p/psmisc/psmisc_22.21-2.1.debian.tar.xz' psmisc_22.21-2.1.debian.tar.xz 6824 SHA256:b4d5fd3e3c4f402c265476cf1b7ef1bf360c810ea11e74d333fade6f44b9d761
```

Likely also available for browsing at:

- https://sources.debian.net/src/psmisc/22.21-2.1/
- https://sources.debian.net/src/psmisc/22.21-2.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pyasn1=0.1.9-2`

Binary Packages:

- `python-pyasn1=0.1.9-2`

Licenses: (parsed from: `/usr/share/doc/python-pyasn1/copyright`)

- `BSD-2-clause`
- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris pyasn1=0.1.9-2
'http://deb.debian.org/debian/pool/main/p/pyasn1/pyasn1_0.1.9-2.dsc' pyasn1_0.1.9-2.dsc 2299 SHA256:2136d96b3f94e702b57202589e3dfdc2d470255bb0f7292f41f1966699198247
'http://deb.debian.org/debian/pool/main/p/pyasn1/pyasn1_0.1.9.orig.tar.gz' pyasn1_0.1.9.orig.tar.gz 75947 SHA256:853cacd96d1f701ddd67aa03ecc05f51890135b7262e922710112f12a2ed2a7f
'http://deb.debian.org/debian/pool/main/p/pyasn1/pyasn1_0.1.9-2.debian.tar.xz' pyasn1_0.1.9-2.debian.tar.xz 4356 SHA256:5c23055bff1716fea109b2590a83aafe37a6f6a46f0145b561783d305425c019
```

Likely also available for browsing at:

- https://sources.debian.net/src/pyasn1/0.1.9-2/
- https://sources.debian.net/src/pyasn1/0.1.9-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-catkin-pkg-modules=0.3.6-1`

Binary Packages:

- `python-catkin-pkg-modules=0.3.6-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-catkin-pkg-modules=0.3.6-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg-modules/python-catkin-pkg-modules_0.3.6-1.dsc' python-catkin-pkg-modules_0.3.6-1.dsc 991 SHA256:b3032474ea46ecc0446683cbe81d5d624c4e8df8fc0d3b98efcae20b99e9e7ba
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg-modules/python-catkin-pkg-modules_0.3.6.orig.tar.gz' python-catkin-pkg-modules_0.3.6.orig.tar.gz 44748 SHA256:94b5b3a4ecbe74e9581151a95e62f2ca52b00506bbe2839eb47a94ecada3f180
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg-modules/python-catkin-pkg-modules_0.3.6-1.debian.tar.xz' python-catkin-pkg-modules_0.3.6-1.debian.tar.xz 1128 SHA256:8226837e52c47cc880217c398bc1396fcd396a2953b1c006d18f08eaf50bc494
```

### `dpkg` source package: `python-catkin-pkg=0.3.6-1`

Binary Packages:

- `python-catkin-pkg=0.3.6-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-catkin-pkg=0.3.6-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg/python-catkin-pkg_0.3.6-1.dsc' python-catkin-pkg_0.3.6-1.dsc 920 SHA256:a3e3801d09f5a05636c4cf17ad338bcf2aab843467e260dcc36685c5f4824d56
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg/python-catkin-pkg_0.3.6.orig.tar.gz' python-catkin-pkg_0.3.6.orig.tar.gz 9647 SHA256:10e413312f8fa9535025ffdf54c84173c8d2f19ec60165dcaad670f340e69523
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-catkin-pkg/python-catkin-pkg_0.3.6-1.debian.tar.xz' python-catkin-pkg_0.3.6-1.debian.tar.xz 1116 SHA256:cc6833d7026831cda3978db5d0512e34a3a676f0334dac86a34991865d890332
```

### `dpkg` source package: `python-cffi=1.9.1-2`

Binary Packages:

- `python-cffi-backend=1.9.1-2`

Licenses: (parsed from: `/usr/share/doc/python-cffi-backend/copyright`)

- `Expat`

Source:

```console
$ apt-get source -qq --print-uris python-cffi=1.9.1-2
'http://deb.debian.org/debian/pool/main/p/python-cffi/python-cffi_1.9.1-2.dsc' python-cffi_1.9.1-2.dsc 2576 SHA256:98147f123ed8357da6d5e0bc1d8fc2a46c0fdb447a11501e10175454d559e306
'http://deb.debian.org/debian/pool/main/p/python-cffi/python-cffi_1.9.1.orig.tar.gz' python-cffi_1.9.1.orig.tar.gz 407108 SHA256:563e0bd53fda03c151573217b3a49b3abad8813de9dd0632e10090f6190fdaf8
'http://deb.debian.org/debian/pool/main/p/python-cffi/python-cffi_1.9.1-2.debian.tar.xz' python-cffi_1.9.1-2.debian.tar.xz 6968 SHA256:b1924c3b7f07627673c71f63b869fa4ce84fac4befd8b9289212924749f61945
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-cffi/1.9.1-2/
- https://sources.debian.net/src/python-cffi/1.9.1-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-cryptography=1.7.1-3`

Binary Packages:

- `python-cryptography=1.7.1-3`

Licenses: (parsed from: `/usr/share/doc/python-cryptography/copyright`)

- `Apache`
- `Apache-2.0`
- `Expat`

Source:

```console
$ apt-get source -qq --print-uris python-cryptography=1.7.1-3
'http://deb.debian.org/debian/pool/main/p/python-cryptography/python-cryptography_1.7.1-3.dsc' python-cryptography_1.7.1-3.dsc 3328 SHA256:4a4b8135450a95970dd64a7260eed7897d5e95c332cbff08eae12dc0d1ac8d6c
'http://deb.debian.org/debian/pool/main/p/python-cryptography/python-cryptography_1.7.1.orig.tar.gz' python-cryptography_1.7.1.orig.tar.gz 420673 SHA256:953fef7d40a49a795f4d955c5ce4338abcec5dea822ed0414ed30348303fdb4c
'http://deb.debian.org/debian/pool/main/p/python-cryptography/python-cryptography_1.7.1-3.debian.tar.xz' python-cryptography_1.7.1-3.debian.tar.xz 26192 SHA256:3c269fcbbff4696bad24ba6d6ab03bac3ec8ed7d0fedcb9ffe40706406461485
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-cryptography/1.7.1-3/
- https://sources.debian.net/src/python-cryptography/1.7.1-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-dateutil=2.5.3-2`

Binary Packages:

- `python-dateutil=2.5.3-2`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-dateutil=2.5.3-2
'http://deb.debian.org/debian/pool/main/p/python-dateutil/python-dateutil_2.5.3-2.dsc' python-dateutil_2.5.3-2.dsc 2094 SHA256:1859469340a2c5048fd5c7717177cf97f3dbcb7a8429c3574c259f2b163ce827
'http://deb.debian.org/debian/pool/main/p/python-dateutil/python-dateutil_2.5.3.orig.tar.gz' python-dateutil_2.5.3.orig.tar.gz 236877 SHA256:1408fdb07c6a1fa9997567ce3fcee6a337b39a503d80699e0f213de4aa4b32ed
'http://deb.debian.org/debian/pool/main/p/python-dateutil/python-dateutil_2.5.3-2.debian.tar.xz' python-dateutil_2.5.3-2.debian.tar.xz 13368 SHA256:7d83deb985ca15daf8de8e3fa7ff03dca1f9a190061b3e04d52bbcb9b807ea12
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-dateutil/2.5.3-2/
- https://sources.debian.net/src/python-dateutil/2.5.3-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-defaults=2.7.13-2`

Binary Packages:

- `libpython-dev:amd64=2.7.13-2`
- `libpython-stdlib:amd64=2.7.13-2`
- `python=2.7.13-2`
- `python-dev=2.7.13-2`
- `python-minimal=2.7.13-2`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-defaults=2.7.13-2
'http://deb.debian.org/debian/pool/main/p/python-defaults/python-defaults_2.7.13-2.dsc' python-defaults_2.7.13-2.dsc 2677 SHA256:80d5452cde16052caa5b9c3880ed067c3d4f2e60485a56947531a6650f6e7d94
'http://deb.debian.org/debian/pool/main/p/python-defaults/python-defaults_2.7.13-2.tar.gz' python-defaults_2.7.13-2.tar.gz 273915 SHA256:aa376f54a9b2ca59b6f051ce0b4320d95ef60f114f90d98a90e510c3968b416a
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-defaults/2.7.13-2/
- https://sources.debian.net/src/python-defaults/2.7.13-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-docutils=0.13.1+dfsg-2`

Binary Packages:

- `docutils-common=0.13.1+dfsg-2`
- `python-docutils=0.13.1+dfsg-2`

Licenses: (parsed from: `/usr/share/doc/docutils-common/copyright`, `/usr/share/doc/python-docutils/copyright`)

- `BSD-2-clause`
- `BSD-3-clause`
- `GPL-3`
- `GPL-3+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `Python-2.1.1`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris python-docutils=0.13.1+dfsg-2
'http://deb.debian.org/debian/pool/main/p/python-docutils/python-docutils_0.13.1+dfsg-2.dsc' python-docutils_0.13.1+dfsg-2.dsc 2470 SHA256:5fcddedc8ce319294071da7c666f9d7a3a587674751fdbcecd01e07ce130dda9
'http://deb.debian.org/debian/pool/main/p/python-docutils/python-docutils_0.13.1+dfsg.orig.tar.gz' python-docutils_0.13.1+dfsg.orig.tar.gz 1739290 SHA256:1178fcc0e58b6f90e3fb31e4d8629d84579fbcd948b9ce0a8c0fbf4881737e55
'http://deb.debian.org/debian/pool/main/p/python-docutils/python-docutils_0.13.1+dfsg-2.debian.tar.xz' python-docutils_0.13.1+dfsg-2.debian.tar.xz 32864 SHA256:13e0e167b99b91acf90d7dc894e361fa48ae8a31d9de382643cb6aff7036f925
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-docutils/0.13.1+dfsg-2/
- https://sources.debian.net/src/python-docutils/0.13.1+dfsg-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-idna=2.2-1`

Binary Packages:

- `python-idna=2.2-1`

Licenses: (parsed from: `/usr/share/doc/python-idna/copyright`)

- `BSD-3-clause`
- `PSF-2`
- `Unicode`

Source:

```console
$ apt-get source -qq --print-uris python-idna=2.2-1
'http://deb.debian.org/debian/pool/main/p/python-idna/python-idna_2.2-1.dsc' python-idna_2.2-1.dsc 2056 SHA256:1a026b62076fe53f279a4adc6af2685fe0b7d081732563e7abe041a3eeeab163
'http://deb.debian.org/debian/pool/main/p/python-idna/python-idna_2.2.orig.tar.gz' python-idna_2.2.orig.tar.gz 130203 SHA256:0ac27740937d86850010e035c6a10a564158a5accddf1aa24df89b0309252426
'http://deb.debian.org/debian/pool/main/p/python-idna/python-idna_2.2-1.debian.tar.xz' python-idna_2.2-1.debian.tar.xz 4260 SHA256:f1bfce5ecea38179932255307506fb6823a3ed387ded7bc2c9bf328304990a00
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-idna/2.2-1/
- https://sources.debian.net/src/python-idna/2.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-ipaddress=1.0.17-1`

Binary Packages:

- `python-ipaddress=1.0.17-1`

Licenses: (parsed from: `/usr/share/doc/python-ipaddress/copyright`)

- `Expat`
- `PSF-2`

Source:

```console
$ apt-get source -qq --print-uris python-ipaddress=1.0.17-1
'http://deb.debian.org/debian/pool/main/p/python-ipaddress/python-ipaddress_1.0.17-1.dsc' python-ipaddress_1.0.17-1.dsc 2146 SHA256:c2737119d84971270b25ff6ddcbdd37d33cf364e24d9861beeffb06c164e83e4
'http://deb.debian.org/debian/pool/main/p/python-ipaddress/python-ipaddress_1.0.17.orig.tar.gz' python-ipaddress_1.0.17.orig.tar.gz 32434 SHA256:3a21c5a15f433710aaa26f1ae174b615973a25182006ae7f9c26de151cd51716
'http://deb.debian.org/debian/pool/main/p/python-ipaddress/python-ipaddress_1.0.17-1.debian.tar.xz' python-ipaddress_1.0.17-1.debian.tar.xz 3624 SHA256:0eb6e0b886d4c6cae9274fdd3aacf78dc7efb559bd2fea2612c312095f9a3f0c
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-ipaddress/1.0.17-1/
- https://sources.debian.net/src/python-ipaddress/1.0.17-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-numpy=1:1.12.1-3`

Binary Packages:

- `python-numpy=1:1.12.1-3`

Licenses: (parsed from: `/usr/share/doc/python-numpy/copyright`)

- `PSF`

Source:

```console
$ apt-get source -qq --print-uris python-numpy=1:1.12.1-3
'http://deb.debian.org/debian/pool/main/p/python-numpy/python-numpy_1.12.1-3.dsc' python-numpy_1.12.1-3.dsc 2863 SHA256:8f0b51feb952c574f2075a7dd972680e820739bbe939e4e8f1d962330d1c1a7e
'http://deb.debian.org/debian/pool/main/p/python-numpy/python-numpy_1.12.1.orig.tar.gz' python-numpy_1.12.1.orig.tar.gz 4344068 SHA256:c13f5cab98eb75545b211d738588d297d8219deced16bc61593e4e89098a913f
'http://deb.debian.org/debian/pool/main/p/python-numpy/python-numpy_1.12.1-3.debian.tar.xz' python-numpy_1.12.1-3.debian.tar.xz 141860 SHA256:efa024a6245c01bb11686f11d0142b62b5c352f31ce2007876d1684c02ded898
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-numpy/1:1.12.1-3/
- https://sources.debian.net/src/python-numpy/1:1.12.1-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-roman=2.0.0-2`

Binary Packages:

- `python-roman=2.0.0-2`

Licenses: (parsed from: `/usr/share/doc/python-roman/copyright`)

- `Python-2.1.1`
- `ZPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris python-roman=2.0.0-2
'http://deb.debian.org/debian/pool/main/p/python-roman/python-roman_2.0.0-2.dsc' python-roman_2.0.0-2.dsc 2138 SHA256:d522dccc7e20d45208bd5dcb58fec644142c90223b1e7841282ed1b73bdfbc9b
'http://deb.debian.org/debian/pool/main/p/python-roman/python-roman_2.0.0.orig.tar.gz' python-roman_2.0.0.orig.tar.gz 4968 SHA256:98f2c0fb3cdcfba465d12c85b3b7139fc4cd2177f1325f1bacfe00878c8fa7b9
'http://deb.debian.org/debian/pool/main/p/python-roman/python-roman_2.0.0-2.debian.tar.xz' python-roman_2.0.0-2.debian.tar.xz 8508 SHA256:fdb23384ad4ab4701214c5776bb2b181e794a347d024fc0483e4ebe5055f4362
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-roman/2.0.0-2/
- https://sources.debian.net/src/python-roman/2.0.0-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python-rosdep=0.11.8-1`

Binary Packages:

- `python-rosdep=0.11.8-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rosdep=0.11.8-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdep/python-rosdep_0.11.8-1.dsc' python-rosdep_0.11.8-1.dsc 900 SHA256:38c7010311aeb8ff47db5b6c0078014db2da9fea2d9517aa6d893866081d9a5c
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdep/python-rosdep_0.11.8.orig.tar.gz' python-rosdep_0.11.8.orig.tar.gz 79644 SHA256:2cdf1049382d38056b4586d7056ad40c3e7b8754f6636df8f4572f72355bfaf8
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdep/python-rosdep_0.11.8-1.debian.tar.gz' python-rosdep_0.11.8-1.debian.tar.gz 1061 SHA256:d6d10835344d2d1860781b7da6776c8481b15835e8c9af5dca126441a89aaec3
```

### `dpkg` source package: `python-rosdistro-modules=0.6.2-1`

Binary Packages:

- `python-rosdistro-modules=0.6.2-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rosdistro-modules=0.6.2-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro-modules/python-rosdistro-modules_0.6.2-1.dsc' python-rosdistro-modules_0.6.2-1.dsc 982 SHA256:dfd1c8010000b1e11439dcbe984dda37790a330f62aafd1e6e3a8fc81673881b
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro-modules/python-rosdistro-modules_0.6.2.orig.tar.gz' python-rosdistro-modules_0.6.2.orig.tar.gz 38452 SHA256:8f03af173b72ed54dfbc289acf287ef1b4ccf5a4b734c0dcf6a2701fc457e9a2
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro-modules/python-rosdistro-modules_0.6.2-1.debian.tar.xz' python-rosdistro-modules_0.6.2-1.debian.tar.xz 1104 SHA256:79155c0d96f267281b649c3a6c9a143109c4fb726696d6554e99350fc95a5659
```

### `dpkg` source package: `python-rosdistro=0.6.2-1`

Binary Packages:

- `python-rosdistro=0.6.2-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rosdistro=0.6.2-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro/python-rosdistro_0.6.2-1.dsc' python-rosdistro_0.6.2-1.dsc 911 SHA256:89501eb5d73746ca7f8f4cccffeeaa21fd9f3913383046b00dd41988c27dddf9
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro/python-rosdistro_0.6.2.orig.tar.gz' python-rosdistro_0.6.2.orig.tar.gz 9185 SHA256:d3399b3a2a6306477da9222684217ac5820b691311e5391213278d85a693b86e
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosdistro/python-rosdistro_0.6.2-1.debian.tar.xz' python-rosdistro_0.6.2-1.debian.tar.xz 1088 SHA256:3253c798ed57d86f4561287398c54e9de47554f9f945da1cd3171bb0cd9afb80
```

### `dpkg` source package: `python-rosinstall=0.7.8-1`

Binary Packages:

- `python-rosinstall=0.7.8-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rosinstall=0.7.8-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosinstall/python-rosinstall_0.7.8-1.dsc' python-rosinstall_0.7.8-1.dsc 917 SHA256:19d6b7db1cb3a2a6a34d6a2b86562982e2934f2f5bd0adcd73813f9b2644c906
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosinstall/python-rosinstall_0.7.8.orig.tar.gz' python-rosinstall_0.7.8.orig.tar.gz 26425 SHA256:bc278e72a6c8aef5df8b04c565d54c6e452caad4fc7ead5d8cea1b4db2926ec4
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rosinstall/python-rosinstall_0.7.8-1.debian.tar.gz' python-rosinstall_0.7.8-1.debian.tar.gz 1008 SHA256:218375984f09c4fcfd9febfa9d08af30706a37c83e0c88925e682d84b6d44c7d
```

### `dpkg` source package: `python-rospkg-modules=1.1.2-1`

Binary Packages:

- `python-rospkg-modules=1.1.2-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rospkg-modules=1.1.2-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg-modules/python-rospkg-modules_1.1.2-1.dsc' python-rospkg-modules_1.1.2-1.dsc 949 SHA256:b65ecb24057c244c53a057795019e869cb6927bfdb48b0355f8bf7488a653edd
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg-modules/python-rospkg-modules_1.1.2.orig.tar.gz' python-rospkg-modules_1.1.2.orig.tar.gz 38411 SHA256:eb74477c7fb2f5ef437dcec8f78f69ffab7f39995b3bc008127a1c770691025a
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg-modules/python-rospkg-modules_1.1.2-1.debian.tar.xz' python-rospkg-modules_1.1.2-1.debian.tar.xz 1124 SHA256:5e4dac09b109bf9fe685df9ac818cfd0e93001797d768f6ed0f5bd67951934a1
```

### `dpkg` source package: `python-rospkg=1.1.2-1`

Binary Packages:

- `python-rospkg=1.1.2-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-rospkg=1.1.2-1
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg/python-rospkg_1.1.2-1.dsc' python-rospkg_1.1.2-1.dsc 881 SHA256:0fed71f6ab6698c18e71f90db0b7f47cc866d8b90a5c0e338dfd92c038fed510
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg/python-rospkg_1.1.2.orig.tar.gz' python-rospkg_1.1.2.orig.tar.gz 18035 SHA256:ddd3b217f86b9ca5641a2cc73337f2d6ce52d69f814ada8ed917b575ab022a74
'http://packages.ros.org/ros/ubuntu/pool/main/p/python-rospkg/python-rospkg_1.1.2-1.debian.tar.xz' python-rospkg_1.1.2-1.debian.tar.xz 1096 SHA256:958b749a96af524e5bfac806268be219f9e4b34e3d186970b043ecffcdeacd48
```

### `dpkg` source package: `python-setuptools=33.1.1-1`

Binary Packages:

- `python-pkg-resources=33.1.1-1`
- `python-setuptools=33.1.1-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python-setuptools=33.1.1-1
'http://deb.debian.org/debian/pool/main/p/python-setuptools/python-setuptools_33.1.1-1.dsc' python-setuptools_33.1.1-1.dsc 2394 SHA256:d77e52bb962b18a87acfb0f0f8840f11101d0b1d869b176e58bf8184d97b0ed7
'http://deb.debian.org/debian/pool/main/p/python-setuptools/python-setuptools_33.1.1.orig.tar.xz' python-setuptools_33.1.1.orig.tar.xz 415528 SHA256:aeeac1aa49ab17fb2164c380eae40a11a90a21719325d668fba5bd31d5cf72e6
'http://deb.debian.org/debian/pool/main/p/python-setuptools/python-setuptools_33.1.1-1.debian.tar.xz' python-setuptools_33.1.1-1.debian.tar.xz 14000 SHA256:572403d5d2ab58bce77be68810369baa090457be188fbcd7075522972c1d186a
```

Likely also available for browsing at:

- https://sources.debian.net/src/python-setuptools/33.1.1-1/
- https://sources.debian.net/src/python-setuptools/33.1.1-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python2.7=2.7.13-2`

Binary Packages:

- `libpython2.7:amd64=2.7.13-2`
- `libpython2.7-dev:amd64=2.7.13-2`
- `libpython2.7-minimal:amd64=2.7.13-2`
- `libpython2.7-stdlib:amd64=2.7.13-2`
- `python2.7=2.7.13-2`
- `python2.7-dev=2.7.13-2`
- `python2.7-minimal=2.7.13-2`

Licenses: (parsed from: `/usr/share/doc/libpython2.7/copyright`, `/usr/share/doc/libpython2.7-dev/copyright`, `/usr/share/doc/libpython2.7-minimal/copyright`, `/usr/share/doc/libpython2.7-stdlib/copyright`, `/usr/share/doc/python2.7/copyright`, `/usr/share/doc/python2.7-dev/copyright`, `/usr/share/doc/python2.7-minimal/copyright`)

- `# Licensed to PSF under a Contributor Agreement`
- `* Permission to use this software in any way is granted without`
- `Apache`
- `Apache-2`
- `Apache-2.0`
- `Expat`
- `GPL-2`
- `ISC`
- `LGPL-2.1+`
- `PSF-2`
- `Permission is hereby granted, free of charge, to any person obtaining`
- `Python`
- `This software is provided 'as-is', without any express`
- `This software is provided as-is, without express`
- `implied`
- `see above, some license as Python`

Source:

```console
$ apt-get source -qq --print-uris python2.7=2.7.13-2
'http://deb.debian.org/debian/pool/main/p/python2.7/python2.7_2.7.13-2.dsc' python2.7_2.7.13-2.dsc 3367 SHA256:ad16150dbf67feb79f2d7a866afe9f072dabedcebdb5e341f3f28228223d4559
'http://deb.debian.org/debian/pool/main/p/python2.7/python2.7_2.7.13.orig.tar.gz' python2.7_2.7.13.orig.tar.gz 17076672 SHA256:a4f05a0720ce0fd92626f0278b6b433eee9a6173ddf2bced7957dfb599a5ece1
'http://deb.debian.org/debian/pool/main/p/python2.7/python2.7_2.7.13-2.diff.gz' python2.7_2.7.13-2.diff.gz 279975 SHA256:a6afffb70b37e56505dad9f5875c6b6fddb19ddfef61330e567e96228da5009b
```

Likely also available for browsing at:

- https://sources.debian.net/src/python2.7/2.7.13-2/
- https://sources.debian.net/src/python2.7/2.7.13-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python3-defaults=3.5.3-1`

Binary Packages:

- `libpython3-dev:amd64=3.5.3-1`
- `libpython3-stdlib:amd64=3.5.3-1`
- `python3=3.5.3-1`
- `python3-dev=3.5.3-1`
- `python3-minimal=3.5.3-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris python3-defaults=3.5.3-1
'http://deb.debian.org/debian/pool/main/p/python3-defaults/python3-defaults_3.5.3-1.dsc' python3-defaults_3.5.3-1.dsc 2776 SHA256:2bec1dd8a5836d5a19fbbd48d7c49aec40642669036297a34bbfd8b0b2d61439
'http://deb.debian.org/debian/pool/main/p/python3-defaults/python3-defaults_3.5.3-1.tar.gz' python3-defaults_3.5.3-1.tar.gz 1007580 SHA256:aa58a9fceb9975f71be344e594393cf3384dd6b55d9541abf0bee7c5dce8ec15
```

Likely also available for browsing at:

- https://sources.debian.net/src/python3-defaults/3.5.3-1/
- https://sources.debian.net/src/python3-defaults/3.5.3-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `python3.5=3.5.3-1`

Binary Packages:

- `libpython3.5:amd64=3.5.3-1`
- `libpython3.5-dev:amd64=3.5.3-1`
- `libpython3.5-minimal:amd64=3.5.3-1`
- `libpython3.5-stdlib:amd64=3.5.3-1`
- `python3.5=3.5.3-1`
- `python3.5-dev=3.5.3-1`
- `python3.5-minimal=3.5.3-1`

Licenses: (parsed from: `/usr/share/doc/libpython3.5/copyright`, `/usr/share/doc/libpython3.5-dev/copyright`, `/usr/share/doc/libpython3.5-minimal/copyright`, `/usr/share/doc/libpython3.5-stdlib/copyright`, `/usr/share/doc/python3.5/copyright`, `/usr/share/doc/python3.5-dev/copyright`, `/usr/share/doc/python3.5-minimal/copyright`)

- `* Permission to use this software in any way is granted without`
- `Apache`
- `Apache-2`
- `Apache-2.0`
- `By obtaining, using, and/or copying this software and/or its`
- `Expat`
- `GPL-2`
- `ISC`
- `LGPL-2.1+`
- `PSF-2`
- `Permission  is  hereby granted,  free  of charge,  to  any person`
- `Permission is hereby granted, free of charge, to any person obtaining`
- `Permission to use, copy, modify,`
- `Python`
- `Redistribution`
- `This software is provided 'as-is', without any express`
- `This software is provided as-is, without express`
- `binary forms, with`
- `distribute this software`
- `distribute this software and`
- `distribute this software for any`
- `implied`
- `its`
- `see above, some license as Python`
- `use in source`
- `without`

Source:

```console
$ apt-get source -qq --print-uris python3.5=3.5.3-1
'http://deb.debian.org/debian/pool/main/p/python3.5/python3.5_3.5.3-1.dsc' python3.5_3.5.3-1.dsc 3367 SHA256:5259cbb15bb93f7bdfbe9ce03a972ea47f81c86057d5939ef9ce578414b2f1de
'http://deb.debian.org/debian/pool/main/p/python3.5/python3.5_3.5.3.orig.tar.xz' python3.5_3.5.3.orig.tar.xz 15213396 SHA256:eefe2ad6575855423ab630f5b51a8ef6e5556f774584c06beab4926f930ddbb0
'http://deb.debian.org/debian/pool/main/p/python3.5/python3.5_3.5.3-1.debian.tar.xz' python3.5_3.5.3-1.debian.tar.xz 218268 SHA256:fc344383001555ff33b9509879d809e3c3749de32c052d8e24b23b2b2486ff6e
```

Likely also available for browsing at:

- https://sources.debian.net/src/python3.5/3.5.3-1/
- https://sources.debian.net/src/python3.5/3.5.3-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `pyyaml=3.12-1`

Binary Packages:

- `python-yaml=3.12-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris pyyaml=3.12-1
'http://deb.debian.org/debian/pool/main/p/pyyaml/pyyaml_3.12-1.dsc' pyyaml_3.12-1.dsc 2277 SHA256:82e7b6a840d4bd94e03aa3a1fef8ad7f782a0db2b2ae303cb23cfb2dfd6b05ad
'http://deb.debian.org/debian/pool/main/p/pyyaml/pyyaml_3.12.orig.tar.gz' pyyaml_3.12.orig.tar.gz 253011 SHA256:592766c6303207a20efc445587778322d7f73b161bd994f227adaa341ba212ab
'http://deb.debian.org/debian/pool/main/p/pyyaml/pyyaml_3.12-1.debian.tar.xz' pyyaml_3.12-1.debian.tar.xz 7196 SHA256:ef0a10a71dbf629307c6cc9f27fa648c641ff2188134be8ab68dd89bb1b4bf48
```

Likely also available for browsing at:

- https://sources.debian.net/src/pyyaml/3.12-1/
- https://sources.debian.net/src/pyyaml/3.12-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `readline=7.0-3`

Binary Packages:

- `libreadline7:amd64=7.0-3`
- `readline-common=7.0-3`

Licenses: (parsed from: `/usr/share/doc/libreadline7/copyright`, `/usr/share/doc/readline-common/copyright`)

- `GFDL`
- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris readline=7.0-3
'http://deb.debian.org/debian/pool/main/r/readline/readline_7.0-3.dsc' readline_7.0-3.dsc 2538 SHA256:f27a5dc9053b88641e3effc6c03b7840cbbbd887e8dcaf05d9e336c7bc7c6a53
'http://deb.debian.org/debian/pool/main/r/readline/readline_7.0.orig.tar.gz' readline_7.0.orig.tar.gz 2910016 SHA256:750d437185286f40a369e1e4f4764eda932b9459b5ec9a731628393dd3d32334
'http://deb.debian.org/debian/pool/main/r/readline/readline_7.0-3.debian.tar.xz' readline_7.0-3.debian.tar.xz 30012 SHA256:bf166310d6ca7716f2bd0e9e06cee2458b0157f7989d028730fc305643560175
```

Likely also available for browsing at:

- https://sources.debian.net/src/readline/7.0-3/
- https://sources.debian.net/src/readline/7.0-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ros-lunar-actionlib-msgs=1.12.5-0stretch-20170606-222138-0800`

Binary Packages:

- `ros-lunar-actionlib-msgs=1.12.5-0stretch-20170606-222138-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-actionlib=1.11.9-0stretch-20170606-231258-0800`

Binary Packages:

- `ros-lunar-actionlib=1.11.9-0stretch-20170606-231258-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-bond-core=1.7.19-0stretch-20170606-223838-0800`

Binary Packages:

- `ros-lunar-bond-core=1.7.19-0stretch-20170606-223838-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-bond=1.7.19-0stretch-20170606-221854-0800`

Binary Packages:

- `ros-lunar-bond=1.7.19-0stretch-20170606-221854-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-bondcpp=1.7.19-0stretch-20170606-223334-0800`

Binary Packages:

- `ros-lunar-bondcpp=1.7.19-0stretch-20170606-223334-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-bondpy=1.7.19-0stretch-20170606-223437-0800`

Binary Packages:

- `ros-lunar-bondpy=1.7.19-0stretch-20170606-223437-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-catkin=0.7.6-0stretch-20170228-162421-0800`

Binary Packages:

- `ros-lunar-catkin=0.7.6-0stretch-20170228-162421-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-class-loader=0.3.6-0stretch-20170228-181127-0800`

Binary Packages:

- `ros-lunar-class-loader=0.3.6-0stretch-20170228-181127-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-cmake-modules=0.4.1-0stretch-20170228-180845-0800`

Binary Packages:

- `ros-lunar-cmake-modules=0.4.1-0stretch-20170228-180845-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-common-msgs=1.12.5-0stretch-20170606-223348-0800`

Binary Packages:

- `ros-lunar-common-msgs=1.12.5-0stretch-20170606-223348-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-cpp-common=0.6.4-0stretch-20170606-142925-0800`

Binary Packages:

- `ros-lunar-cpp-common=0.6.4-0stretch-20170606-142925-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-diagnostic-msgs=1.12.5-0stretch-20170606-221912-0800`

Binary Packages:

- `ros-lunar-diagnostic-msgs=1.12.5-0stretch-20170606-221912-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-dynamic-reconfigure=1.5.48-0stretch-20170606-230255-0800`

Binary Packages:

- `ros-lunar-dynamic-reconfigure=1.5.48-0stretch-20170606-230255-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-gencpp=0.5.5-0stretch-20170228-181102-0800`

Binary Packages:

- `ros-lunar-gencpp=0.5.5-0stretch-20170228-181102-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-geneus=2.2.6-0stretch-20170523-091827-0800`

Binary Packages:

- `ros-lunar-geneus=2.2.6-0stretch-20170523-091827-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-genlisp=0.4.16-0stretch-20170228-181112-0800`

Binary Packages:

- `ros-lunar-genlisp=0.4.16-0stretch-20170228-181112-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-genmsg=0.5.8-0stretch-20170228-180817-0800`

Binary Packages:

- `ros-lunar-genmsg=0.5.8-0stretch-20170228-180817-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-gennodejs=2.0.1-0stretch-20170228-181117-0800`

Binary Packages:

- `ros-lunar-gennodejs=2.0.1-0stretch-20170228-181117-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-genpy=0.6.5-0stretch-20170309-142000-0800`

Binary Packages:

- `ros-lunar-genpy=0.6.5-0stretch-20170309-142000-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-geometry-msgs=1.12.5-0stretch-20170606-222215-0800`

Binary Packages:

- `ros-lunar-geometry-msgs=1.12.5-0stretch-20170606-222215-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-message-filters=1.13.0-0stretch-20170606-224836-0800`

Binary Packages:

- `ros-lunar-message-filters=1.13.0-0stretch-20170606-224836-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-message-generation=0.4.0-0stretch-20170523-092406-0800`

Binary Packages:

- `ros-lunar-message-generation=0.4.0-0stretch-20170523-092406-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-message-runtime=0.4.12-0stretch-20170606-145537-0800`

Binary Packages:

- `ros-lunar-message-runtime=0.4.12-0stretch-20170606-145537-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-mk=1.14.0-0stretch-20170606-221829-0800`

Binary Packages:

- `ros-lunar-mk=1.14.0-0stretch-20170606-221829-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-nav-msgs=1.12.5-0stretch-20170606-222602-0800`

Binary Packages:

- `ros-lunar-nav-msgs=1.12.5-0stretch-20170606-222602-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-nodelet-core=1.9.10-0stretch-20170606-231235-0800`

Binary Packages:

- `ros-lunar-nodelet-core=1.9.10-0stretch-20170606-231235-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-nodelet-topic-tools=1.9.10-0stretch-20170606-230740-0800`

Binary Packages:

- `ros-lunar-nodelet-topic-tools=1.9.10-0stretch-20170606-230740-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-nodelet=1.9.10-0stretch-20170606-223840-0800`

Binary Packages:

- `ros-lunar-nodelet=1.9.10-0stretch-20170606-223840-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-pluginlib=1.10.5-0stretch-20170606-223354-0800`

Binary Packages:

- `ros-lunar-pluginlib=1.10.5-0stretch-20170606-223354-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-ros-base=1.3.1-0stretch-20170606-233019-0800`

Binary Packages:

- `ros-lunar-ros-base=1.3.1-0stretch-20170606-233019-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-ros-comm=1.13.0-0stretch-20170606-232203-0800`

Binary Packages:

- `ros-lunar-ros-comm=1.13.0-0stretch-20170606-232203-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-ros-core=1.3.1-0stretch-20170606-232652-0800`

Binary Packages:

- `ros-lunar-ros-core=1.3.1-0stretch-20170606-232652-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-ros=1.14.0-0stretch-20170606-221929-0800`

Binary Packages:

- `ros-lunar-ros=1.14.0-0stretch-20170606-221929-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosbag-migration-rule=1.0.0-0stretch-20170228-180545-0800`

Binary Packages:

- `ros-lunar-rosbag-migration-rule=1.0.0-0stretch-20170228-180545-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosbag-storage=1.13.0-0stretch-20170606-145115-0800`

Binary Packages:

- `ros-lunar-rosbag-storage=1.13.0-0stretch-20170606-145115-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosbag=1.13.0-0stretch-20170606-225242-0800`

Binary Packages:

- `ros-lunar-rosbag=1.13.0-0stretch-20170606-225242-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosbash=1.14.0-0stretch-20170228-180947-0800`

Binary Packages:

- `ros-lunar-rosbash=1.14.0-0stretch-20170228-180947-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosboost-cfg=1.14.0-0stretch-20170228-180550-0800`

Binary Packages:

- `ros-lunar-rosboost-cfg=1.14.0-0stretch-20170228-180550-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosbuild=1.14.0-0stretch-20170606-220537-0800`

Binary Packages:

- `ros-lunar-rosbuild=1.14.0-0stretch-20170606-220537-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosclean=1.14.0-0stretch-20170228-180556-0800`

Binary Packages:

- `ros-lunar-rosclean=1.14.0-0stretch-20170228-180556-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosconsole-bridge=0.4.4-0stretch-20170606-223317-0800`

Binary Packages:

- `ros-lunar-rosconsole-bridge=0.4.4-0stretch-20170606-223317-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosconsole=1.13.0-0stretch-20170606-221827-0800`

Binary Packages:

- `ros-lunar-rosconsole=1.13.0-0stretch-20170606-221827-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roscpp-core=0.6.4-0stretch-20170606-145624-0800`

Binary Packages:

- `ros-lunar-roscpp-core=0.6.4-0stretch-20170606-145624-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roscpp-serialization=0.6.4-0stretch-20170606-144440-0800`

Binary Packages:

- `ros-lunar-roscpp-serialization=0.6.4-0stretch-20170606-144440-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roscpp-traits=0.6.4-0stretch-20170606-144009-0800`

Binary Packages:

- `ros-lunar-roscpp-traits=0.6.4-0stretch-20170606-144009-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roscpp=1.13.0-0stretch-20170606-222357-0800`

Binary Packages:

- `ros-lunar-roscpp=1.13.0-0stretch-20170606-222357-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roscreate=1.14.0-0stretch-20170228-180600-0800`

Binary Packages:

- `ros-lunar-roscreate=1.14.0-0stretch-20170228-180600-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosgraph-msgs=1.11.2-0stretch-20170606-222001-0800`

Binary Packages:

- `ros-lunar-rosgraph-msgs=1.11.2-0stretch-20170606-222001-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosgraph=1.13.0-0stretch-20170228-180821-0800`

Binary Packages:

- `ros-lunar-rosgraph=1.13.0-0stretch-20170228-180821-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roslang=1.14.0-0stretch-20170228-181123-0800`

Binary Packages:

- `ros-lunar-roslang=1.14.0-0stretch-20170228-181123-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roslaunch=1.13.0-0stretch-20170606-224058-0800`

Binary Packages:

- `ros-lunar-roslaunch=1.13.0-0stretch-20170606-224058-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roslib=1.14.0-0stretch-20170228-181527-0800`

Binary Packages:

- `ros-lunar-roslib=1.14.0-0stretch-20170228-181527-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roslisp=1.9.20-0stretch-20170606-222714-0800`

Binary Packages:

- `ros-lunar-roslisp=1.9.20-0stretch-20170606-222714-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roslz4=1.13.0-0stretch-20170228-182013-0800`

Binary Packages:

- `ros-lunar-roslz4=1.13.0-0stretch-20170228-182013-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosmake=1.14.0-0stretch-20170228-180845-0800`

Binary Packages:

- `ros-lunar-rosmake=1.14.0-0stretch-20170228-180845-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosmaster=1.13.0-0stretch-20170228-181134-0800`

Binary Packages:

- `ros-lunar-rosmaster=1.13.0-0stretch-20170228-181134-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosmsg=1.13.0-0stretch-20170606-225750-0800`

Binary Packages:

- `ros-lunar-rosmsg=1.13.0-0stretch-20170606-225750-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosnode=1.13.0-0stretch-20170606-230843-0800`

Binary Packages:

- `ros-lunar-rosnode=1.13.0-0stretch-20170606-230843-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosout=1.13.0-0stretch-20170606-223739-0800`

Binary Packages:

- `ros-lunar-rosout=1.13.0-0stretch-20170606-223739-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rospack=2.4.1-0stretch-20170228-181227-0800`

Binary Packages:

- `ros-lunar-rospack=2.4.1-0stretch-20170228-181227-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosparam=1.13.0-0stretch-20170228-181227-0800`

Binary Packages:

- `ros-lunar-rosparam=1.13.0-0stretch-20170228-181227-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rospy=1.13.0-0stretch-20170606-223209-0800`

Binary Packages:

- `ros-lunar-rospy=1.13.0-0stretch-20170606-223209-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosservice=1.13.0-0stretch-20170606-230151-0800`

Binary Packages:

- `ros-lunar-rosservice=1.13.0-0stretch-20170606-230151-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rostest=1.13.0-0stretch-20170606-224423-0800`

Binary Packages:

- `ros-lunar-rostest=1.13.0-0stretch-20170606-224423-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rostime=0.6.4-0stretch-20170606-143520-0800`

Binary Packages:

- `ros-lunar-rostime=0.6.4-0stretch-20170606-143520-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rostopic=1.13.0-0stretch-20170606-230148-0800`

Binary Packages:

- `ros-lunar-rostopic=1.13.0-0stretch-20170606-230148-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-rosunit=1.14.0-0stretch-20170228-181911-0800`

Binary Packages:

- `ros-lunar-rosunit=1.14.0-0stretch-20170228-181911-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-roswtf=1.13.0-0stretch-20170606-231424-0800`

Binary Packages:

- `ros-lunar-roswtf=1.13.0-0stretch-20170606-231424-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-sensor-msgs=1.12.5-0stretch-20170606-222637-0800`

Binary Packages:

- `ros-lunar-sensor-msgs=1.12.5-0stretch-20170606-222637-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-shape-msgs=1.12.5-0stretch-20170606-222628-0800`

Binary Packages:

- `ros-lunar-shape-msgs=1.12.5-0stretch-20170606-222628-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-smclib=1.7.19-0stretch-20170327-152124-0700`

Binary Packages:

- `ros-lunar-smclib=1.7.19-0stretch-20170327-152124-0700`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-std-msgs=0.5.11-0stretch-20170606-220532-0800`

Binary Packages:

- `ros-lunar-std-msgs=0.5.11-0stretch-20170606-220532-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-std-srvs=1.11.2-0stretch-20170606-220626-0800`

Binary Packages:

- `ros-lunar-std-srvs=1.11.2-0stretch-20170606-220626-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-stereo-msgs=1.12.5-0stretch-20170606-223029-0800`

Binary Packages:

- `ros-lunar-stereo-msgs=1.12.5-0stretch-20170606-223029-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-topic-tools=1.13.0-0stretch-20170606-224752-0800`

Binary Packages:

- `ros-lunar-topic-tools=1.13.0-0stretch-20170606-224752-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-trajectory-msgs=1.12.5-0stretch-20170606-222630-0800`

Binary Packages:

- `ros-lunar-trajectory-msgs=1.12.5-0stretch-20170606-222630-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-visualization-msgs=1.12.5-0stretch-20170606-222639-0800`

Binary Packages:

- `ros-lunar-visualization-msgs=1.12.5-0stretch-20170606-222639-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-lunar-xmlrpcpp=1.13.0-0stretch-20170606-144118-0800`

Binary Packages:

- `ros-lunar-xmlrpcpp=1.13.0-0stretch-20170606-144118-0800`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `ros-vcstools=0.1.39-1`

Binary Packages:

- `python-vcstools=0.1.39-1`

Licenses: (parsed from: `/usr/share/doc/python-vcstools/copyright`)

- `BSD-3-clause`

Source:

```console
$ apt-get source -qq --print-uris ros-vcstools=0.1.39-1
'http://deb.debian.org/debian/pool/main/r/ros-vcstools/ros-vcstools_0.1.39-1.dsc' ros-vcstools_0.1.39-1.dsc 2173 SHA256:b3e2e01384592ec87f7c1cdb20ccf9acf87912b60e53d26174c31dae16e5b10a
'http://deb.debian.org/debian/pool/main/r/ros-vcstools/ros-vcstools_0.1.39.orig.tar.gz' ros-vcstools_0.1.39.orig.tar.gz 62839 SHA256:512c4fc540d16294050830b4736c4fe2713189e75407e5207612dafc08703426
'http://deb.debian.org/debian/pool/main/r/ros-vcstools/ros-vcstools_0.1.39-1.debian.tar.xz' ros-vcstools_0.1.39-1.debian.tar.xz 2456 SHA256:ab8f066245b3923d3fe080d615bef35549e6c269596a7406cc7ebc35116ffbb6
```

Likely also available for browsing at:

- https://sources.debian.net/src/ros-vcstools/0.1.39-1/
- https://sources.debian.net/src/ros-vcstools/0.1.39-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ros-wstool=0.1.13-1`

Binary Packages:

- `python-wstool=0.1.13-1`

Licenses: (parsed from: `/usr/share/doc/python-wstool/copyright`)

- `BSD-3-clause`

Source:

```console
$ apt-get source -qq --print-uris ros-wstool=0.1.13-1
'http://deb.debian.org/debian/pool/main/r/ros-wstool/ros-wstool_0.1.13-1.dsc' ros-wstool_0.1.13-1.dsc 2149 SHA256:9f759f1eb66f5615bbf71fbe66ed5ff5386df3296a327ab66aea2071bd3f5d36
'http://deb.debian.org/debian/pool/main/r/ros-wstool/ros-wstool_0.1.13.orig.tar.gz' ros-wstool_0.1.13.orig.tar.gz 75188 SHA256:97db71105728b3bed1828c85becfb1216b95f8b2776d94e280ad1875f2196160
'http://deb.debian.org/debian/pool/main/r/ros-wstool/ros-wstool_0.1.13-1.debian.tar.xz' ros-wstool_0.1.13-1.debian.tar.xz 2960 SHA256:e0ceed0c4cfcb14ca1db8f25c85bc8422e83590315504374f3eb6b30593a102d
```

Likely also available for browsing at:

- https://sources.debian.net/src/ros-wstool/0.1.13-1/
- https://sources.debian.net/src/ros-wstool/0.1.13-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `rtmpdump=2.4+20151223.gitfa8646d.1-1`

Binary Packages:

- `librtmp1:amd64=2.4+20151223.gitfa8646d.1-1+b1`

Licenses: (parsed from: `/usr/share/doc/librtmp1/copyright`)

- `GPL-2`
- `LGPL-2.1`

Source:

```console
$ apt-get source -qq --print-uris rtmpdump=2.4+20151223.gitfa8646d.1-1
'http://deb.debian.org/debian/pool/main/r/rtmpdump/rtmpdump_2.4+20151223.gitfa8646d.1-1.dsc' rtmpdump_2.4+20151223.gitfa8646d.1-1.dsc 2315 SHA256:e56822b88625bf6a51f06652fc36fa2a1348b4325ac76541800cd078192aa3d2
'http://deb.debian.org/debian/pool/main/r/rtmpdump/rtmpdump_2.4+20151223.gitfa8646d.1.orig.tar.gz' rtmpdump_2.4+20151223.gitfa8646d.1.orig.tar.gz 142213 SHA256:5c032f5c8cc2937eb55a81a94effdfed3b0a0304b6376147b86f951e225e3ab5
'http://deb.debian.org/debian/pool/main/r/rtmpdump/rtmpdump_2.4+20151223.gitfa8646d.1-1.debian.tar.xz' rtmpdump_2.4+20151223.gitfa8646d.1-1.debian.tar.xz 8044 SHA256:675847f5cddb860256cbf2e7d5b85918aa53b59b0fd97a466b39a5c77a399537
```

Likely also available for browsing at:

- https://sources.debian.net/src/rtmpdump/2.4+20151223.gitfa8646d.1-1/
- https://sources.debian.net/src/rtmpdump/2.4+20151223.gitfa8646d.1-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `sbcl=2:1.3.14-2`

Binary Packages:

- `sbcl=2:1.3.14-2+b1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris sbcl=2:1.3.14-2
'http://deb.debian.org/debian/pool/main/s/sbcl/sbcl_1.3.14-2.dsc' sbcl_1.3.14-2.dsc 2402 SHA256:424201cb05d8b2d518d6def8702a2d24c33f2625fd19cb0726066c2c5120bde5
'http://deb.debian.org/debian/pool/main/s/sbcl/sbcl_1.3.14.orig.tar.bz2' sbcl_1.3.14.orig.tar.bz2 5784135 SHA256:bf963d58533d839eb76a8028abd17071708d964d5dce07787839cfb6d0d6dcca
'http://deb.debian.org/debian/pool/main/s/sbcl/sbcl_1.3.14-2.debian.tar.xz' sbcl_1.3.14-2.debian.tar.xz 76888 SHA256:2871b57f76dc21d51fe44686ef65cda6a79640eecf30bef10c08123ef5f7e0ce
```

Likely also available for browsing at:

- https://sources.debian.net/src/sbcl/2:1.3.14-2/
- https://sources.debian.net/src/sbcl/2:1.3.14-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `sed=4.4-1`

Binary Packages:

- `sed=4.4-1`

Licenses: (parsed from: `/usr/share/doc/sed/copyright`)

- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris sed=4.4-1
'http://deb.debian.org/debian/pool/main/s/sed/sed_4.4-1.dsc' sed_4.4-1.dsc 2048 SHA256:bb2a11d04f3aeba73cc994e097219fde8c5e0fd1bcf42e0ecc8a4f2282c00fc9
'http://deb.debian.org/debian/pool/main/s/sed/sed_4.4.orig.tar.xz' sed_4.4.orig.tar.xz 1181664 SHA256:cbd6ebc5aaf080ed60d0162d7f6aeae58211a1ee9ba9bb25623daa6cd942683b
'http://deb.debian.org/debian/pool/main/s/sed/sed_4.4-1.debian.tar.xz' sed_4.4-1.debian.tar.xz 59552 SHA256:56dd1f91c5e33b419f38cde93afc90d6fad9064ef4594a877424a0ab2ac9a4bf
```

Likely also available for browsing at:

- https://sources.debian.net/src/sed/4.4-1/
- https://sources.debian.net/src/sed/4.4-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `sensible-utils=0.0.9`

Binary Packages:

- `sensible-utils=0.0.9`

Licenses: (parsed from: `/usr/share/doc/sensible-utils/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris sensible-utils=0.0.9
'http://deb.debian.org/debian/pool/main/s/sensible-utils/sensible-utils_0.0.9.dsc' sensible-utils_0.0.9.dsc 1405 SHA256:390c29b31a09ab7f31f8b5fc0fd82e47c25f15b22b17c614fb87f12d3b091070
'http://deb.debian.org/debian/pool/main/s/sensible-utils/sensible-utils_0.0.9.tar.gz' sensible-utils_0.0.9.tar.gz 74331 SHA256:6fcb5cc0f7f1cf80421840cfa17b1b3fa5afaf3fe852dc984a789023af2f70c6
```

Likely also available for browsing at:

- https://sources.debian.net/src/sensible-utils/0.0.9/
- https://sources.debian.net/src/sensible-utils/0.0.9/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `serf=1.3.9-3`

Binary Packages:

- `libserf-1-1:amd64=1.3.9-3`

Licenses: (parsed from: `/usr/share/doc/libserf-1-1/copyright`)

- `Apache`
- `Apache-2.0`
- `Zlib`

**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `sgml-base=1.29`

Binary Packages:

- `sgml-base=1.29`

Licenses: (parsed from: `/usr/share/doc/sgml-base/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris sgml-base=1.29
'http://deb.debian.org/debian/pool/main/s/sgml-base/sgml-base_1.29.dsc' sgml-base_1.29.dsc 1387 SHA256:5fa519d3de7365d2256c7b9e74b6234a5c81bd115efb6305a53444584c32f8b1
'http://deb.debian.org/debian/pool/main/s/sgml-base/sgml-base_1.29.tar.xz' sgml-base_1.29.tar.xz 12224 SHA256:33808f1d51407ae105d471bf53cab526fe8903b003b78bc7ac4fd1429b7986b4
```

Likely also available for browsing at:

- https://sources.debian.net/src/sgml-base/1.29/
- https://sources.debian.net/src/sgml-base/1.29/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `shadow=1:4.4-4.1`

Binary Packages:

- `login=1:4.4-4.1`
- `passwd=1:4.4-4.1`

Licenses: (parsed from: `/usr/share/doc/login/copyright`, `/usr/share/doc/passwd/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris shadow=1:4.4-4.1
'http://deb.debian.org/debian/pool/main/s/shadow/shadow_4.4-4.1.dsc' shadow_4.4-4.1.dsc 2453 SHA256:6760f8ee90562ed02cb3902b81167e6153923a979c61dc06671426321e575f74
'http://deb.debian.org/debian/pool/main/s/shadow/shadow_4.4.orig.tar.gz' shadow_4.4.orig.tar.gz 3003036 SHA256:1323e7e932836e03dbfa441f7eeb349ede2c92d62b788ade0732411fd516be3d
'http://deb.debian.org/debian/pool/main/s/shadow/shadow_4.4-4.1.debian.tar.xz' shadow_4.4-4.1.debian.tar.xz 600560 SHA256:42610e666c762b88b9e60ea878b522b0639240dc9a74fe627b1ac497dd3d7424
```

Likely also available for browsing at:

- https://sources.debian.net/src/shadow/1:4.4-4.1/
- https://sources.debian.net/src/shadow/1:4.4-4.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `shared-mime-info=1.8-1`

Binary Packages:

- `shared-mime-info=1.8-1`

Licenses: (parsed from: `/usr/share/doc/shared-mime-info/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris shared-mime-info=1.8-1
'http://deb.debian.org/debian/pool/main/s/shared-mime-info/shared-mime-info_1.8-1.dsc' shared-mime-info_1.8-1.dsc 2238 SHA256:53a57dc9cecf61204c57d6df282b5b4db3c82214d585c474dbb33835a25530af
'http://deb.debian.org/debian/pool/main/s/shared-mime-info/shared-mime-info_1.8.orig.tar.xz' shared-mime-info_1.8.orig.tar.xz 589444 SHA256:2af55ef1a0319805b74ab40d331a3962c905477d76c086f49e34dc96363589e9
'http://deb.debian.org/debian/pool/main/s/shared-mime-info/shared-mime-info_1.8-1.debian.tar.xz' shared-mime-info_1.8-1.debian.tar.xz 10324 SHA256:c169b5cb2669f12d2dbdbcb02026c6acbee2bfb6e512feadec50b8593cb2f779
```

Likely also available for browsing at:

- https://sources.debian.net/src/shared-mime-info/1.8-1/
- https://sources.debian.net/src/shared-mime-info/1.8-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `six=1.10.0-3`

Binary Packages:

- `python-six=1.10.0-3`

Licenses: (parsed from: `/usr/share/doc/python-six/copyright`)

- `Expat`

Source:

```console
$ apt-get source -qq --print-uris six=1.10.0-3
'http://deb.debian.org/debian/pool/main/s/six/six_1.10.0-3.dsc' six_1.10.0-3.dsc 2158 SHA256:71f2d5ff8b999c471cc2e92712befe482351a5ae226321e0e795bc683c8729cb
'http://deb.debian.org/debian/pool/main/s/six/six_1.10.0.orig.tar.gz' six_1.10.0.orig.tar.gz 29630 SHA256:105f8d68616f8248e24bf0e9372ef04d3cc10104f1980f54d57b2ce73a5ad56a
'http://deb.debian.org/debian/pool/main/s/six/six_1.10.0-3.debian.tar.xz' six_1.10.0-3.debian.tar.xz 3668 SHA256:860cc57244ea4e69eb4ee3ad1b823472c20d868c1cc25745b236ba6c9e1f3563
```

Likely also available for browsing at:

- https://sources.debian.net/src/six/1.10.0-3/
- https://sources.debian.net/src/six/1.10.0-3/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `sqlite3=3.16.2-5`

Binary Packages:

- `libsqlite3-0:amd64=3.16.2-5`
- `libsqlite3-dev:amd64=3.16.2-5`

Licenses: (parsed from: `/usr/share/doc/libsqlite3-0/copyright`, `/usr/share/doc/libsqlite3-dev/copyright`)

- `GPL-2`
- `GPL-2+`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris sqlite3=3.16.2-5
'http://deb.debian.org/debian/pool/main/s/sqlite3/sqlite3_3.16.2-5.dsc' sqlite3_3.16.2-5.dsc 2510 SHA256:21a2d432ace9ecf50ca5d64580af78d4414a0cfcc8b8a4f15222e11cf105da09
'http://deb.debian.org/debian/pool/main/s/sqlite3/sqlite3_3.16.2.orig-www.tar.xz' sqlite3_3.16.2.orig-www.tar.xz 3383968 SHA256:d5dd3de405c55c63c9f99fbfcf3defc91a54a81b5656c510cd46544aaed134fa
'http://deb.debian.org/debian/pool/main/s/sqlite3/sqlite3_3.16.2.orig.tar.xz' sqlite3_3.16.2.orig.tar.xz 5634120 SHA256:bf7b1e8ea7577253b7f8a8287d111d542d1792cf1768edc66541ac851ff92453
'http://deb.debian.org/debian/pool/main/s/sqlite3/sqlite3_3.16.2-5.debian.tar.xz' sqlite3_3.16.2-5.debian.tar.xz 21688 SHA256:a517fd9e479509cf861d9e916455e0195aebb2ec286c993f74a2cb0de889bd3e
```

Likely also available for browsing at:

- https://sources.debian.net/src/sqlite3/3.16.2-5/
- https://sources.debian.net/src/sqlite3/3.16.2-5/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `subversion=1.9.5-1+deb9u1`

Binary Packages:

- `libsvn1:amd64=1.9.5-1+deb9u1`
- `subversion=1.9.5-1+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libsvn1/copyright`, `/usr/share/doc/subversion/copyright`)

- `Apache-2.0`
- `GPL-2`
- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris subversion=1.9.5-1+deb9u1
'http://security.debian.org/pool/updates/main/s/subversion/subversion_1.9.5-1+deb9u1.dsc' subversion_1.9.5-1+deb9u1.dsc 3077 SHA256:343fda8307ee3d0238303dc5c07fe394000058446bad56d800e5583a62c6b5fd
'http://security.debian.org/pool/updates/main/s/subversion/subversion_1.9.5.orig.tar.gz' subversion_1.9.5.orig.tar.gz 10615674 SHA256:280ba586c5d51d7b976b65d22d5e8e42f3908ed1c968d71120dcf534ce857a83
'http://security.debian.org/pool/updates/main/s/subversion/subversion_1.9.5-1+deb9u1.diff.gz' subversion_1.9.5-1+deb9u1.diff.gz 2535701 SHA256:2bb2797c058e1ca671dcf219c2fb7317ec106078ce496ea00a921c0eb37299a7
```

Likely also available for browsing at:

- https://sources.debian.net/src/subversion/1.9.5-1+deb9u1/
- https://sources.debian.net/src/subversion/1.9.5-1+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `systemd=232-25+deb9u1`

Binary Packages:

- `libsystemd0:amd64=232-25+deb9u1`
- `libudev1:amd64=232-25+deb9u1`

Licenses: (parsed from: `/usr/share/doc/libsystemd0/copyright`, `/usr/share/doc/libudev1/copyright`)

- `CC0`
- `Expat`
- `GPL-2`
- `GPL-2+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris systemd=232-25+deb9u1
'http://deb.debian.org/debian/pool/main/s/systemd/systemd_232-25+deb9u1.dsc' systemd_232-25+deb9u1.dsc 4797 SHA256:624303bdd40a5cc5ffa6c2c1e4557976908a4c8b45d2f59dee1acf0965308823
'http://deb.debian.org/debian/pool/main/s/systemd/systemd_232.orig.tar.gz' systemd_232.orig.tar.gz 4529048 SHA256:1172c7c7d5d72fbded53186e7599d5272231f04cc8b72f9a0fb2c5c20dfc4880
'http://deb.debian.org/debian/pool/main/s/systemd/systemd_232-25+deb9u1.debian.tar.xz' systemd_232-25+deb9u1.debian.tar.xz 205680 SHA256:5b9ef3d5f28dc8e5988eca66c2df022a1e79453f87d1d4a8693c3bf9d6786a14
```

Likely also available for browsing at:

- https://sources.debian.net/src/systemd/232-25+deb9u1/
- https://sources.debian.net/src/systemd/232-25+deb9u1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `sysvinit=2.88dsf-59.9`

Binary Packages:

- `sysvinit-utils=2.88dsf-59.9`

Licenses: (parsed from: `/usr/share/doc/sysvinit-utils/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris sysvinit=2.88dsf-59.9
'http://deb.debian.org/debian/pool/main/s/sysvinit/sysvinit_2.88dsf-59.9.dsc' sysvinit_2.88dsf-59.9.dsc 2123 SHA256:a943edeac16668d3e55583daa4033ad46469e84ffad014e0e2007d9c3167e63d
'http://deb.debian.org/debian/pool/main/s/sysvinit/sysvinit_2.88dsf.orig.tar.gz' sysvinit_2.88dsf.orig.tar.gz 125330 SHA256:b016f937958d2809a020d407e1287bdc09abf1d44efaa96530e2ea57f544f4e8
'http://deb.debian.org/debian/pool/main/s/sysvinit/sysvinit_2.88dsf-59.9.debian.tar.xz' sysvinit_2.88dsf-59.9.debian.tar.xz 132584 SHA256:fbd5c085680d896ec6ee1c5a55ae2d8a5a6b9fd5a7ec1e13010dace24fdbcd5c
```

Likely also available for browsing at:

- https://sources.debian.net/src/sysvinit/2.88dsf-59.9/
- https://sources.debian.net/src/sysvinit/2.88dsf-59.9/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `tar=1.29b-1.1`

Binary Packages:

- `tar=1.29b-1.1`

Licenses: (parsed from: `/usr/share/doc/tar/copyright`)

- `GPL-2`
- `GPL-3`

Source:

```console
$ apt-get source -qq --print-uris tar=1.29b-1.1
'http://deb.debian.org/debian/pool/main/t/tar/tar_1.29b-1.1.dsc' tar_1.29b-1.1.dsc 2057 SHA256:9474ed422017e23e8208785c071b9f7765d73d704b9bb19da22699c6581d73ef
'http://deb.debian.org/debian/pool/main/t/tar/tar_1.29b.orig.tar.xz' tar_1.29b.orig.tar.xz 1822008 SHA256:6a59706ebee384a6cd2fb3ee1dbfbfc20c5c66c7efd7cedb28edc054fca8ba00
'http://deb.debian.org/debian/pool/main/t/tar/tar_1.29b-1.1.debian.tar.xz' tar_1.29b-1.1.debian.tar.xz 28484 SHA256:380f80af0e87446796f05ba384c5d130ea2ad5978b8cfdcf315503966333ebb9
```

Likely also available for browsing at:

- https://sources.debian.net/src/tar/1.29b-1.1/
- https://sources.debian.net/src/tar/1.29b-1.1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `tinyxml2=4.0.1-2`

Binary Packages:

- `libtinyxml2-4:amd64=4.0.1-2`
- `libtinyxml2-dev:amd64=4.0.1-2`

Licenses: (parsed from: `/usr/share/doc/libtinyxml2-4/copyright`, `/usr/share/doc/libtinyxml2-dev/copyright`)

- `GPL-2`
- `GPL-2+`
- `zlib/libpng`

**WARNING:** unable to find source (`apt-get source` failed or returned no results)!


### `dpkg` source package: `tinyxml=2.6.2-4`

Binary Packages:

- `libtinyxml-dev:amd64=2.6.2-4`
- `libtinyxml2.6.2v5:amd64=2.6.2-4`

Licenses: (parsed from: `/usr/share/doc/libtinyxml-dev/copyright`, `/usr/share/doc/libtinyxml2.6.2v5/copyright`)

- `ZLIB`

Source:

```console
$ apt-get source -qq --print-uris tinyxml=2.6.2-4
'http://deb.debian.org/debian/pool/main/t/tinyxml/tinyxml_2.6.2-4.dsc' tinyxml_2.6.2-4.dsc 2037 SHA256:20b92fb0ce6365ba6bd780bf5fe68bdc8c013317203eaa1b955adf72ccdb3d8a
'http://deb.debian.org/debian/pool/main/t/tinyxml/tinyxml_2.6.2.orig.tar.gz' tinyxml_2.6.2.orig.tar.gz 210124 SHA256:15bdfdcec58a7da30adc87ac2b078e4417dbe5392f3afb719f9ba6d062645593
'http://deb.debian.org/debian/pool/main/t/tinyxml/tinyxml_2.6.2-4.debian.tar.xz' tinyxml_2.6.2-4.debian.tar.xz 4344 SHA256:ceb250b862165f89d0fd081d4d3174fe5843ca0573517c9acb765b5af1723002
```

Likely also available for browsing at:

- https://sources.debian.net/src/tinyxml/2.6.2-4/
- https://sources.debian.net/src/tinyxml/2.6.2-4/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `tzdata=2017b-1`

Binary Packages:

- `tzdata=2017b-1`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris tzdata=2017b-1
'http://deb.debian.org/debian/pool/main/t/tzdata/tzdata_2017b-1.dsc' tzdata_2017b-1.dsc 2005 SHA256:ab26ea2d019b6db54abd8ee17c90aeb717641dc8900ab19dca8d5faa4b66d852
'http://deb.debian.org/debian/pool/main/t/tzdata/tzdata_2017b.orig.tar.gz' tzdata_2017b.orig.tar.gz 324317 SHA256:f8242a522ea3496b0ce4ff4f2e75a049178da21001a08b8e666d8cbe07d18086
'http://deb.debian.org/debian/pool/main/t/tzdata/tzdata_2017b-1.debian.tar.xz' tzdata_2017b-1.debian.tar.xz 101168 SHA256:b7ed1f68343a5463aa2efbc527a05b89461e93b5626337d8d581c78e8fdf180c
```

Likely also available for browsing at:

- https://sources.debian.net/src/tzdata/2017b-1/
- https://sources.debian.net/src/tzdata/2017b-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ucf=3.0036`

Binary Packages:

- `ucf=3.0036`

Licenses: (parsed from: `/usr/share/doc/ucf/copyright`)

- `GPL-2`

Source:

```console
$ apt-get source -qq --print-uris ucf=3.0036
'http://deb.debian.org/debian/pool/main/u/ucf/ucf_3.0036.dsc' ucf_3.0036.dsc 1343 SHA256:e67a8a3012ac357c7759dabd93d258422b1003bad8c3f17f25fc2a289eeda3bb
'http://deb.debian.org/debian/pool/main/u/ucf/ucf_3.0036.tar.xz' ucf_3.0036.tar.xz 65020 SHA256:34aa44416106f1205376918386b2896edf21dd42b633133b5f8fedecae17fca8
```

Likely also available for browsing at:

- https://sources.debian.net/src/ucf/3.0036/
- https://sources.debian.net/src/ucf/3.0036/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `unixodbc=2.3.4-1`

Binary Packages:

- `libodbc1:amd64=2.3.4-1`

Licenses: (parsed from: `/usr/share/doc/libodbc1/copyright`)

- `GPL`
- `GPL-2+`
- `LGPL`
- `LGPL-2+`

Source:

```console
$ apt-get source -qq --print-uris unixodbc=2.3.4-1
'http://deb.debian.org/debian/pool/main/u/unixodbc/unixodbc_2.3.4-1.dsc' unixodbc_2.3.4-1.dsc 2126 SHA256:d519915c6fc3a1e8d9e08d7e46294766ed9dc1d5a69644a7a2bdf5e89a227389
'http://deb.debian.org/debian/pool/main/u/unixodbc/unixodbc_2.3.4.orig.tar.gz' unixodbc_2.3.4.orig.tar.gz 1830660 SHA256:2e1509a96bb18d248bf08ead0d74804957304ff7c6f8b2e5965309c632421e39
'http://deb.debian.org/debian/pool/main/u/unixodbc/unixodbc_2.3.4-1.diff.gz' unixodbc_2.3.4-1.diff.gz 18981 SHA256:b623a1c965dfc1d5d584e5c6295791a03549bf492c90c3fe1e02fd5580c81c56
```

Likely also available for browsing at:

- https://sources.debian.net/src/unixodbc/2.3.4-1/
- https://sources.debian.net/src/unixodbc/2.3.4-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `ustr=1.0.4-6`

Binary Packages:

- `libustr-1.0-1:amd64=1.0.4-6`

Licenses: (parsed from: `/usr/share/doc/libustr-1.0-1/copyright`)

- `BSD-2-clause`
- `GPL-2`
- `GPL-2+`
- `LGPL-2+`
- `LGPL-2.1`
- `MIT`

Source:

```console
$ apt-get source -qq --print-uris ustr=1.0.4-6
'http://deb.debian.org/debian/pool/main/u/ustr/ustr_1.0.4-6.dsc' ustr_1.0.4-6.dsc 2029 SHA256:87a854fc03dc059d5d4f135dfd36353c8c09f88a6eb216c6dcea8adadbe6ba59
'http://deb.debian.org/debian/pool/main/u/ustr/ustr_1.0.4.orig.tar.gz' ustr_1.0.4.orig.tar.gz 301345 SHA256:4d293b6b9d9fe51d58441f4b09b1f0005fcad8256ae8048587789bf5dbefb62e
'http://deb.debian.org/debian/pool/main/u/ustr/ustr_1.0.4-6.debian.tar.xz' ustr_1.0.4-6.debian.tar.xz 25608 SHA256:75aa6be2c70eba632ac63078e55ecb4b5a45e6624501a8ed6d81b9a2014d149e
```

Likely also available for browsing at:

- https://sources.debian.net/src/ustr/1.0.4-6/
- https://sources.debian.net/src/ustr/1.0.4-6/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `util-linux=2.29.2-1`

Binary Packages:

- `bsdutils=1:2.29.2-1`
- `libblkid1:amd64=2.29.2-1`
- `libfdisk1:amd64=2.29.2-1`
- `libmount1:amd64=2.29.2-1`
- `libsmartcols1:amd64=2.29.2-1`
- `libuuid1:amd64=2.29.2-1`
- `mount=2.29.2-1`
- `util-linux=2.29.2-1`
- `uuid-dev:amd64=2.29.2-1`

Licenses: (parsed from: `/usr/share/doc/bsdutils/copyright`, `/usr/share/doc/libblkid1/copyright`, `/usr/share/doc/libfdisk1/copyright`, `/usr/share/doc/libmount1/copyright`, `/usr/share/doc/libsmartcols1/copyright`, `/usr/share/doc/libuuid1/copyright`, `/usr/share/doc/mount/copyright`, `/usr/share/doc/util-linux/copyright`, `/usr/share/doc/uuid-dev/copyright`)

- `BSD-2-clause`
- `BSD-3-clause`
- `BSD-4-clause`
- `GPL-2`
- `GPL-2+`
- `GPL-3`
- `GPL-3+`
- `LGPL`
- `LGPL-2`
- `LGPL-2+`
- `LGPL-2.1`
- `LGPL-2.1+`
- `LGPL-3`
- `LGPL-3+`
- `MIT`
- `public-domain`

Source:

```console
$ apt-get source -qq --print-uris util-linux=2.29.2-1
'http://deb.debian.org/debian/pool/main/u/util-linux/util-linux_2.29.2-1.dsc' util-linux_2.29.2-1.dsc 3918 SHA256:a1b5983b4ae58c6478d05f34b120b6a9d51b18dc2287ee9e52de8bf6e43e2bb0
'http://deb.debian.org/debian/pool/main/u/util-linux/util-linux_2.29.2.orig.tar.xz' util-linux_2.29.2.orig.tar.xz 4277668 SHA256:accea4d678209f97f634f40a93b7e9fcad5915d1f4749f6c47bee6bf110fe8e3
'http://deb.debian.org/debian/pool/main/u/util-linux/util-linux_2.29.2-1.debian.tar.xz' util-linux_2.29.2-1.debian.tar.xz 73664 SHA256:820511a8c7c03c7b62218c03f57e4a33e5e928a2cb7d9cda58b9c07aade7744b
```

Likely also available for browsing at:

- https://sources.debian.net/src/util-linux/2.29.2-1/
- https://sources.debian.net/src/util-linux/2.29.2-1/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `xdg-user-dirs=0.15-2`

Binary Packages:

- `xdg-user-dirs=0.15-2+b1`

Licenses: (parsed from: `/usr/share/doc/xdg-user-dirs/copyright`)

- `GPL`

Source:

```console
$ apt-get source -qq --print-uris xdg-user-dirs=0.15-2
'http://deb.debian.org/debian/pool/main/x/xdg-user-dirs/xdg-user-dirs_0.15-2.dsc' xdg-user-dirs_0.15-2.dsc 2160 SHA256:5dccf25ce40d2d843d84ac2c32691d7c52e4841f75c3db8465185f24307286e7
'http://deb.debian.org/debian/pool/main/x/xdg-user-dirs/xdg-user-dirs_0.15.orig.tar.gz' xdg-user-dirs_0.15.orig.tar.gz 243747 SHA256:20b4a751f41d0554bce3e0ce5e8d934be98cc62d48f0b90a894c3e1916552786
'http://deb.debian.org/debian/pool/main/x/xdg-user-dirs/xdg-user-dirs_0.15-2.debian.tar.xz' xdg-user-dirs_0.15-2.debian.tar.xz 3676 SHA256:0f4635d659130670b7b9e443875d3b2b87b70c9970796f3b192ace89719c55dd
```

Likely also available for browsing at:

- https://sources.debian.net/src/xdg-user-dirs/0.15-2/
- https://sources.debian.net/src/xdg-user-dirs/0.15-2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `xml-core=0.17`

Binary Packages:

- `xml-core=0.17`

Licenses: (parsed from: `/usr/share/doc/xml-core/copyright`)

- `GPL-2`
- `GPL-2+`

Source:

```console
$ apt-get source -qq --print-uris xml-core=0.17
'http://deb.debian.org/debian/pool/main/x/xml-core/xml-core_0.17.dsc' xml-core_0.17.dsc 1686 SHA256:f4b953e75740239f4500174a3cb5234916b624d40c55c363b193b5a078b7ef42
'http://deb.debian.org/debian/pool/main/x/xml-core/xml-core_0.17.tar.xz' xml-core_0.17.tar.xz 21180 SHA256:2f21dbefa53aa54373214312edbf1c7f35041d6ac1d295bca50d3da9bd5007c3
```

Likely also available for browsing at:

- https://sources.debian.net/src/xml-core/0.17/
- https://sources.debian.net/src/xml-core/0.17/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `xz-utils=5.2.2-1.2`

Binary Packages:

- `liblzma5:amd64=5.2.2-1.2+b1`
- `xz-utils=5.2.2-1.2+b1`

Licenses: (parsed from: `/usr/share/doc/liblzma5/copyright`, `/usr/share/doc/xz-utils/copyright`)

- `Autoconf`
- `GPL-2`
- `GPL-2+`
- `GPL-3`
- `LGPL-2`
- `LGPL-2.1`
- `LGPL-2.1+`
- `PD`
- `PD-debian`
- `config-h`
- `noderivs`
- `none`
- `permissive-fsf`
- `permissive-nowarranty`
- `probably-PD`

Source:

```console
$ apt-get source -qq --print-uris xz-utils=5.2.2-1.2
'http://deb.debian.org/debian/pool/main/x/xz-utils/xz-utils_5.2.2-1.2.dsc' xz-utils_5.2.2-1.2.dsc 2550 SHA256:13c8d8d0c243af78dc89b6e2cd670c8d8a2522379e1fcd196957c95d988d5961
'http://deb.debian.org/debian/pool/main/x/xz-utils/xz-utils_5.2.2.orig.tar.xz' xz-utils_5.2.2.orig.tar.xz 1016404 SHA256:f341b1906ebcdde291dd619399ae944600edc9193619dd0c0110a5f05bfcc89e
'http://deb.debian.org/debian/pool/main/x/xz-utils/xz-utils_5.2.2.orig.tar.xz.asc' xz-utils_5.2.2.orig.tar.xz.asc 543 SHA256:2cc0575556e1331b3f468e6e7dca5969ce86efcc315d62672279b4e68b2e449f
'http://deb.debian.org/debian/pool/main/x/xz-utils/xz-utils_5.2.2-1.2.debian.tar.xz' xz-utils_5.2.2-1.2.debian.tar.xz 108632 SHA256:231c08d5c2c4e5c8ef5d6d58cac91aaeb2e4fcddc35e1ed3c69d730a2375c948
```

Likely also available for browsing at:

- https://sources.debian.net/src/xz-utils/5.2.2-1.2/
- https://sources.debian.net/src/xz-utils/5.2.2-1.2/debian/copyright (for direct copyright/license information)

### `dpkg` source package: `zlib=1:1.2.8.dfsg-5`

Binary Packages:

- `zlib1g:amd64=1:1.2.8.dfsg-5`
- `zlib1g-dev:amd64=1:1.2.8.dfsg-5`

**WARNING:** unable to detect licenses! (package likely not compliant with DEP-5)
  If source is available (seen below), check the contents of `debian/copyright` within it.


Source:

```console
$ apt-get source -qq --print-uris zlib=1:1.2.8.dfsg-5
'http://deb.debian.org/debian/pool/main/z/zlib/zlib_1.2.8.dfsg-5.dsc' zlib_1.2.8.dfsg-5.dsc 2259 SHA256:35ebfdbb74b3563d344b2bb946909f5d3221cdf971876549ea7ccec01fabcbec
'http://deb.debian.org/debian/pool/main/z/zlib/zlib_1.2.8.dfsg.orig.tar.gz' zlib_1.2.8.dfsg.orig.tar.gz 361943 SHA256:2caecc2c3f1ef8b87b8f72b128a03e61c307e8c14f5ec9b422ef7914ba75cf9f
'http://deb.debian.org/debian/pool/main/z/zlib/zlib_1.2.8.dfsg-5.debian.tar.xz' zlib_1.2.8.dfsg-5.debian.tar.xz 18500 SHA256:7b88f58d1bfe8e873b8362ede3d0bc569793decc60094189fad1a110599cdd95
```

Likely also available for browsing at:

- https://sources.debian.net/src/zlib/1:1.2.8.dfsg-5/
- https://sources.debian.net/src/zlib/1:1.2.8.dfsg-5/debian/copyright (for direct copyright/license information)