# ORT-Image
This repo hosts a pre-built image of [OSS Review Toolkit](https://github.com/oss-review-toolkit/ort) (ORT). We use/maintain this image to allow our [ts-scan](https://github.com/trustsource/ts-scan) utility to execute ORT as part of its SCA process. Using ts-scan, the image will be pulled automatically. Please note: The image is about 5 GB, thus dependning on your internet connection this might take a few mins! 
However, you also may pull the plain image from here for your own purposes. To pull, use the following command:
```
docker pull ghcr.io/trustsource/ort:latest
```
The repository holds the Dockerfile we use for building the image. Currently we do not have a regular update-cycle. But we plan to automate it based on ORT-releases.  

# License
ORT comes under *Apache-2.0* License, so we decided to put the Dockerfile under *Apache-2.0* as well.

# Contact
In case of questions feel free to reach out [support(at)trustsource.io](mailto:support@trustsource.io)

# Background
TrustSource is a one-stop-solution to automate Open Source Compliance and Security tasks at scale. It is available as [open source, stand-alone solution](https://github.com/trustsource/ts-ce) or as [managed service](https://app.trustsource.io). To learn more see [https://www.trustsource.io](https://www.trustsource.io)
