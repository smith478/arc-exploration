# arc exploration
Playing with techniques used in the [arc challenge](https://lab42.global/arc/).

## Program synthesis

One interesting approach to the arc challenge is to have an LLM generate a number of programs that may solve problems. Here is a [blog](https://redwoodresearch.substack.com/p/getting-50-sota-on-arc-agi-with-gpt) post describing one such example from Ryan Greenblatt.

### Text classification

We will download the [Reuters dataset](https://kdd.ics.uci.edu/databases/reuters21578/reuters21578.html) with topic classifications and attempt to use program synthesis to get classification without explicit training, but rather giving an outline of the problem with a few examples and ask an LLM to generate a function to solve the problem. 

