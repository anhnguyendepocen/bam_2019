# Home assignment 2

Your task is to read though Chapter 2 of *Statistical Rethinking* (without section 2.4), and the introduction to chapter 3 (pp. 49-52). This will help you, if you find Bayes theorem not intuitive.

Afterward, solve the following problem.
1. You have a test that correctly detects vampirism 95% of the time, if given to a vampire, i.e. P(positive | vampire) = .95.
2. The test does make mistakes: If given to a human, 10% of the time it will return positive result, i.e. P(positive | human) = .10. Furthermore, if given to a werewolf, 50% of the time it will also return positive result, P(positive | werewolf) = .50.
3. You know that in the total population vampires are rare, i.e. there is only 1 in 100 individuals (P(vampire) = .01). Werewolves are also rare, but the chance of meeting one is slightly higher that the chance of meeting a vampire, i.e. P(werewolf) = .04. The remaining are humans, P(human) = .95.
4. Given that you conducted a test which returned a positive result, what is the change that the individual you test is a vampire, a werewolf, or a human. In other words, find:
  - P(vampire | positive)
  - P(werewolf | positive)
  - P(human | positive)

5. Show your results using `ggplot2`. In other words, create a data.frame with the following code:

```
categoriesP = c("vampire", "werewolf","human")
probability = c(...      , ...       , ...   )
data = data.frame(categories, probability)
```
Put the computed probabilities associated with being a vampire, werewolf, or human in respective places denoted by `...`. Afterward, plot the results with `ggplot2` (perhaps `geom_col()` will do the best job).

* In your homework include both your calculations, the code that you used, and the plot.
* You can do this task in pairs or triads.

**Deadline: 4.11.2019**
