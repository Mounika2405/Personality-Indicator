# Personality-Indicator
The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

 * Introversion (I) – Extroversion (E)
 * Intuition (N) – Sensing (S)
 * Thinking (T) – Feeling (F)
 * Judging (J) – Perceiving (P)

This dataset contains over 8600 rows of data, on each row is a person’s:

 * Type (This persons 4 letter MBTI code/type)
 * A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))
 Data Source : https://www.kaggle.com/datasnaek/mbti-type/data
 
 Following are my major contributions to the project:

 * Extracted descriptions from valid URLs using Beautiful Soup (a library in Python).
 * Handled misspelled and slang words in the text using SpaCy.
 * Determined the personality types of individuals with their given posts using multi target text classification and checked for the          validity of the original tool.

