# picoGPT
taking some learnings from nanoGPT speedruns and applying experiments


Model.py/Train.py is a simple ~gpt2 sized language model with FlexAttention, Multi-latent Attention, 768 embed_dim, 12 layers, 12 heads



MoEmodel.py/MoEtrain.py is the same as above except with MoEs replacing feedforwards (similar to deepseek v2,v3)
