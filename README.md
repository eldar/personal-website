# Academic Webpage

This is the source code for my [personal webpage](https://eldar.github.io/).

The code is based on the **Academic** framework for **Hugo**.
This framework allows you to never touch HTML/CSS to build your own website.
I simplified and streamlined the theme significantly to match the type of personal webpages you would find in the Machine Learning community.
You can check out [the original demo](https://themes.gohugo.io/theme/academic/) of Academic or its [official documentation](https://sourcethemes.com/academic/docs/).

In this README I will re-iterate the very basics needed to get started, mostly for my own sake.

## Getting Started

1. [Download](https://github.com/gohugoio/hugo/releases) and install Hugo.

2. Clone or fork this repository:

```bash
git clone --recurse-submodules https://github.com/eldar/personal-website.git mywebsite
cd mywebsite
```

3. View your website

```bash
    hugo server
```

    Now you can go to http://localhost:1313 and your new Academic powered website should appear.

## Filling Content

### General Info
1. Set your name in `config.toml` in the `[params]` section. Also set the title of the website

2. Add short bio to the `content/home/about.md`

### Publications
1. Now you can start adding publications. Publications are stored in the `content/publication` directory, you can use mine as an example. In order to generate data for publication you can use a python tool that is supplied with the **Academic** framework:

```bash
# First install the tool:
pip3 install academic

# then import the .bib file into the website
# make sure your current directory is the root of the website repo
academic import --bibtex /path/to/publication.bib
```

2. The previous step will create a directory corresponding to the publication under `content/publication`. This directory will contain file `index.md` which contains various definitions. You will have to open it and make further edits:

- Set the abstract to the `abstract` field, if not already there
- Set unique publication identifier to the `shortname`, much like you do in the bibtex, for example `"watson2018cvpr"`
- Specify abbreviation for the conference in `venue` field, for example `"CVPR, 2018"`
- You can place an optional teaser image to the publication directory, its file name has to contain `featured` in it.
- Add various URLs associated with the paper: `url_pdf` to link to the PDF of the paper (required), `url_project` for the project page, `url_video` for the video, `url_code` for the code and `url_slides` for the slides.

## License

Copyright 2018 [George Cushen](https://georgecushen.com), [Eldar Insafutdinov](https://eldar.github.io).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.
