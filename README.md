# Dockerfiles for base images used in Ample


## Naming

Dockerfiles should be named using the `Dockerfile.[image_name]` format. For
instance, the Dockerfile for ruby-2.6 would be named `Dockerfile.ruby-2.6`


## Usage
To build an image using a specific dockerfile, use the following command:

```
./build_image Dockerfile.ruby-2.6
```

This commands builds an image named `ruby-2.6` with the commit id as its tag.
