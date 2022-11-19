# Run in RStudio

Use docker to make it reproducible and mount the volume to the root folder of the project

`docker run -d -p 8787:8787 -p 4321:4321 -v /fpvl-source:/mnt/repos -e PASSWORD=SOME_PASSWORD --name rstudio rocker/rstudio`

Working on R 4.2 and Hugo 0.106.0

After it, open the browser on 8787, and run `setup.R` to install rblogdown, hugo and the theme.

### TO DO
- [] Dockerfile
- [] CI/CD
- [] Better docs and instructions.