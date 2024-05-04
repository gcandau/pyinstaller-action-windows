# Docker Files

To push new images up to Docker hub

1. `docker login`
2. `docker build -f Dockerfile-py3.11-win64 . --platform=linux/amd64 -t gcandau/pyinstaller-windows:3.11 -t gcandau/pyinstaller-windows:latest && docker push gcandau/pyinstaller-windows:3.11 && docker push gcandau/pyinstaller-windows:latest`