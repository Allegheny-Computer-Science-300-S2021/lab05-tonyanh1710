#### Name: Anh Tran
#### Date: 29 March 2021
#### What this is: Questions in blue from the assignment sheet.

#### Part 1.


 1. Which software did you use to conduct your analysis?

- I use the Interactive demo for Needleman-Wunsch algorithm website to conduct the
 analysis. However, in order to do so, I had to open the Fasta file using the
 BioPython. Once I manage to read these two Fasta file, I copied and paste these
 sequences into each of comparing box. From there, it conducted a result table of
 Needleman-Wunsch global alignment.

 2. How similar were the two sequences (`s1.fasta` and `s2.fasta`) which you applied an alignment program?

- When apply an alignment program for two sequences, I can see that there some
similarity among these sequences. First of all, these sequences all share the
same length and they all start with `ATTT`. Secondly, both sequences all share
similar nucleotide bases, which determine whether there is a common ancestor in
these sequences.

 3. Are the two sequences closely related to each other, in your opinion?

- These sequences are seem to be closely related to each other.

 4. What proof do you have to suggest such a claim?


-  When examining in Needleman-Wunsch's Global Alignment algorithm, we can see
that these sequences share more numbers of matches than numbers of mismatches.
Particularly, there are 9 matches total founded in the sequence alignment, While
the number of mismatches is only seven. Not only that, there is only two gaps
founded between the two sequences, which suggest that these sequences can be closely
related. When there is a large gaps founded in a sequence alignment, we can see
that some bases in these sequences are not the same, which some insert or deletion
could be caused.



#### Part 2
 1. How much similarity exists between each of the sequences to the others?

- For the pair of `Influenza A Chicken Vietnam2005 avianH5N1 segment4` and `Influenza avianHong Kong2007 avianH5N1 segment4`, the similarity between the two are 95.2%.
Next, for the pair of `Influenza A Chicken Vietnam2005 avianH5N1 segment4` and
`Influenza avianHong Kong2007 avianH5N1 segment4`, the similarity is higher compared
to the former pair, which is about 96%. Finally, the pair between `Influenza A Chicken Vietnam2005 avianH5N1 segment4` and `Influenza avianHong Kong2007 avianH5N1 segment4`
share the highest similarity rate, which is about 97.5%. Therefore, the third pair
are closely related compared to the other two, due to the similarity in climate,
environment human's lifestyle, and even culture between China and Hong Kong.

 2. Based on your results so far (which are too few to provide a comprehensive study), do you believe there is evidence that human adaptation is occurring in H5N1 viruses that might merit concern about human-to-human transmission in the near future?

- Based on my results so far, I can assume that there could be some evidence suggesting
that human adaption is occurring in H5N1 viruses that might merit concern about
human-to-human transmission in the near future. For one thing, viruses that like
SARS-CoV-2 could produce many types of variants, which these variants could develop
different characteristics based on the environment of the place where it spreads.
When people travel from one place to another, they could carry the viruses to where
they travel. During the time when people are residing, the viruses will find its
way to adapt the environment that it is living. From there, these viruses will
develop into different variants, which carry some unique features while still
sharing some similarities with the original virus whom was firstly reported.
With viruses like H5N1, researchers and health expertise should therefore pay more
attention to human-to-human transmission such as traveling, because these actions
could contribute to further development of that type of viruses into many new
variants that are related to them.

 3. Statistics: What were the numbers of Lengths, Similarities, Gaps and Scores for each of your alignment tasks?

- For the first pair (A_China_GD01_2006_ and Vietnam2005):

```
#=======================================
#
# Aligned_sequences: 2
# 1: A_chicken_Viet_Nam_10_2005_(H5N1)_segment_4
# 2: A_China_GD01_2006_(H5N1)_segment_4
# Matrix: EDNAFULL
# Gap_penalty: 10.0
# Extend_penalty: 0.5
#
# Length: 1776
# Identity:    1690/1776 (95.2%)
# Similarity:  1690/1776 (95.2%)
# Gaps:          45/1776 ( 2.5%)
# Score: 8286.0
#
#
#=======================================
```

- For the second pair (HongKong2007 and Vietnam2005):
```
#=======================================
#
# Aligned_sequences: 2
# 1: A_chicken_Viet_Nam_10_2005_(H5N1)_segment_4
# 2: A_avian_Hong_Kong_719_2007_(H5N1)_segment_4
# Matrix: EDNAFULL
# Gap_penalty: 10.0
# Extend_penalty: 0.5
#
# Length: 1751
# Identity:    1681/1751 (96.0%)
# Similarity:  1681/1751 (96.0%)
# Gaps:          20/1751 ( 1.1%)
# Score: 8205.0
#
#
#=======================================

```

- For the third pair (A_China_GD01_2006_ and HongKong2007):

```
#=======================================
#
# Aligned_sequences: 2
# 1: A_China_GD01_2006_(H5N1)_segment_4
# 2: A_avian_Hong_Kong_719_2007_(H5N1)_segment_4
# Matrix: EDNAFULL
# Gap_penalty: 10.0
# Extend_penalty: 0.5
#
# Length: 1776
# Identity:    1731/1776 (97.5%)
# Similarity:  1731/1776 (97.5%)
# Gaps:          25/1776 ( 1.4%)
# Score: 8575.0
#
#
#=======================================
```

(Did you remember to add your name to this Markdown file?)
