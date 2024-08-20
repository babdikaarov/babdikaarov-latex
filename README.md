# DOC

## it is a raw version of Docker images in docker.hub https://hub.docker.com/repository/docker/babdikaarov/latex/general

## Usage

```bash
docker pull babdikaarov/latex:latest


docker run --rm -v "$(pwd)":/data babdikaarov/latex:latest \
    bash -c "cd /data && pdflatex yourfile.tex && convert -density 300 yourfile.pdf -quality 100 yourfile.jpg"

```
