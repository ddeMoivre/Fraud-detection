Le but de ce mini projet est de detecter les fraudes dans les transactions financières à l'aide du language de programmation Python.


DONNEES : Il y a trois sources de données :

- data.csv qui contient l'ensemble des transactions étudiées. Les données à notre disposition sont le montant de la transaction (en €) et le type de transaction. Pour mieux comprendre à quoi correspond le type de transaction on peut se reporter au fichier type_transaction.txt.

- historique.csv qui contient les informations liées à l'historique de la transaction. Cette table contient les montants du panier moyen de l'utilisateur qui fait la transaction, ainsi que le nombre de transaction passées dans les 10 dernières heures. 
A NOTER que l'historique est incomplet, il existe des transactions dont on ne connaît pas l'historique. Il y a donc des valeurs manquantes.

- Le fichier fraude.csv contient l'information concernant les fraudes.



OBJECTIFS : A partir des fichers de test, test_data.csv, test_historique.csv, il faut prédire les fraudes. La métrique utilisée pour évaluer la performance sera l'aire sous la courbe ROC (https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html)

