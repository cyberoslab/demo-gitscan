# Detect Vulnerabilities in Images
## Detect Vulnerabilities in the image

Build the image `docker build --no-cache -t krol/demo-gitscan:main-fdf2a30 -f Dockerfile .` or `make build`

Run the scanner `gitscan image krol/demo-gitscan:main-fdf2a30` or `make scan-image`

