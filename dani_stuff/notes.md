
## Identify categorical variables
- When looking at native country stats, don't sort. M

## Ordinal encoder
- Instead of warning: ask on which of the columns we think ordinal encoding would be appropriate
  - none
  - actually for education, there was a nominal encoding for it (years of schooling), but we ditched it.
- Instead of telling them about clothing sizes, ask whether they can think of an ordinal coding system that is not in numbers
  - anything goes, but I would like to highlight 2 situations: one alphabetized and one not so much, e.g.:
    - Not alphabetized: clothing sizes: XS, S, M, L, XL, XXL
    - Alphabetized: US grading system: A, B, C, D, F
- Ask what they think would happen if we input XS,S,M,L,XL (or their own suggestion) as ordinal system
  - How to solve the issue? (Look in documentation; at the very top)

## Nominal encoding
- specifically call the encoder onehot, so that we can compare to ordinal
- Instead of sending education_onehot to a Dataframe, I can also show the Jupyter:Variables tab of my notebook?



