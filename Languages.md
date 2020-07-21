# Languages and Their Features

Below is the table with all languages used and their features.
See <a href="#sources">information sources</a> to learn what we refered to for the information presented in the table.

Language|SV/VS|VO/OV|AdjN/NAdj|Morphological type|WPO 1|WPO 2|Number of components|Ratio of components|RelativeClause + Noun|Gen-Noun|Neg V|Neg Morphemes
--|--|--|--|--|--|--|--|--|--|--|--|--
English|SV|VO|AdjN|flective|N/A|N/A|N/A|N/A|Noun-Relative clause|No dominant order|NegV|Negative particle
Russian|SV|VO|AdjN|flective|0|0|13886|69|Noun-Relative clause|Noun-Genitive|NegV|Negative particle
Spanish|SV|VO|NAdj|flective|3|29.00|16235|81|Noun-Relative clause|Noun-Genitive|NegV|Negative particle
French|SV|VO|NAdj|flective|3|46.00|15434|77|Noun-Relative clause|Noun-Genitive|OptDoubleNeg: (Neg)Vneg|Negative particle
Italian|SV|VO|NAdj|flective|3|37.00|8555|42|Noun-Relative clause|Noun-Genitive|NegV|Negative particle
German|SV|VO/OV|AdjN|flective|3|51.00|14742|73|Noun-Relative clause|Noun-Genitive|Type 1 / Type 2|Negative particle
Finnish|SV|VO|AdjN|agglutinative|3|34.00|13847|69|Noun-Relative clause|	Genitive-Noun|NegV|Negative auxiliary verb
Japaneese|SV|OV|AdjN|agglutinative|0|0|16178|80|Relative clause-Noun|Genitive-Noun|[V-Neg]|Negative affix
Hindi|SV|OV|AdjN|analytical|0|0|8156|40|Correlative|	Genitive-Noun|NegV|Negative affix
Turkish|SV|OV|AdjN|agglutinative|1|10|18457|92|Relative clause-Noun|	Genitive-Noun|[V-Neg]|Negative affix
Vietnameese|SV|VO|NAdj|analytical|1|10|4677|23|Noun-Relative clause|Noun-Genitive|NegV|Negative word| unclear if verb or particle
Lithuanian|SV|VO|AdjN|flective|2|20|7165|35|Noun-Relative clause|	Genitive-Noun|[Neg-V]|Negative affix
Hebrew|SV|VO|NAdj|flective|0|0|14721|73|Noun-Relative clause|Noun-Genitive|NegV|Negative particle
Arabic|VS|VO|NAdj|flective|0|0|16970|84|Noun-Relative clause|Noun-Genitive|NegV|Negative particle
Icelandic|SV|VO|AdjN|flective|2|20|7934|39|Noun-Relative clause|Noun-Genitive|Type 1 / Type 2|Negative particle

## Synthesism and Agglutination Indices

We were also able to find synthesism and agglutination indices for some languages.

Language|	Synthesism index|	Agglutination index
--|--|--
English|	1.63	| -
Russian	|2.4	|-
German	|2| -	
Japaneese	| 2.71|	0.86
Hindi	|1.74	|0.34
Turkish	|2.15	|0.98
Vietnamese|	1.52	|1
Hebrew|	2	|0.18
Arabic|	3.14|	0.5


## <a name="sources">Information Sources</a> 

We used various sources to get different features of the languages:

### WALS

Almost all structural features are taken from WALS:
* SV/VS
* VO/OV
* AdjN/NAdj
* RelativeClause + Noun
* Gen-Noun
* Neg V
* Neg Morphemes

### E-Z-Glot 

We used E-Z-Glot to get an estimation of word-piece overlap between English and other languages.

* WPO1
* WPO2

Since not all languages are represented at E-Z-Glot, we converted WPO1 into WPO2 applying the following logic:
- 0 - a language with a writing system other than Latin;
- 1 - a language with a Latin script, but belonging to a non-Indo-European language family;
- 2 - a language with Latin script and belonging to the Indo-European language family;
- 3 - a language with Latin script and one of the closest languages according to E-Z Glot. It is important to note that the language family did not matter here (Vietnamese also received this rank), since it is the amount of general vocabulary that is important to us.

### Calculations

* Number of components
* Ratio of components

These features are calculated after transforming data set lists into graphs (see mBERT_Experiments.ipynb).

### Kasevich et al., Quantitative Typology of Asian and African Languages\*

* Agglutination index
* Synthesism index

\* _Касевич, В.Б., Яхонтов С.Е. (отв.ред.) Квантитативная типология языков Азии и Африки. Л., Изд-во Ленинградского ун-та, 1982.- 331 с._
