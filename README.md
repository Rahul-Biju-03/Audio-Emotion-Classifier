# Audio-Emotion-Classifier
Analyzing the Perception and Production of Prosody in Depressed vs Non-Depressed using ML models

## Dataset

Participants who can speak both malayalam and English were selected.
132 Participants (Age group: 18-35)
Recordings were collected in a room with sufficient acoustics to provide a
relatively clean audio sample and saved in WAV format.
To protect the privacy of the participants, sensitive personal information is
cut before further analysis.
A total of 44 sentences ( 22 English, 22 Malayalam) were recorded from
each participant.
Sentences obtained from IViE Corpus are:

### Coordinations
- C1- Are you growing limes or lemons?
- C2- Is his name Miller or Mailer?
- C3- Did you say mellow or yellow?
- C4- Do you live in ealing or reading?
- C5- Did he say lino or lilo?

### Inversion Questions
- I1- May I lean on the railings?
- I2- May I leave the meal early?
- I3- Will you live in ealing?

### Questions without morphosyntactic markers
- M1- He is on the Lilo?
- M2- You remembered the lilies?
- M3- You live in ealing?

### Simple Sentences
- S1- We live in ealing.
- S2- You remembered the lilies.
- S3- We arrived in a limo.
- S4- They are on the railings.
- S5- We were in yellow.
- S6- He is on the lilo.
- S7- You are feeling mellow.
- S8- We were lying.

### WH Questions
- W1- Where is the manual?
- W2- When will you be in ealing?
- W3- Why are we in a limo?

## Excel Sheet

### Dataset
- Contains Audio_ID, Emphasized word and comments.
- Audio_ID is sorted by P1_S1_E, P1_S2_E, ....

### Dataset Sorted
- The dataset is sorted. 
- Contains Audio_ID, Emphasized word, comments and count of Emphasized words.
- Gives count of an emphasized word for al participants in total.
- Eg: Emphasised Count of live is 73, after checking all the English audios of 132 participants
- Audio_ID is sorted by P1_S1_E, P2_S1_E, ....

### Emphasised Word Count
- Shows count of an emphasized word for al participants in total in an easy manner.

### Analysis Count
- Analyses the type of each word of sentence and gives count of each word used.
- Eg: In the sentence S1 "We live in Ealing,":
  We is subject, live is verb/linking verb, in is preposition, and ealing is last word(mostly object).

### Non Questions
- Includes Audio_ID of all Questions without morphosyntactic markers

### Ivie Corpus
- 
- Our IviE Corpus is taken from Bradford, Cambridge and Belfast
- Both Male and Female recordings
- Terms used:  
whq - wh questions,
dec - simple sentences,
coo - coordinations,
dqu - w/o morphosyntactic markers,
yno - inversion questions,
c - cambridge,
b - Belfast,
p - Bradford,
m- male,
f- female
- Eg: f1 (ONLY 17 IN EXCEL SHEET, BUT ACTUALLY IT HAS TO BE 22)
   Coordinations: p-coo1-f1, p-coo2-f2, p-coo3-f3, p-coo4-f4, p-coo5-f5
   Simple sentences: p-dec1-f1, p-dec3-f1, p-dec6-f1, p-dec-8, b-dec5-f1
   Inversion questions: p-yno1-f1, b-yno3-f1
   Coordinations: c-coo1-f1, b-coo1-f1, b-coo4-f1
   W/O Morphosyntactic markers: c-dqu2-f1, b-dqu3-f1, 

### Vowel Sounds

These are the phonetic vowel sounds represented in the International Phonetic Alphabet (IPA). Some examples are:

- In the sentence S1 "We live in Ealing," there are 5 vowel sounds:

e in "we",
i in "live",
i in "live",
e in "Ealing",
a in "Ealing",


- In the sentence S2 "You remembered the lilies," there are 7 vowel sounds:

o in "you",
e in "you",
e in "remembered",
e in "remembered",
e in "remembered",
i in "lilies",
i in "lilies",


