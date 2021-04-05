# WWCode Data Science: NLP Fuzzy Match Algorithms

Fuzzy string matching is technique to find strings which have approximate matches. 
There are multiple applications of fuzzy matching. 
This talk will cover a few algorithms which are implemented for such approximate string matchings.

<br> 

## Outline of the talk:    

- Introduction to fuzzy matching
- Applications of fuzzy matching
- Algorithms used for fuzzy matching
    - Levenshtein distance algorithm
    - Damerau-Levenshtein distance algorithm
    - Bitmap algorithm 
    - n-gram algorithm
- Implementation of fuzzy matching on real data
- Other fuzzy matching algorithms

<br>

### Implementation on Real Data

Download data [here from Kaggle](https://www.kaggle.com/leandrodoze/room-type).

The data contains two columns for room type descriptions. Column 1 is the description from Expedia, and column 2 is the associated room type in Booking.com.

<u> **Aim:**</u> is to compare and match these two columns and the result would be 'human like understanding that the matched entries are same'.

Snapshot of the data:

![image](https://user-images.githubusercontent.com/31106009/113615144-7f5fbd00-9621-11eb-8beb-b4ede994d464.png)

<br>

## Libraries used:
- Jellyfish: Refer [here](https://pypi.org/project/jellyfish/) for more information
- Fuzzywuzzy: Refer [here](https://pypi.org/project/fuzzywuzzy/) for more information
- Fuzzy_match: Refer [here](https://pypi.org/project/fuzzy-match/) for more information


## References:
1. [Levenshtein, Vladimir I. "Binary codes capable of correcting deletions, insertions, and reversals." In Soviet physics doklady, vol. 10, no. 8, pp. 707-710. 1966.](https://nymity.ch/sybilhunting/pdf/Levenshtein1966a.pdf)
2. [Damerau, Fred J. "A technique for computer detection and correction of spelling errors." Communications of the ACM 7, no. 3 (1964): 171-176.](https://dl.acm.org/doi/abs/10.1145/363958.363994)
3. [Cayrol, M., Farreny, H. and Prade, H. (1982), 'Fuzzy Pattern Matching', Kybernetes, Vol. 11 No. 2, pp. 103-116.](https://doi.org/10.1108/eb005612)
4. [Ukkonen, Esko. "Algorithms for approximate string matching." Information and control 64, no. 1-3 (1985): 100-118.](https://reader.elsevier.com/reader/sd/pii/S0019995885800462?token=6B1FB04FFCA70F0F9A2AAB96C6311FAA5E93FFB7F1C1B4A75A61D72728A2B6A655B4944421AD983395F0B11AAB73F520&originRegion=us-east-1&originCreation=20210331153641)
5. [Geek for Geeks - applications of fuzzy string matching](https://www.geeksforgeeks.org/applications-of-string-matching-algorithms/)
6. [Geek for Geeks - Bitap Algorithm](https://www.geeksforgeeks.org/java-program-to-implement-bitap-algorithm-for-string-matching/)
7. [Stanford slides on n-gram](https://web.stanford.edu/~jurafsky/slp3/slides/LM_4.pdf)
8. [Data camp tutorial - fuzzy string matching](https://www.datacamp.com/community/tutorials/fuzzy-string-python)
9. [Levenshtein distance theory](https://www.python-course.eu/levenshtein_distance.php)
10. [Article on record linking and fuzzy matching](https://pbpython.com/record-linking.html)
11. [Medium post on Levenshtein distance](https://blog.paperspace.com/measuring-text-similarity-using-levenshtein-distance/)
12. https://www.rosette.com/blog/overview-fuzzy-name-matching-techniques/

Feel free to reach out if you have any questions.
