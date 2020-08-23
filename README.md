# genExam Source Code
## The basic idea
### Generation of Random test

Let us say that a you have 120 students in a classroom. Now, at the distance learning mode, giving those 120 student a exam papers so that any two exmas are exactly same. This is where the genExam can help. If you have a set of question lets say 10 and you need to make exam papers of any 3 question from this set of 10, total number of exlusive sets that can be created is 120. Now, if you have a class of 120 students, no two students will have the same paper. Now, if we put a little more effort and make 15 question, the total number of 3 questions sets that are generated will be 455. That's it, now the probability of any two students getting even two similar question is less. 

There is another question though, what is we want to have question from different chapters and within the paper the quetion carry different marks. No problem, we can set any difined rules at the begining and the code will make sure that exam papers are generated according the rules that you have set.

### How does it work!

Initially we need to feed seperate word file for question, cover paper, end page. Now, to generate all possible combinations, one just needs to specify how many questions each paper should have. In case, additional rules are to be applied, the source code can be changed easily. A few examples for exam papers with user defined rule are given.

## Running the code

The code can be eaily run on python by typing the command:
> python genExam.py

## Authors

# In case of any further information on the code or the use of it, please contact us at
- Swarit Dwivedi (dwivediswarit@gmail.com)
- Akshat Tanksale (Akshat.Tanksale@monash.edu)
