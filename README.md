# Izzi Lab Website

Academic website for the Izzi Group on Bioinformatics and Data Analysis at the University of Oulu, Finland.

## About

The Izzi Lab, led by Associate Professor Valerio Izzi, focuses on developing computational methods to understand cancer biology through the lens of systems biology, with particular emphasis on the extracellular matrix and tumor microenvironment.

## Building the Website

This website is built using [Quarto](https://quarto.org/). To build locally:

```bash
# Install Quarto from https://quarto.org/docs/get-started/

# Clone the repository
git clone https://github.com/izzilab/izzilab.git
cd izzilab

# Build the website
quarto render

# Preview locally
quarto preview
```

## Structure

- `index.qmd` - Homepage
- `people/` - Team member profiles
- `posts/` - News and blog posts
- `publications/` - Research publications
- `research.qmd` - Research overview
- `resources.qmd` - Software tools and datasets
- `opportunities.qmd` - Open positions
- `contact.qmd` - Contact information

## Contributing

To add content:

1. **Add a team member**: Create a new `.qmd` file in `people/staff/`, `people/gras/`, or `people/uras/`
2. **Add a publication**: Create a new `.qmd` file in `publications/articles/`
3. **Add a news post**: Create a new folder with `index.qmd` in `posts/`

## Contact

- **PI:** Valerio Izzi (Valerio.Izzi@oulu.fi)
- **Website:** https://izzilab.github.io
- **GitHub:** https://github.com/Izzilab

## License

Content is licensed under CC BY 4.0. Code is licensed under MIT.
