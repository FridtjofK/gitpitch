# GitPitch Desktop Download

!> [Docker Desktop](https://www.docker.com/products/docker-desktop) must already be installed locally in order to download GitPitch Desktop.

### Trial Edition

The trial software is no longer available. GitPitch is shutting down on March 1, 2021.

### Paid Edition


The paid edition of the [Desktop app](/desktop/README.md) is also delivered as a Docker image and available for use on MacOS, Linux, and Windows 10.

The paid image is maintained within a *private* repository on Docker Hub. Access to this image requires explicit authorization. Authorization is granted as part of [paid service activation](https://gitpitch.com/pricing).

Once authorized, to download make sure you first `docker login` and then run the following command in a local shell:

```shell
docker pull gitpitch/4.0
```

Following successful service activation download instructions for the paid edition of the desktop app will also be displayed on your GitPitch account dashboard.

