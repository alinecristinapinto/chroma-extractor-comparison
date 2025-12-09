###Introdution
This project contributes to reproducing and expanding the research of Korzeniowski and Widmer (2016) by applying it to a different database. The reference work focused on performances of songs by Franz Schubert, specifically his 'Winterreise' (1826–1828). A significant issue in previous academic studies was noise in Chromagram analysis; this has been greatly refined through the use of a sliding analysis window and Deep Learning. The current goal is to apply this analysis to a new source to validate the results within the context of classical piano and vocal duets.

# chroma-extractor-comparison
A benchmark comparing the Deep Chroma Extractor (madmom) against standard chroma features (librosa) for chord recognition

### Dataset
[Schubert Winterreise Dataset - HU33](https://zenodo.org/records/3968389)

### Dependences
`pip install numpy pandas librosa tensorflow matplotlib jupyter notebook`

### Running notebooks
`py -m jupyter notebook`
