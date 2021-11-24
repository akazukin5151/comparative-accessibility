You can view this on your browser with binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akazukin5151/comparative-accessibility/HEAD)

To run, you need to install `momepy` (https://docs.momepy.org/en/stable/index.html) with `pip install momepy`

You need to download the data yourself. They can't be uploaded to github because they're too large.

- data/india/GTFS
    - https://opendata.iiitd.edu.in/data/static/

- data/bus-stops-10-06-15.csv
    - https://data.london.gov.uk/dataset/tfl-bus-stop-locations-and-routes

- data/bus-sequences.csv
    - https://tfl.gov.uk/info-for/open-data-users/api-documentation#on-this-page-4

- data/london/RODS_2017
    - https://data.london.gov.uk/dataset/tfl-rolling-origin-and-destination-survey

- data/london/roads/
    - https://data.gov.uk/dataset/65bf62c8-eae0-4475-9c16-a2e81afcbdb0/os-open-roads
    - Files starting with TQ contains London; remove all other files

- data/india/overpass/export.geojson
    - paste the contents of code.md into https://overpass-turbo.eu/
