

--------------------------------------------------------------------------------

## Treebank Statistics (UD_German)

This relation is universal.

4894 nodes (2%) are attached to their parents as `cop`.

3816 instances of `cop` (78%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.60543522680834.

The following 37 pairs of parts of speech are connected with `cop`: [de-pos/ADJ]()-[de-pos/VERB]() (2176; 44% instances), [de-pos/NOUN]()-[de-pos/VERB]() (2121; 43% instances), [de-pos/PROPN]()-[de-pos/VERB]() (229; 5% instances), [de-pos/PRON]()-[de-pos/VERB]() (76; 2% instances), [de-pos/ADJ]()-[de-pos/NOUN]() (54; 1% instances), [de-pos/ADP]()-[de-pos/VERB]() (32; 1% instances), [de-pos/NOUN]()-[de-pos/NOUN]() (28; 1% instances), [de-pos/ADJ]()-[de-pos/ADJ]() (23; 0% instances), [de-pos/ADV]()-[de-pos/VERB]() (22; 0% instances), [de-pos/NUM]()-[de-pos/VERB]() (19; 0% instances), [de-pos/PROPN]()-[de-pos/PROPN]() (19; 0% instances), [de-pos/VERB]()-[de-pos/VERB]() (18; 0% instances), [de-pos/NOUN]()-[de-pos/ADP]() (16; 0% instances), [de-pos/ADJ]()-[de-pos/ADP]() (6; 0% instances), [de-pos/ADJ]()-[de-pos/AUX]() (6; 0% instances), [de-pos/NOUN]()-[de-pos/NUM]() (6; 0% instances), [de-pos/ADJ]()-[de-pos/PRON]() (5; 0% instances), [de-pos/PROPN]()-[de-pos/ADP]() (5; 0% instances), [de-pos/X]()-[de-pos/VERB]() (5; 0% instances), [de-pos/NOUN]()-[de-pos/AUX]() (4; 0% instances), [de-pos/NOUN]()-[de-pos/ADJ]() (3; 0% instances), [de-pos/ADJ]()-[de-pos/X]() (2; 0% instances), [de-pos/ADP]()-[de-pos/ADJ]() (2; 0% instances), [de-pos/NOUN]()-[de-pos/PROPN]() (2; 0% instances), [de-pos/PROPN]()-[de-pos/ADJ]() (2; 0% instances), [de-pos/VERB]()-[de-pos/NOUN]() (2; 0% instances), [de-pos/ADJ]()-[de-pos/NUM]() (1; 0% instances), [de-pos/ADJ]()-[de-pos/PROPN]() (1; 0% instances), [de-pos/ADP]()-[de-pos/PROPN]() (1; 0% instances), [de-pos/NOUN]()-[de-pos/ADV]() (1; 0% instances), [de-pos/NOUN]()-[de-pos/PRON]() (1; 0% instances), [de-pos/NOUN]()-[de-pos/PUNCT]() (1; 0% instances), [de-pos/PRON]()-[de-pos/NOUN]() (1; 0% instances), [de-pos/PROPN]()-[de-pos/NOUN]() (1; 0% instances), [de-pos/PROPN]()-[de-pos/NUM]() (1; 0% instances), [de-pos/VERB]()-[de-pos/ADJ]() (1; 0% instances), [de-pos/VERB]()-[de-pos/AUX]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 cop	color:blue
1	Es	es	PRON	PPER	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	3	nsubj	_	_
2	ist	sein	VERB	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	cop	_	_
3	unbeschreiblich	unbeschreiblich	ADJ	ADJD	Degree=Pos	0	root	_	_
4	.	.	PUNCT	$.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 cop	color:blue
1	Manasse	Manasse	PROPN	NN	Case=Nom|Number=Sing	5	nsubj	_	_
2	ist	sein	VERB	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	cop	_	_
3	ein	ein	DET	ART	Definite=Ind|PronType=Art	5	det	_	_
4	einzigartiger	einzigartig	ADJ	ADJA	Degree=Cmp,Pos	5	amod	_	_
5	Parfümeur	Parfümeur	NOUN	NN	_	0	root	_	_
6	.	.	PUNCT	$.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 cop	color:blue
1	Ich	ich	PRON	PPER	Case=Nom|Number=Sing|Person=1|PronType=Prs	3	nsubj	_	_
2	bin	sein	VERB	VAFIN	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	3	cop	_	_
3	Schafflunder	Schafflunder	PROPN	NN	_	0	root	_	_
4	und	und	CONJ	KON	_	3	cc	_	_
5	übernachte	übernachten	NOUN	VVFIN	_	3	conj	_	_
6	selbst	selbst	ADV	ADV	_	5	advmod	_	_
7	nicht	nicht	PART	PTKNEG	_	5	neg	_	_
8	in	in	ADP	APPR	_	10	case	_	_
9	dem	der	DET	ART	Case=Dat|Definite=Def|Gender=Masc,Neut|Number=Sing|PronType=Art	10	det	_	_
10	Utspann	Utspann	PROPN	NN	Case=Dat|Gender=Masc,Neut|Number=Sing	5	nmod	_	_
11	.	.	PUNCT	$.	_	3	punct	_	_

~~~


