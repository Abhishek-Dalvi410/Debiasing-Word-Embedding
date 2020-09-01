# Debiasing-Word-Embedding

*This is just a visualization of biased and debiased word embeddings on tensorboard Embedding Projector using https://github.com/tolga-b/debiaswe*

**Man is to computer programmer as woman is to homemaker? debiasing word embeddings**
_**-T Bolukbasi, KW Chang, JY Zou, V Saligrama, AT Kalai - Advances in neural information processing systems, 2016**_

Commands to visualize:-
1. tensorboard --logdir runs/biased
2. tensorboard --logdir runs/debiased --port=8080
3. cd into the website directory
4. python -m http.server
5. See the results on the web browser on localhost and port number on which http.server is running.
