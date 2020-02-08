---
layout: page
title: "Download"
description: ""
group:
---
<!--
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->
{% include JB/setup %}

# Download Apache Submarine

The latest release of Apache Submarine is **0.3.0**.

  - Apache Submarine 0.3.0 released on Feb 01, 2020 ([release notes](./releases/submarine-release-0.3.0.html)) ([git tag](https://github.com/apache/submarine/tree/rel/release-0.3.0))

    * Binary package ([Install guide](https://github.com/apache/submarine#quick-start)):
    <p><div class="btn btn-md btn-primary" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/submarine/submarine-0.3.0/submarine-dist-0.3.0-hadoop-2.9.tar.gz'">submarine-dist-0.3.0-hadoop-2.9.tar.gz</div> (550 MB,
    [checksum](https://www.apache.org/dist/submarine/submarine-0.3.0/submarine-dist-0.3.0-hadoop-2.9.tar.gz.sha512),
    [signature](https://www.apache.org/dist/submarine/submarine-0.3.0/submarine-dist-0.3.0-hadoop-2.9.tar.gz.asc))</p>

    * Source:
    <p><div class="btn btn-md btn-primary" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/submarine/submarine-0.3.0/submarine-dist-0.3.0-src.tar.gz'">submarine-dist-0.3.0-src.tar.gz</div> (6 MB,
    [checksum](https://www.apache.org/dist/submarine/submarine-0.3.0/submarine-dist-0.3.0-src.tar.gz.sha512),
    [signature](https://www.apache.org/dist/submarine/submarine-0.3.0/submarine-dist-0.3.0-src.tar.gz.asc))
    <p></p>
    * Docker images:
    <p>*[mini-submarine](https://hub.docker.com/layers/apache/submarine/mini-0.3.0/images/sha256-3dd49054bf8a91521f5743c675278d626a5fa568e91651c67867b8ba6ceba340)* [(guide)](https://github.com/apache/submarine/blob/rel/release-0.3.0/dev-support/mini-submarine/README.md#mini-submarine):</p>
    <code>docker run -it -h submarine-dev --name mini-submarine --net=bridge --privileged -P apache/submarine:mini-0.3.0 /bin/bash</code>

## Verify the integrity of the files

It is essential that you [verify](https://www.apache.org/info/verification.html) the integrity of the downloaded files using the PGP or MD5 signatures. This signature should be matched against the [KEYS](https://www.apache.org/dist/submarine/KEYS) file.

```
gpg --import KEYS
gpg --verify submarine-dist-X.Y.Z-src.tar.gz.asc
```

## Build from source

For developers, to get latest version check [README](https://github.com/apache/submarine/blob/master/docs/development/BuildFromCode.md).


## Old releases

  - Apache Submarine 0.2.0 released on Jul 2, 2019

    * Binary package with submarine:
    <a style="cursor:pointer" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0.tar.gz'">hadoop-submarine-0.2.0.tar.gz</a> (111 MB,
    [checksum](https://dist.apache.org/repos/dist/release/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0.tar.gz.mds),
    [signature](https://dist.apache.org/repos/dist/release/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0.tar.gz.asc),
    [Announcement](http://hadoop.apache.org/submarine/release/0.2.0/))

    * Source:
    <a style="cursor:pointer" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0-src.tar.gz'">hadoop-submarine-0.2.0-src.tar.gz</a> (1.4 MB,
    [checksum](https://dist.apache.org/repos/dist/release/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0-src.tar.gz.mds),
    [signature](https://dist.apache.org/repos/dist/release/hadoop/submarine/submarine-0.2.0/hadoop-submarine-0.2.0-src.tar.gz.asc))


  - Apache Submarine 0.1.0 released on Jan 16, 2019

    * Binary package with submarine:
    <a style="cursor:pointer" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.2.0/hadoop-3.2.0.tar.gz'">submarine-0.2.0-bin-all.tgz</a> (97 MB,
    [checksum](https://www.apache.org/dist/hadoop/common/hadoop-3.2.0/hadoop-3.2.0.tar.gz.mds),
    [signature](https://www.apache.org/dist/hadoop/common/hadoop-3.2.0/hadoop-3.2.0.tar.gz.asc),
    [Announcement](https://hadoop.apache.org/docs/r3.2.0/index.html))

    * Source:
    <a style="cursor:pointer" onclick="window.location.href='https://www.apache.org/dyn/closer.cgi/hadoop/common/hadoop-3.2.0/hadoop-3.2.0-src.tar.gz'">submarine-hadoop-3.2.0-src.tar.gz</a> (1.1 MB,
    [checksum](https://www.apache.org/dist/hadoop/common/hadoop-3.2.0/hadoop-3.2.0-src.tar.gz.mds),
    [signature](https://www.apache.org/dist/hadoop/common/hadoop-3.2.0/hadoop-3.2.0-src.tar.gz.asc))

  <p />