# Q_network
This repository is where I am putting my work learning about the classic Q_network and Deep_Q_network (DQN), as well as any improvements made on the DQN architecture. 

My goal is to improve the DQN algorithm to be able to learn how to play multiple games, and leverage previously learned environments to solve new environments. I don't know if I will be successful in this challenge, but it is worth trying. If I am successful, you will see my success in subsequent creations, but it will probably be a while. 


My first commit is the classic Q network (Taxi-v3_Q_net). Training this network takes less than a minute, honestly only a few second, which is fantastic. It makes sense since the game has a small amount of possible states to record in the Q table. 

The next commit will be the deep Q network. I have not uploaded it yet because it is still training using the google colab GPU. I predict it will take a total of 100 hours to train. The game is the same taxi game used in my first commit, but training takes forever because of how the DQN architecture works. If we can leverage previously seen game environments to train on a new game environment, I predict it would speed up training, which is why I want to work on doing that. The weight values of the DQN are analogous to our memories so if we can use a pretrained agent with weights learned on simmilar games then it should be able to leverage those pretrained weights to learn the new environment with less episodes, less times playing the game. If I do manage to get this to work, I hope to publish an article about it and probably upload the code here.

Wish me luck.
