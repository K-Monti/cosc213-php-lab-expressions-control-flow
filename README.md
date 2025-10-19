# cosc213-php-lab-expressions-control-flow

Explanations and sample outputs can be found in the subbmitted lab report along with the screenshots.


== is loose. === is strict
"Loose" typing means php will automatically interpret the values into types that can be compared together. For example, (1 == true) would return true. But with strict typing, it would return false.
Most of the time you'd want to exclusivly use === as it prevents unintended errors.

A scenario you might want to use == instead of === would be if you were taking input for a users age and wanted to have that input, which would come in as a string, satisfy an integer condition in your code.