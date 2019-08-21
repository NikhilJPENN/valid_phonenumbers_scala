# valid_phonenumbers_scala

The following scala program filters out the invalid phone number columns from spark dataframe and gives out valid phone columns.

The regex is used to compare/match the pattern of phone numbers. Each column is selected from orignal dataframe to check pattern.

The filter and rlike removes unmatched/null elements in the column. If the number original elements in the column is not equal to filtered column. Those columns are simply removed from the original data frame.
