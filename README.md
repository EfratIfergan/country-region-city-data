﻿# country-region-city-data
This repository contains a list of countries with their regions and cities. The data is based on the ISO database, and the codes are updated accordingly.

## Data Structure
The data is structured in TypeScript interfaces, as follows:
```
 interface CountryWithCitiesAndRegions {
  countryName: string;
  countryShortCode: string;
  cities: Cities[];
  regions: Regions[];
}

interface Cities {
  cityName: string;
}

interface Regions {
  name: string;
  shortCode?: string;
}
```
## Contributing
If you find any errors or have suggestions for improvements, please open an issue or submit a pull request. We welcome any feedback that can help make this data more accurate and useful.


