Labo Machine-État 1 --> lien [ici](https://colab.research.google.com/drive/1DQwYecQrYvq6OLtB1I8Qdnta9HG80Di3?usp=sharing)

Listez les états ? il y a trois états : bien, peur et faim \
Listez les événements ? il y a quatre événements  : recevoir_nourriture, ennemi_arrive, ami_arrive et ennemi_quitte\
Quel événement pourrait-on ajouter ? On pourrait ajouter un événement "jouer". Si ami est là ou que le Tamagotchi est bien, il joue.


Labo Machine-État 2 --> 

1) Illustrer une machine d'état qui permet de parser if(a==b)
![if(a==b)](https://github.com/user-attachments/assets/c9b5b376-bf83-4466-8f99-5a26382cb74d)


2) Ajoute la reconnaissance de if(false) 
![machine-etat2](https://github.com/user-attachments/assets/16d40c50-d649-445c-b216-61689c4d44a4)


Labo Sortie du Nid -->  lien du projet [ici](https://github.com/simonlesly/Labo_Agent_Machine_Etat/tree/main/Hummingbirds)


- lien résultat -->  [ici]()


Training :
![training1](https://github.com/user-attachments/assets/2a65cebd-0afc-4628-b1fe-fd35a3869ca5)


Tensorboard :
![tensordboard](https://github.com/user-attachments/assets/0e45cbe2-97cc-47e3-b1d0-a7b27fda5037)




Labo Data Log -->

- Une famille de 3 enfant avec une mère et un père
- Un enfant A porte un foulard rouge
- Un enfant B porte un foulard bleu
- Un enfant C porte un foulard bleu
- La mère porte le même foulard que A


Expression du  problème :

                          parent(mere,enfantA).
                          parent(mere,enfantB).
                          parent(mere,enfantC).
                          
                          foulardColor(enfantA,rouge).
                          foulardColor(enfantB,bleu).
                          foulardColor(enfantC,bleu).
                          
                          (parent(X,Y)  & foulardColor(Y,Z)) => MotherColor(X,Z).
                          MotherColor(X,Y) => ChildColor(Y,X).
                          
                          MotherColor(X,rouge) => $ans(X).


