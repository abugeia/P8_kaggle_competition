# P8 Competition Kaggle : Optiver Realized Volatility Prediction

Ce projet présente une participation à la compétition Kaggle [Optiver Realized Volatility Prediction](https://www.kaggle.com/c/optiver-realized-volatility-prediction/overview)

Il est également visible sur [Kaggle](https://www.kaggle.com/antoinebugeia/p8-optiver-volatility-prediction)

## Installation

```bash
pip install -r requirements.txt
```

## Notice

Changer les variables en fonction de son environnement dans la celle 'Variables'
Exécuter le notebook.

Le notebook va ensuite préprocesser les données, puis tester plusieurs modèles avant de choisir le plus performant sur le jeu de train.  
Ce modèle servira à prédire la volatilité du jeu de test et celle ci sera extraite dans un fichier 'submission.csv'

## References

Ces Kernels m'ont particulièrement aidé dans ma participation :

[https://www.kaggle.com/alexioslyon/lgbm-baseline](https://www.kaggle.com/alexioslyon/lgbm-baseline)  
[https://www.kaggle.com/munumbutt/feature-engineering-tuned-xgboost-lgbm](https://www.kaggle.com/munumbutt/feature-engineering-tuned-xgboost-lgbm)

## Results


<img src="https://github.com/abugeia/P8_kaggle_competition/blob/master/img/kaggle_score.PNG" width="800px"/>
