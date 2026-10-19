# Maps

Interactive climate maps of the lower 48 states at 800-meter detail.

- **[How many days a year do trees have leaves?](https://mailforfredclaus.github.io/Maps/)**: the average time from spring leaf-out to autumn leaf drop. It also shows leaf-out and leaf-drop dates, and a line where trees have leaves exactly half the year.
- **[How long are the warm and cold seasons?](https://mailforfredclaus.github.io/Maps/seasons.html)**: days a year when the average daily high is above 70°F or below 50°F, with season dates for any spot and a line where the two are equal.

Hover or tap anywhere for local values, search for a town, and zoom in to see mountains and valleys.

## How they were made

- **Climate:** PRISM 1991-2020 temperature normals (800 m monthly values, shaped day by day with PRISM's 4 km daily normals).
- **Leaf timing:** a temperature-driven leaf-out and leaf-drop model, calibrated against the PhenoCam Network's forest-canopy cameras at about 140 deciduous sites and checked against USA-NPN observations.
- **Accuracy:** typical error at a camera site the model never saw is about 8 days for leaf-out and 10 days for leaf drop.

Each page is a single self-contained HTML file.

## Data sources

- [PRISM Climate Group](https://prism.oregonstate.edu/normals/), Oregon State University
- [PhenoCam Network](https://phenocam.nau.edu/)
- [USA National Phenology Network](https://www.usanpn.org/)
- US Census Bureau boundaries, gazetteer and population estimates
