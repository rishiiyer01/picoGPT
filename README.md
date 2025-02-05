# picoGPT
Taking some learnings from nanoGPT speedruns and applying experiments for educational purposes.
The main purpose of this repo is NOT to speedrun, but instead do small 8xH100 sized experiments to both learn and tinker with recent research. I encourage you to do some simple experiments with this repo, it was meant to be easily adaptable. For sampling/generation I left that up to preference, but I tend to make a separate class that wraps around the model I used to train.


Model.py/Train.py is a simple ~gpt2 sized language model with FlexAttention, Multi-latent Attention, 768 embed_dim, 12 layers, 12 heads



MoEmodel.py/MoEtrain.py is the same as above except with expert parallel MoEs replacing feedforwards (similar to deepseek v2,v3), 8 experts, topk=2

Full writeup and blogpost of initial experiments:
https://rishiiyer.com/writings/picogpt.html
