hms-jre8
=============

This image is the oracle [jre8][jre8] base. It comes from [hms-base][hms-base].

## Build

```
docker build -t rawmind/hms-jre8:<version> .
```

## Versions

- `1.8.112` [(Dockerfile)](https://github.com/rawmind0/hms-jre8/blob/1.8.112/Dockerfile)


## Usage

To use this image include `FROM rawmind/hms-jre8` at the top of your `Dockerfile`. 

[hms-base]: https://github.com/rawmind0/hms-base/
[jre8]: http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html