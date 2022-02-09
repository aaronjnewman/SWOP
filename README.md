# SWOP (Swedish Word Order Processing)

Data and analysis scripts associated with the manuscript: *Native word order processing is not uniform: An ERP-study of verb-second word order*. This paper was accepted for publication by *Frontiers in Psychology - Language Sciences*, on Feb 3, 2022; DOI: 10.3389/fpsyg.2022.668276

## Authors:
- **[Susan Sayehli](https://www.su.se/profiles/ssaye-1.266931)**, Centre for Research on Bilingualism, Department of Swedish Language and Multilingualism, Stockholm University, Stockholm, Sweden
- **[Marianne Gullberg](https://www.sol.lu.se/en/person/MarianneGullberg)**, Centre for Languages and Literature, Lund University, Lund, Sweden
- **[Aaron J Newman](https://www.dal.ca/faculty/science/psychology_neuroscience/faculty-staff/our-faculty/aaron-newman.html)**, Department of Psychology & Neuroscience, Dalhousie University, Halifax, NS, Canada
- **[Annika Andersson](https://lnu.se/en/staff/annika.andersson/)**, Swedish as a Second Language, Department of Swedish, Linnaeus University, Växjö, Sweden

## Abstract:
Studies of native syntactic processing often target phrase structure violations that do not occur in natural production. In contrast, this study examines how variation in basic word order is processed, looking specifically at structures traditionally labelled as violations but that do occur naturally. We examined Swedish verb-second (V2) and verb-third (V3) word order-processing in adult native Swedish speakers, manipulating sentence-initial adverbials (temporal idag ‘today’, spatial hemma ‘at home’, and sentential kanske ‘maybe’) in a written sentence completion task, in acceptability judgements, and neurocognitively as event-related potentials (ERP) recorded to visually presented sentences. An initial corpus study showed that the adverbials differ in frequency in fronted position (idag > kanske > hemma), and although all occur mainly with V2 word order, kanske occurs more frequently with V3 in natural production than both idag and hemma. 

## Code

All results reported in the manuscript should be reproducible using the code and data in this repository. Code is provided in Jupyter notebooks, which are extensively annotated. The original raw EEG data files are not included in this GitHub repository, because they exceed GitHub's file limit. The raw EEG files are provided on the accompanying [OSF site](https://osf.io/5vn2y/) for this project, and should be downloaded to the `data` folder of this repo if one desires to re-run the preprocesing.

- EEG preprocessing and visualization were conducted using [MNE](https://mne.tools/) v 0.23.0 under [Python](https://www.python.org/) v 3.9
- statistical analyses were conducted using the [mgcv](https://cran.r-project.org/web/packages/mgcv/) package v 1.8-36, under [R](https://cran.r-project.org/) v 4.1.0

Code was written by [Aaron J Newman](https://github.com/aaronjnewman), [NeuroCognitive Imaging Lab](http://ncil.science), [Dalhousie University](https://dal.ca), [including code adapted from Alday](https://osf.io/pnaku/) for computing baseline regression in MNE. Code is released under the [The 3-Clause BSD License](https://opensource.org/licenses/BSD-3-Clause).
