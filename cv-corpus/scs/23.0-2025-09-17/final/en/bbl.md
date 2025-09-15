# *ვაჲღეჼ* &mdash; Tush (`bbl`)

This datasheet is for version 23.0 of the the Mozilla Common Voice *Scripted Speech* dataset 
for Tush (`bbl`). The dataset contains 12 hours of recorded
speech (12 hours validated) from 22 speakers.

## Language

<!-- {{LANGUAGE_DESCRIPTION}} -->
<!-- Provide a brief (1-2 paragraph) description of your language -->
This language belongs to the Nakhi language family and is currently endangered. The language is acknowledged by researchers as much older than the two other languages of this language family - Chechen and Ingush. The grammar of this language was the first to be scientifically studied among all Iberian-Caucasian languages (A. Schiefner, Versuch über die Tush-Sprache, Petersburg, 1854). This ancient language, brought to this day by the ethnically Georgian (Orthodox Christian) aboriginal bilingual population, was spoken by more than 3,000 people a century ago.
This language was known, and still is known, in the main settlement of the Tush people - the village of Zemo Alvani - by people from other parts of Georgia and other nationalities who settled there during World War I-II.
In recent decades, as a result of the outflow of the working-age population from the country, the connection between generations has been severed, and mixed marriages have become more common. That's why today only the older generation knows the language well, the 40+ generation not so well, and those under 25 mostly only understand it and cannot speak. That is, fewer than 800 people scattered around the world speak this language to a greater or lesser extent, and about 400 locally.
In fact, the scientific study of the language today is in complete stagnation - the language is unexplored. Although there is a lot to be studied, both in terms of this language itself and its connection with the Georgian-Kartvelian and Hurrian languages. This language course is no longer taught in the country's higher education institutions.
The language is referred to by different terms - the Georgian term Tushuri and the Russian term тушинский; during the USSR, it was replaced by the term Batsburi - бацбийский, and after that by Tsova Tush. People are dissatisfied - by changing the name of their language, the Tushetians - this border-defending people, praised many times in history - appear as an unclear ethnicity.
But the language is still alive - enthusiasts even translate poetry into this language, while maintaining rhyme, meter, and rhythm.

<!-- ### Variants -->
<!-- {{VARIANT_DESCRIPTION}} -->
<!-- @ OPTIONAL @ -->
<!-- Describe the variants (MCV variants) of your language -->

<!-- Original Answer: -->
<!-- There are no variants defined for the Tush language. Slight variations present in the language are not essential. -->

## Demographic information
<!-- You can get a lot of the information in this section from https://analyzer.cv-toolbox.web.tr/browse -->
The dataset includes the following distribution of age and gender.

### Gender

Self-declared gender information, frequency refers to the number of clips annotated with this gender.

<!-- {{GENDER_TABLE}} -->
<!-- @ AUTOMATICALLY GENERATED @ -->
<!-- 
| Gender | Frequency |
|--------|-----------|
| male, masculine | ? |
| undeclared | ? |
| female, feminine | ? |
-->
### Age

Self-declared age information, frequency refers to the number of clips annotated with this age band.

<!-- {{AGE_TABLE}} -->
<!-- @ AUTOMATICALLY GENERATED @ -->
<!-- 
| Age band | Frequency |
|----------|-----------|
| teens | ? |
| twenties | ? |
| thirties | ? |
| fourties | ? |
| fifties | ? |
   ...if other age ranges are present in your data, add rows...
-->

## Text corpus

<!-- {{TEXT_CORPUS_DESCRIPTION}} -->
<!-- @ OPTIONAL @ -->
<!-- An overview of the text corpus, with information such as average length (in characters and words) of validated sentences. -->
Presently, the corpus contains single sentences or texts with a few sentences (5 to 30 sentences). The average length of the sentences is from 8 to 15 words. These texts are created by enthusiasts specifically for Common Voice.

### Writing system

<!-- {{WRITING_SYSTEM_DESCRIPTION}} -->
<!-- @ OPTIONAL @ -->
<!-- A description of the writing system (or writing systems) used in the text corpus -->
Georgian alphabet with additional signs, symbols.

#### Symbol table

<!-- {{ALPHABET_TABLE}} -->
<!-- @ OPTIONAL @ -->
<!-- If the writing system is alphabetic, you can include the valid alphabet here -->
```ა ბ გ დ ე ვ ზ თ ი ჲ კ ლ ლ' მ ნ ჼ ო პ ჟ რ ს ტ უ უ̂ ფ ქ ღ ყ შ ჩ ც ძ წ ჭ ხ ჴ ჯ ჰ ჰ̦ ჵ ჸ ჺ ა́ ე́ ი́ ო́ უ́  ე̆ ი̆ ო̆ უ̆```

### Sample

There follows a randomly selected sample of five sentences from the corpus.

<!-- {{SENTENCES_SAMPLE}} -->
```
1. ცჰ̦აჲნი̆ გე́ფსუდო́ლიჼ წე́ლტი უჲთთო̆, თიშჩოვ, თხა ბუჲსო̆ მა́ მა́რხო̆ და́სტლა.
2. წყე სო́მხთი რესტო́რნე შეკვე́თ მე ჲე́ჸეჼ თხოჼ, სო́უზეჼ დაყე̆ დითხ რე́ვალაჲნი̆ საკმაზ იცნორა́თხ. 
3. ვარბი ქე́კერ ჸეჸმაქ ას ა́ლვინ ვო́ტუშ, ვორ'ლწატყ-იწატყ მო́ჸ ხილ'ურ, მეჯოგე́ გურ ო́სი ცჰ̦ა.
4. ო თათაჲრი̆ დაკლაჲვნო́რ, ეჴუჲგო დუჴ ტათებ ხილ'ო-აჲნო̆, ლაჭყ-ლაჭყუშ ჰ̦ალო̆ ბო́წბაჲლნო́რ.
5. ჴო́წ ტყაუზტყ დო́ლარ ხილ'ნო́ჰ̦ერ სო́გო, "ფსიკეჼ-თანთეჼ ფალ" ჰ̦ალო̆ ღე́ბადოჩო̆ ჟაგნოღ დე́რწდორა́ს.
```
### Sources

<!-- {{SOURCES_LIST}} -->
<!-- @ OPTIONAL @ -->
<!-- A list of sentence sources, can be curated to the top-N -->

### Text domains

<!-- {{TEXT_DOMAIN_DESCRIPTION}} -->
<!-- @ OPTIONAL @ -->
<!-- What text domains are represented in the corpus? -->
General
Agriculture and Food
Nature and Environment

### Processing

<!-- {{PROCESSING_DESCRIPTION}} -->
<!-- @ OPTIONAL @ -->
<!-- How has the text data been processed -->
Because there is no single agreed-upon font, we could not use texts copied from books. To compose sentences for the corpus, we developed a font that is as convenient as possible—simplified on the one hand, and refined with the addition of stressed vowels on the other. The material collected to date consists of short episodes written specifically for this corpus by several people. Editing was expressed in shortening sentences and reducing them to fewer than 15 words. Sometimes we had to check and clarify texts over the phone or in person. We also recorded the stories of those who knew the language best.
The biggest obstacle turned out to be:
    1. In Pirago, there is no single consonant () grapheme, for which we used the letter (ჰ̦), and the symbols for short vowels and consonants, placing them one by one on the graphemes, take a lot of time when typing;
    2. With two exceptions, elderly people cannot independently create voice recordings due to their lack of computer skills, even though they know the language well.

## Get involved!

### Contribute

<!-- {{CONTRIBUTE_LINKS_LIST}} -->
<!-- Here you can include links for how to contribute to the dataset -->

## Acknowledgements

### Datasheet authors

<!-- {{DATASHEET_AUTHORS_LIST}} -->
<!-- A list in the format of: Your Name <email@email.com> -->
* Tinatin Tsiskarishvili <tinatintsiskarishvili@gmail.com>

## Licence

This dataset is released under the [Creative Commons Zero (CC-0)](https://creativecommons.org/public-domain/cc0/) licence. By downloading this data
you agree to not determine the identity of speakers in the dataset.

