# emojis_for_abusive_language_detection

This package contains supplementary notes and the new resources created for the paper "Exploiting Emojis for Abusive Language Detection".

There are two subdirectories:

# *subdirectory: Lexicons*
This subdirectory contains the resources regarding our lexicon induction experiments.

abusive.lexicon.emojibased.english.txt: This is the English lexicon of abusive words induced with the help of emojis.

abusive.lexicon.emojibased.german.txt: This is the German lexicon of abusive words induced with the help of emojis.
Note that the German lexicon is twice as large as the English and Portuguese lexicon. This reflects the fact that German, due to its large amount of (noun) compounds, has a much larger vocabulary (compare the size of the English and German vocabulary files). 

abusive.lexicon.naacl2018replicated.german.txt: This is the German replication of the induction approach proposed by Wiegand et al. "Inducing a Lexicon of Abusive Words – a Feature-Based Approach" (i.e. resource-intensive approach).
Note that the English lexicon following that approach is included in the supplementary material of that work: https://github.com/uds-lsv/lexicon-of-abusive-words/blob/master/Lexicons/expandedLexicon.txt

abusive.lexicon.emojibased.portuguese.txt: This is the Portuguese lexicon of abusive words induced with the help of emojis.

vocabulary.negpolar.german.txt: This is the German vocabulary of negative polar expressions of which abusive words represent a proper subset. The German vocabulary is notably larger than the vocabulary of the other languages. This is due the high frequency of compounds. 

vocabulary.negpolar.portuguese.txt: This is the Portuguese vocabulary of negative polar expressions of which abusive words represent a proper subset.

Note that the English vocabulary of negative polar expressions is available in the supplementary material of Wiegand et al. "Inducing a Lexicon of Abusive Words – a Feature-Based Approach": https://github.com/uds-lsv/lexicon-of-abusive-words/blob/master/Lexicons/expandedLexicon.txt (This is the path to the "expanded lexicon"; that lexicon contains the entire vocabulary of negative polar expressions with negative polar expressions having a positive score being predicted as abusive and expressions having a negative score being predicted as non-abusive.)


# *subdirectory: Disambiguation*
This subdirectory contains the resources regarding the disambiguation experiments.

guidelinesFWord.pdf: This file represents the annotation guidelines the annotators from Prolific Academic were given to categorize tweets mentioning the word "fuck" into abusive and merely profane usages.

guidelinesBWord.pdf: This file represents the annotation guidelines the annotators from Prolific Academic were given to categorize tweets mentioning the word "bitch" into abusive and merely profane usages.

BWord: This subdirectory contains the gold standard data for disambiguating the the word "bitch". The file BWord/abuse.txt contains the tweets categorized as abusive usages by the majority of annotators; the file BWord/profane.txt contains the tweets categorized as profane by the majority of annotators.

FWord: This subdirectory contains the gold standard data for disambiguating the the word "fuck". The file FWord/abuse.txt contains the tweets categorized as abusive usages by the majority of annotators; the file FWord/profane.txt contains the tweets categorized as profane by the majority of annotators.


# *contact information*
Please direct any questions that you have about this software to Michael Wiegand at Alpen-Adria Universitaet Klagenfurt.

Michael Wiegand email: michael.wiegand@aau.at


# *reference*

M. Wiegand & J. Ruppenhofer: Exploiting Emojis for Abusive Language Detection, in EACL, 2021.