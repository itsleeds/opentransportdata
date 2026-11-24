# opentransportdata

A curated list of open transport datasets for research, teaching, and to save the world 🚲🚶🚀

If you know of any other useful datasets / resources to help with these things, please put in a [PR](https://github.com/Robinlovelace/opentransportdata/edit/master/README.md).

Each addition must come with a description that explains how it's useful.
The aim is to highlight high quality datasets rather than breadth.

## Lists

There are already lists of transport data, including:

- https://data.world/datasets/transportation which lists a variety of 3000+ seemingly mostly open datasets
- https://opentransportdata.swiss/de/dataset which lists open datasets in Switzerland
- https://www.europeandataportal.eu/data/en/group/transport open transport datasets in Europe
- https://github.com/awesomedata/awesome-public-datasets#transportation a list of transport data curated by awesomedata
- https://data.gov.uk/search?filters%5Btopic%5D=Transport 1000+ transport datasets from gov.uk in the UK
- https://catalog.data.gov/dataset?q=transport transport data from data.gov in the USA
- https://github.com/andylua-beep/kales-trailer-road-regulations — an open JSON dataset and summary table of statutory heavy commercial trailer axle-load, drive-axle, width, and height limits across 28 jurisdictions with primary regulatory citations (useful for freight routing and fleet load-compliance modeling).
- Any more? let us know!

## Point data

- https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data which links to an open dataset on road crashes in the UK. A large (1.6m points) sample of these can be accessed with `dl_stats19()` function from the stplanr R package (see [here](https://cran.r-project.org/web/packages/stplanr/vignettes/stplanr-paper.html) for details).

## Origin-destination data

## Route network and GTFS data

## Travel survey data


| Country       | Region           | Description                                                                                                                                                                 | Link                                                                                   | Used in                                    |
| ------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------ |
| Australia     | Queensland state | Queensland Household Travel Survey Series                                                                                                                                   | https://www.data.qld.gov.au/dataset/queensland-household-travel-survey-series          |                                            |
| Australia     | Victoria state   | Victorian Integrated Survey of Travel and Activity                                                                                                                          | https://transport.vic.gov.au/about/data-and-research/vista/vista-data-and-publications | https://github.com/matsim-melbourne/demand |
| United States | Various states   | The Transportation Secure Data Center (TSDC) provides free access to detailed transportation data from a variety of travel surveys and studies conducted across the nation. | https://www.nrel.gov/transportation/secure-transportation-data/                        |                                            |

