# statistical-rethinking-notes

### Installation

```R
install.packages(c("mvtnorm","loo","coda"), repos="https://cloud.r-project.org/",dependencies=TRUE)
options(repos=c(getOption('repos'), rethinking='http://xcelab.net/R'))
install.packages('rethinking',type='source')
# If it errors and needs shape
install.packages('shape',type='source')
```
