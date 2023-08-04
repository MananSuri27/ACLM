## 💽 Data Guide
### Structure
Each of the folders here represent the size of the dataset. We run ACLM under data constrained conditions to highlight the performance gain brought forth with ACLM.

The data in the files follows the CONLL format. The data is structured in a BIO notation:

#### BIO Notation

BIO format, also known as IOB (Inside-Outside-Beginning), is a common data representation format used in Named Entity Recognition (NER) and other sequence labeling tasks. The purpose of the BIO format is to label each token in a sentence with a tag that indicates whether the token is the beginning (B), inside (I), or outside (O) of a named entity. 

In the BIO format:

B-XXX represents the beginning of an entity of type XXX.
I-XXX represents a token inside an entity of type XXX.
O represents a token outside of any named entity.
The BIO format is designed to handle multi-word named entities in a way that is clear and unambiguous. It allows for the identification of the entity type and the boundaries of each entity in the sentence.

##### Example:
```
ease	B-CW
on	I-CW
down	I-CW
the	I-CW
road	I-CW
—	O
charlie	B-PER
smalls	I-PER
(	O
diana	B-PER
ross	I-PER
and	O
michael	B-PER
jackson	I-PER
in	O
the	B-CW
wiz	I-CW
)	O
```
### Languages
Languages in the data and their keys:

| Language   | BART Language Key | Dataset Language Key |
|------------|-------------------|----------------------|
| German     | de_DE             | de                   |
| English    | en_XX             | en                   |
| Spanish    | es_XX             | es                   |
| Hindi      | hi_IN             | hi                   |
| Korean     | ko_KR             | ko                   |
| Dutch      | nl_XX             | nl                   |
| Russian    | ru_RU             | ru                   |
| Turkish    | tr_TR             | tr                   |
| Chinese    | zh_CN             | zh                   |
| Bengali    | bn_IN             | bn                   |
