# macro2
Repository for experiment done in **Auditing Gender and Prestige Bias in News Reporting**. Analyzes how news sources use expert speakers in article quotes, and how quantity of representation differs by expert gender and news outlet ideological orientation.
Repository includes:
- **process.ipynb:** Illustrates parsing of newspaper articles for sentences featuring quotes. Inculdes inference of the speaker's gender and speaker's affiliated academic, federal and think tank organizations.
- **compare.ipynb:** Analysis of results. Provides code for generating all figures in paper, as well as a few experiments not included in the paper.
- **data/:** Extractions retrieved using methodology outlined in process.ipynb. Also includes _unknown_dict.csv_ and _andy_dict.csv_, containing corrected gender labels for most commonly misgendered (via unknown and androgynous labels) public figures.


## Installation requirements:
- Download [GenderGapTracker](https://github.com/sfu-discourse-lab/GenderGapTracker) for dependency parse based quote and speaker extraction methods. Package requires additional libraries.
- Download [gender_detector](https://pypi.org/project/gender-guesser/) for inferring most likely gender affiliations from first names.


## Contributors
TODO: file of contributors

## Citation
```bash
bibtex citation goes here
```
