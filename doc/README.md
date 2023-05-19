# Side notes

## Possible improvements

Our solution uses an attention-based pooling method to weight tiles. Using attention scores, we could analyse which tiles triggered the attention module the most. Doing so we could find :

* Potential bias in our model
* Interesting patterns we could use to further improve the model and iterate
* Add some explainability to the model

## Next steps

Note that this project was a 3-day sprint. Our only goal was maximizing the performance metric.

With more time, we would have considered moving the code to containerize our code :

- [ ] Moving from notebook to python files
- [ ] Add a main.py to launch from CLI
- [ ] Add Dockerfile for easier reuse
