# Trove newspapers with articles published after 1954

[![Frictionless](https://github.com/GLAM-Workbench/trove-newspapers-data-post-54/actions/workflows/frictionless.yaml/badge.svg)](https://repository.frictionlessdata.io/report?user=GLAM-Workbench&repo=trove-newspapers-data-post-54&flow=frictionless) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6812811.svg)](https://doi.org/10.5281/zenodo.6812811)

Current version: [v1.1](https://github.com/GLAM-Workbench/trove-newspapers-data-post-54/releases/tag/v1.1)

Due to copyright restrictions, most of the digitised newspaper articles on Trove were published before 1955. However, some articles published after 1954 have been made available. This repository provides data about digitised newspapers in Trove that have articles available from after 1954 (the 'copyright cliff of death'). 

The data was extracted from the Trove API using [this notebook](https://glam-workbench.net/trove-newspapers/#beyond-the-copyright-cliff-of-death) from the [Trove newspapers](https://glam-workbench.net/trove-newspapers/) section of the GLAM Workbench.

The data is available as a CSV file entitled `newspapers_post_54.csv` and contains the following fields:

- `title` – the full title of the newspaper
- `state` – the state in which the newspaper was published
- `id` – Trove's unique identifier for this newspaper
- `startDate` – the earliest date of articles from this newspaper available in Trove
- `endDate` – the latest date of articles from this newspaper available in Trove
- `issn` – ISSN
- `number_of_articles` – the number of articles from this newspaper **published after 1954** available in Trove
- `troveUrl` – link to more information about this newspaper

----

This repository is part of the [GLAM Workbench](https://glam-workbench.github.io/).  
If you think this project is worthwhile, you might like [to sponsor me on GitHub](https://github.com/sponsors/wragge?o=esb).