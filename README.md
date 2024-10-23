Labo Machine-État 1 --> lien [ici](https://colab.research.google.com/drive/1DQwYecQrYvq6OLtB1I8Qdnta9HG80Di3?usp=sharing)

Listez les états ? Listez les événements ?
Quel événement pourrait-on ajouter ?

Labo Machine-État 2 --> 

1) Illustrer une machine d'état qui permet de parser if(a==b)
![if(a==b)](https://github.com/user-attachments/assets/c9b5b376-bf83-4466-8f99-5a26382cb74d)



2) Ajoute la reconnaissance de if(false)

3) Ajouter une tolérance à la syntaxe if(0)

Placer les images de vos machines d'état dans github, les faire afficher dans le readme et les expliquer.
Expliquer comment améliorer le programme en tolérant des espaces



Labo Sortie du Nid -->  lien du projet [ici](https://github.com/simonlesly/Labo_Agent_Machine_Etat/tree/main/Hummingbirds)


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


