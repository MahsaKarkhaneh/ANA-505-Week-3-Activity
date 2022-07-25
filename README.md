# ANA-505-Week-3-Activity

#Arguments is not required for getwd.
hw <- getwd()
setwd(dir=hw)
women
head(women,2)
str(women)
summary(women)  
mean(women$height)
install.packages(package="dplyr")
library(package="dplyr")
newwomen1 <- select(.data = women,c(2))
newwomen2 <- select(.data = women,c(1))
newwomen1
newwomen2
newwomen3 <- subset(women,height>65)
newwomen3
nrow(x=women)
ncol(x=women)
dim(x=women)
install.packages("ggplot2")
library(package="ggplot2")
ggplot(women, aes(x=height, y=weight)) + 
  geom_point()
ggplot(women, aes(x=height, y=weight)) + 
  geom_point(shape = 21, colour = "black", fill = "white", size = 5, stroke = 5)
  
  [New Text Document.txt](https://github.com/MahsaKarkhaneh/ANA-505-Week-3-Activity/files/9177825/New.Text.Document.txt)
