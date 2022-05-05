# Code for Craft AI blog article on an overview of XAI libraries



## Setup
Use poetry python package manager to install the correct dependencies :

- [Python](https://www.python.org) (any version >3.8 should work),
- [Poetry](https://python-poetry.org).

Once poetry is installed, in order to install the dependencies run:

 ```console
  poetry install
  ```
Then to launch the notebook run:

 ```console
 poetry run jupyter notebook ./src/explaining_penguins.ipynb
  ```

### Code Directory
Contains explaining_penguins.ipynb jupyter notebook illustrating the blog article.

### Data Directory
Contains the Palmer penguins dataset

## References
__Data originally published in:__

    Gorman KB, Williams TD, Fraser WR (2014). Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (genus Pygoscelis). PLoS ONE 9(3):e90081. https://doi.org/10.1371/journal.pone.0090081

__Data citations:__

Adélie penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Adélie penguins (Pygoscelis adeliae) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative. https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f.

Gentoo penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Gentoo penguin (Pygoscelis papua) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative. https://doi.org/10.6073/pasta/7fca67fb28d56ee2ffa3d9370ebda689.

Chinstrap penguins:

    Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Chinstrap penguin (Pygoscelis antarcticus) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 6. Environmental Data Initiative. https://doi.org/10.6073/pasta/c14dfcfada8ea13a17536e73eb6fbe9e.

