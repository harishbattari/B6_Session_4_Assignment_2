# B6_Session_4_Assignment_2

1.x <- c(â€˜data.science.in.Râ€™, â€˜machine.learning.in.Râ€™)
Perform the below string Operation:
â€¢ Replace the period character "." within each string with another character i.e. "-" minus sign.
2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
â€¢ Append again with â€œ-â€œ minus sign character at the start of the each string and finally concatenate all the string within the vector to form a final single string and assigning it the object.

Ans:-
1.      x <- c(â€˜data.science.in.Râ€™, â€˜machine.learning.in.Râ€™)
Perform the below string Operation:
â€¢ Replace the period character "." within each string with another character i.e. "-" minus sign.
 Gsub(â€˜\\.â€™, â€˜-â€˜, x) or gsub(â€˜[.]â€™, â€˜-â€˜, x)
2. x <- c('data.science.in.R','machine.learning.in.R')
Perform the below String Operation:
â€¢ Append again with â€œ-â€œ minus sign character at the start of the each string and finally concatenate all the string within the vector to form a final single string and assigning it the object.
#Replaces .with minus
gsub('[.]','-',x)
gsub('\\.','-',x)
# paste two strings in a vector
x_1<-paste('-',x)
paste(x_1[1],x_1[2]) #without space
paste0(x_1[1],x_1[2]) #with space



