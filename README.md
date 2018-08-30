# explore_some_functional_datasets
explore some functional datasets

```
library(fda)
data("StatSciChinese")
amat<-StatSciChinese[,1,]
plot(amat[,1],amat[,2],type="l")
for(ii in 2:20){
  amat<-StatSciChinese[,ii,]
  lines(amat[,1],amat[,2],type="l")
}
```
