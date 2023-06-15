# dude_bro_sis

# Read me

The data and files in this repository accompany an article soon to be published. More info when it comes out!
The data consists of:
- 55893 concordance lignes extracted from the TV Corpus website (shared with Mark Davies' permission), with "dude", "dudette", "bro" and "sis" as keywords.
- The TV Corpus metadata.

### Objectives of the study
The goal of the study was to explore the diachronic development of four gendered address terms in the TV Corpus, from 1950 to 2017 : "dude" and "dudette", "bro" and "sis". 

### About the data
The [TV Corpus](https://www.english-corpora.org/tv/) is awesome! It contains contains 325 million words from 75,000 TV episodes.

The corpus can be queried for free, which is how I generated the concordances in this repo. It took me a long time, lots of copying and pasting, 110% would not recommend. I think the free version is fine if you want to study words that are rare or if you are just interested in aggregated frequencies (that you can get easily with the "Chart" tool of the corpus interface).

In my case, I wanted to do some manual annotation, to remove metalanguage ("I spent a month practicing how to say 'dude' " - *The O.C.*, 2006) and to distinguish between reference terms ("See this dude here? See that dude in the gold?" - *The A-Team*, 1985) and address terms ("Hey, dude, do I look like a pharmacist?" *90210*, 2011).

Additionally, I was not interested in aggregated frequencies, but in the frequency of the address/reference terms per episode. Turns out, it was impossible to know, as the unique identifiers in the [metadata](https://www.english-corpora.org/tv/files/sources_tv.zip) provided on the TV Corpus site are not provided with the concordances in the free version of the corpus. So I did something else: I created a variable called "unique_titles", by concatenating the name of each show + the year provided in each concordance line. This way I was able to know how many times "dude", "bro", "sis" and "dudette" appeared in each year of each series.



