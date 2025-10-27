# ruby-libvips

Docker image with Ruby 3.4 and libvips preinstalled.

## Docker Image

This repository builds and publishes a Docker image to Docker Hub with Ruby 3.4 and the libvips library preinstalled. This is useful for applications that need image processing capabilities using libvips.

## Usage

Pull the image from Docker Hub:
```bash
docker pull <dockerhub-username>/ruby-libvips:latest
```

Use it in your Dockerfile:
```dockerfile
FROM <dockerhub-username>/ruby-libvips:latest
```

## Setup

To enable automatic publishing to Docker Hub, configure the following secrets in your GitHub repository:
- `DOCKERHUB_USERNAME`: Your Docker Hub username
- `DOCKERHUB_TOKEN`: Your Docker Hub access token

## What's Included

- Ruby 3.4
- libvips 8.16+ (image processing library)