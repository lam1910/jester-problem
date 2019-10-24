# Jester Datasets

## from [Jester](http://eigentaste.berkeley.edu/dataset/)

### credits to Jester 5.0 Project Team of UC Berkeley

**About the format for each file:**

- 3 Data files contain anonymous ratings data from 73,421 users.

- Data files are in .zip format, when unzipped, they are in Excel (.xls) format

- Ratings are real values ranging from -10.00 to +10.00 (the value "99" corresponds to "null" = "not rated").

- One row per user

- The first column gives the number of jokes rated by that user. The next 100 columns give the ratings for jokes 01 - 100.

- The sub-matrix including only columns {5, 7, 8, 13, 15, 16, 17, 18, 19, 20} is dense. Almost all users have rated those jokes (see discussion of "universal queries" in the above paper).

