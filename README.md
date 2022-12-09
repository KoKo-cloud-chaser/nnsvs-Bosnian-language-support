# nnsvs-Bosnian-language-support
Hed and supporting files for Bosnian Language NNSVS Dataset Creation

This repo contains the files required to create a Bosnian dataset for use in NNSVS.
A full pronunciation guide is provided.

The phoneme set is custom (based on bosnian alphabet) .

Here's some helpful infos:
| Language       | Num. Phonemes | Native Spk Verified | est. hours | Dict? |
| -------------- | ------------- | ------------------- | ---------- | ----- |
| Bosnian        | 31 ~ 38       | ~                  | 50 mins ~ 1.5 hr| O

## Additional Inf

The HED file was written UtaUtaUtau's hed writer for NNSVS.

the /dic folder contains several files:  
/BoX_Bosnian_NNSVS.table - dictionaries for various lanugages.
/pronunciation.txt - a full pronunciation guide using english words as an example
/phonemes.txt - the full list of phonemes used to made the .hed and .table files 

A the time of writing, there are no samples using this hed file. `ValueError: could not broadcast input array from shape (###,496) into shape (###,###)`.
