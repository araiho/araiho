# Hi, I'm Ann Raiho 👋

Quantitative ecologist and senior data scientist, Ph.D. I turn ecological and satellite data into decisions, and I move research models into production with versioned releases and CI/CD.

My lane is Bayesian and hierarchical modeling, uncertainty quantification, forecasting, and reproducible geospatial pipelines. A decade of it across academia, NASA, and climate tech.

### What I build

- **[bayes-retriever](https://github.com/araiho/bayes-retriever)**: A Bayesian search-and-rescue system for lost dogs. It fuses USGS 1m LiDAR and OpenStreetMap into a Probability-of-Area map. It ranks non-overlapping search segments so the top ~10 hold ~73% of the probability, and republishes every 30 minutes via GitHub Actions. Python, folium, GitHub Pages.
- **Canopy Intelligence**: A per-tree climate-forecasting product that scores 142,000 Philadelphia street trees against 2050 conditions, with auditable per-tree risk from a reproducible remote-sensing pipeline. Python.
- **[linkages_package](https://github.com/araiho/linkages_package)**: Fortran and R implementation of the LINKAGES forest gap model (Pastor and Post 1983). Long-lived, still forked and used.

### What I'm working on now

- **Temple University** (Adjunct Research Assistant Professor): Leading an NSF-funded program that forecasts species extinction risk under climate and land-use change. I cut one core forecast from 10 days to 7 minutes by improving I/O and vectorizing the math, and improved alignment with IUCN Red List categories 10x. The pipeline runs on satellite imagery and foundation-model embeddings, validated against ground truth before it ships.
- **Raiho Consulting** (Principal): Integrated the SPITFIRE fire model into the LPJ-EOSIM Earth system model in C++, including a new coupling to its CENTURY nitrogen cycle, with reproducible workflows and a validation framework.

### Before that

Head of Data Science at **Funga**. There I led a team of 4 Ph.D. scientists, built a patented ensemble recommender that raised inoculant selection win rate from 10% to 50%, and ran carbon-reporting pipelines across 28,000 acres that cut manual effort 50%. Before that, a postdoc at **NASA Goddard / UMD**. I set minimum satellite requirements that informed instrument and orbit choices for the Surface Biology and Geology mission, and flew a 13-week AVIRIS-NG hyperspectral campaign.

### A note on what you can see here

Most of my recent work is client or in-progress and lives in private repos, so the public list is only part of the picture. A few examples I can describe:

- **Extinction risk** (Temple, NSF-funded): a forecasting system for time to extinction under climate and land-use change, built on satellite imagery and foundation-model embeddings at global scale.
- **LPJ-EOSIM**: fire and Earth-system-model development, including the SPITFIRE fire model and a new coupling to the CENTURY nitrogen cycle, in a NASA dynamic global vegetation model.
- **Canopy Intelligence**: a monorepo of forest and tree analytics products for Raiho Consulting clients.
- **GeoMend**: a training-free pipeline that flags, corrects, and georeferences erroneous coordinates in GBIF occurrence records.
- **Wissahickon forecast**: forest forecasting for the Wissahickon watershed built on the UVAFME gap model.

Happy to walk through any of it on request.

### Tools

Python · R · C++ · SQL · PyTorch · GDAL · rasterio · XArray · GeoPandas · Shapely · Google Earth Engine · AWS · Docker · GitHub Actions · HPC

### Reach me

📍 Philadelphia, PA · 🔗 [ann-raiho](https://www.linkedin.com/in/ann-raiho-20b7ba1b9) · 🌐 [araiho.github.io](https://araiho.github.io)
