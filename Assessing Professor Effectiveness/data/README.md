Description of dataset:

The datafile rmpCapstoneNum.csv contains 89893 records. Each of these records (rows) corresponds to information about one professor.
  The columns represent the following information, in order:
  1: Average Rating (the arithmetic mean of all individual quality ratings of this professor)
  2: Average Difficulty (the arithmetic mean of all individual difficulty ratings of this professor)
  3: Number of ratings (simply the total number of ratings these averages are based on)
  4: Received a “pepper”? (Boolean - was this professor judged as “hot” by the students?)
  5: The proportion of students that said they would take the class again
  6: The number of ratings coming from online classes
  7: Male gender (Boolean – 1: determined with high confidence that professor is male)
  8: Female (Boolean – 1: determined with high confidence that professor is female)

There is a second datafile rmpCapstoneQual.csv that has the same number of 89893 records in the
same order, but only 3 columns containing qualitative information:
  Column 1: Major/Field
  Column 2: University
  Column 3: US State (2 letter abbreviation)

There is a third datafile rmpCapstoneTags.csv that has the same number of 89893 records in the same
order. It also has 20 columns. The numbers in these columns correspond to the raw number of “tags” a
professor has received. A student can award up to 3 such tags, but doesn’t have to award any. These
tags are supposed to characterize the teaching style of the professor qualitatively, beyond ratings. Here
is what the columns in this dataset represent:
  Column 1: “Tough grader”
  Column 2: “Good feedback”
  Column 3: “Respected”
  Column 4: “Lots to read”
  Column 5: “Participation matters”
  Column 6: “Don’t skip class or you will not pass”
  Column 7: “Lots of homework”
  Column 8: “Inspirational”
  Column 9: “Pop quizzes!”
  Column 10: “Accessible”
  Column 11: “So many papers”
  Column 12: “Clear grading”
  Column 13: “Hilarious”
  Column 14: “Test heavy”
  Column 15: “Graded by few things”
  Column 16: “Amazing lectures”
  Column 17: “Caring”
  Column 18: “Extra credit”
  Column 19: “Group projects”
  Column 20: “Lecture heavy”
