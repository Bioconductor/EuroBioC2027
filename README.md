# For developers

## Organizers

### How to add your image?

1. Please fork the project.
2. Add your image to [images/organizers](https://github.com/Bioconductor/EuroBioC2027/tree/devel/images/organizers) directory.
3. Add information to [data/organizers.csv](https://github.com/Bioconductor/EuroBioC2027/blob/devel/data/organizers.csv) file.
4. Create a pull request.

## How to add a page?

1. Add page in quarto format to the [pages](https://github.com/Bioconductor/EuroBioC2027/tree/devel/pages) directory.
2. Update [_quarto.yml](https://github.com/Bioconductor/EuroBioC2027/blob/devel/_quarto.yml) file.
3. Build the site locally.

## How to build the site?

The site is built by using GitHub Actions. Always build the website locally if
you have done major changes. The site can be built with the following R command:

```
quarto::quarto_render()
```

## How to get bioconductor.org address?

Ask the Bioconductor core team to add EuroBioC202* subdomain. Update CNAME.

## How to add images to carousel?

The images for the carousel are [here](https://github.com/Bioconductor/EuroBioC2027/tree/devel/images/carousel).
To harmonize the width of images, one can run [the script](https://github.com/Bioconductor/EuroBioC2027/blob/devel/R/add_image_background.R).
It automatically adds blue/green borders.

Without the harmonized widths and heights, the carousel would not look as good.

Update the [carousel.yml](https://github.com/Bioconductor/EuroBioC2027/blob/devel/data/carousel.yml).
