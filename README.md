# FormantPath-vowels
Application of Praat's "To FormantPath..." command for getting by-speaker, by-token formant ceilings, as a more precise alternative to setting general ceilings based on assumptions about speaker sex. Generates numerous formant measurements per token, which may later be aggregated as desired (e.g., by-token medians).

Demoed in [get_formant_path.ipynb](https://github.com/acgalvano/FormantPath-vowels/blob/main/get_formant_path.ipynb) for single and dual speaker recordings. Requires [parselmouth](https://github.com/YannickJadoul/Parselmouth), [phonlab](https://github.com/rsprouse/phonlab), and [audiolabel](https://github.com/rsprouse/audiolabel) libraries.

Visualization using various by-token grouping stragies and kernel density plots demoed in [visualize_formants.ipynb](https://github.com/acgalvano/FormantPath-vowels/blob/main/visualize_formants.ipynb).

Script for dealing with pairwise results for categorial predictors from an R-based linear mixed-effects model for one formant (e.g., F1), a continous outcome: [manage_pairwise_results.ipynb](https://github.com/acgalvano/FormantPath-vowels/blob/main/manage_pairwise_results.ipynb)

Outlier detection (plotting, saving set of outliers for all speakers: [vowel_outliers_05-23-25.ipynb](https://github.com/acgalvano/FormantPath-vowels/blob/beadfbddd1035e52f73ee950162e23a0229778fa/vowel_outliers_05-23-25.ipynb). Contact repo owner for full formants data file.
