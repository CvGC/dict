# CvGC dict

<img align="left" src="https://avatars2.githubusercontent.com/u/20906737?v=3&s=200"> This is a dictionary project led by the CvGC (**C**ecmu lo **v**oi **G**asnu lo **C**umki).

The first phase will consist of reviewing, editing, adjusting and/or clarifying the definitions, notes, and related data of the Lojban root words, also known as *gismu*. (Subsequent projects may include doing the same for the cmavo.)

#### How to participate:

If you want to discuss a particular word, its definition, notes, or other related data:
  1. first do a search for an issue with the name of the word. If the issue already exists, use it for discussion. There will only be one thread (issue) per word.
  2. If no issue exists, create one and start a discussion.

Each word lives in a separate YAML file, and contains the following data:
* definition
* notes
* place types
* example sentences
* keywords
* glosses
* related words
* semantic fields
* frame
* arity

Here is an example entry, of the root word **zvati**:

```
zvati:
   definition:
      x1 is at x2.

   notes:
      Spatial equivalent of {cabna}. True of any two objects or events that spatially coincide, either temporarily or permanently. For permanent locations in particular, see {stuzi}.

   types:
      x1: object
      x2: object

   examples:
      - "do zvati ma":
           "Where are you?"
      - "mi zvati lo zarci":
           "I am at the market."
      - "xu su'o lo zvati cu banka'e lo .inglico":
           "Is anyone present who speaks English?"
      - "xu lo se zvati be lo nu do pu viska lo cribe cu zvada'o":
           "Is the place where you saw the bear far away?"

   keywords:
      - at
      - present
      - attending
      - there

   glosses:
      x1: present
      x2: place

   confer:
      synonyms:
         -
      antonym: 
      hypernym: 
      holonym: 

   fields:
      - location words

   frame: ZVATI

   arity: 2
```

The CvGC will attempt to create the best possible word list, which may involve various changes of the data along the way in accordance with the CvGC's ideals, which are, among others, consistency, logic, regularity, simplicity and beauty.

The CvGC aspires to bring the quality of the definitions and the related data fields to a high and publishable level.

*The CvGC is not a governing body and does not claim any official status to its views or documents published under its name.*
