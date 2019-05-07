# decbae
DEep Contextualized Biomedical Abbreviation Expansion

# Dataset
Please download the automatically collected dataset [here](https://drive.google.com/open?id=1zsGHLbRXg_DwK9R3luz057IiN1WjL1WC). It's a list of contexts for all abbreviations. Each element in this list is ```List[List[Tokens], Str(Abbr), Str(Definition)]```

```data/abbr_dataset.json``` is a dict organized as ```Dict{Str(Abbr): Dict{Abbr Dataset}}```, indices in it are the list indices of the dataset above.
