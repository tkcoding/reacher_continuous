# Reacher environment for continuous action space
Train arm to intact with ball using continuous control with DDPG

Reward of agent with batch normalization at Critic network results in significant difference in terms of convergence and stability

![reward_norm](assets/rewards_withbatch.png)

Reward of agent without batch normalization at Critic network 

![reward_nonorm](assets/rewards_wobatch.png)


### Agent Weight 
* checkpoint_actor.pth - actor agent
* checkpoint_critic.pth - critic agent learnt through batch normalization
* checkpoint_critic_without_batchnormalization - critic agent learnt through without normalization
