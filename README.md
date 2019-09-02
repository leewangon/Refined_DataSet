# Refined_DataSet
Refined Training and Test dataset for Knowledge Graph Model

## Dataset Description
```description01
    This repository contains refinement dataset to train and evaluate knowledge graph model.
    If you have any questions or comments, please fell free to contact us by email [leewangon@gmail.com].
```

## Data overview
```description02
    In this project, we eliminated triples about coordinates, time and dates.  
    In addition, ambiguous data related to the university's sports team were excluded.
```

## Data format
```description03
   This data is represented by a sequence of the following n-triple format.
   n-triple - a format for storing and transmitting data. 
            - a line-based, plain text serialisation format for RDF (Resource Description Framework) graphs.
            - a subset of the Turtle (Terse RDF Triple Language) format.
   <s, p, o>
   * s - subject
   * p - predicate
   * o - object
```  


## Statistics of dataset
|:-----------:|------------:|
| NELL-995 ||
|Size|26MB|
|Triples|308,426|
|Entities|75,492|
|Relations|400|
|Classes|292|

## The institute to construct dataset
 * __NELL-995 : http://rtw.ml.cmu.edu/rtw/__

## Citation
If our dataset is helpful, please kindly cite the following paper:
```description04
@inproceedings{
NELL-aaai15, 
Title = {Never-Ending Learning}, 
Author = {T. Mitchell and W. Cohen and E. Hruschka and P. Talukdar and J. Betteridge and A. Carlson and B. Dalvi and M. Gardner and B. Kisiel and J. Krishnamurthy and N. Lao and K. Mazaitis and T. Mohamed and N. Nakashole and E. Platanios and A. Ritter and M. Samadi and B. Settles and R. Wang and D. Wijaya and A. Gupta and X. Chen and A. Saparov and M. Greaves and J. Welling}, 
Booktitle = {Proceedings of the Twenty-Ninth AAAI Conference on Artificial Intelligence (AAAI-15)}, 
Year = {2015}
}
```

## Acknowledgement
 * 
