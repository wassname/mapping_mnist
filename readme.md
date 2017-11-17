MNIST is the hello world of machine learning. When we learn out optimizer moves through peaks and valleys. But how bumpy are those valleys and how many are there?

This project tries to map a slice of the MNIST classification problem. We reduce mnist to a binary problem: is the number > 5? 

- Then we pre-train a model
- freeze all but two parameters. We call those x and y. 
- Height, or z, is our loss. 
- Then we peform a grid search over x and y to find the loss at differen't points.
- finally we countour the landscape
- and show the path of our model as it learns 


![](docs/countours.png)


TODO

- [ ] run a finer grid
- [ ] show path of a model as it learns
- [ ] make gif
