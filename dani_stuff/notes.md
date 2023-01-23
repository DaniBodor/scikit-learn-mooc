
## Identify categorical variables
- When looking at native country stats, don't sort. M

## Ordinal encoder
- Work on marital-status instead of on education (fewer categories, easier to see)
- At end of module: ask whether ordinal encoding is appropriate for marital status; then on which it would be
  - Only for education --> in fact, there was already a nominal encoding for it (years of schooling), but we ditched it.
- Ask for another example of an ordinal encoding system that is not in numbers
  - Anything goes, but I would like to highlight 2 situations: one alphabetized and one not, e.g.:
    - Alphabetized: US grading system: A, B, C, D, F
    - Not alphabetized: clothing sizes: XS, S, M, L, XL, XXL
- Ask what they think would happen if we input XS,S,M,L,XL (or their own suggestion) as ordinal system
  - How to solve the issue? (Look in documentation; at the very top)
    - Answer
      ```
      ordered_size_list = ['XS', 'S', 'M', 'L', 'XL', 'XXL']
      encoder_with_order = OrdinalEncoder(categories=ordered_size_list)
      ```


## Nominal encoding
- Specifically call the encoder onehot, so that we can compare to ordinal
- Instead of sending education_onehot to a Dataframe, I can also show the Jupyter:Variables tab of my notebook?



