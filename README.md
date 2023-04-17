### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sebastian_biernat_resume.tex
```
### License

Format is MIT but all the data is owned by Sebastian Biernat.
