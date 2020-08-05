# Recommender Systems Project 2020 - Colloberative Filltering With Side Information
## File List
1. SVD_baseline - A notebook containing code for a GPU version of SVD,
    and it's description evaluation on the Movielens1m dataset.
2. CKE - A notebook containg all the relevent code to build and train a CKE models
3. CKE_SOTA - A notebook containing our improvements for the CKE model(BERT, Resnet)
4. prepere_recall_eval - assitense notebook to prepere data for calculation of the
    @k on Movielens1m
5. calc recall@k and MAP@k_v1.1 - assitense notebook to calculate @k scores for
    recommender systems

## Data and Models
Get all additional data from our [drive](https://drive.google.com/drive/folders/1sr4tUfyMHK1b5Ct3wGEBgNEW8_DHDlXH?usp=sharing
):

To run the models you will need to download both the models and the posters images.

Those can be found our drive. Poseters need to be placed in:
```
'./movielens1m/posters/data'
```
The models them self should be placed in:
```
'./models'
```

## Reuirements
```
matplotlib=3.2.2=0
matplotlib-base=3.2.2=py38h2af1d28_0
numpy=1.18.5=py38h8854b6b_0
numpy-base=1.18.5=py38h2f8d375_0
pandas=1.0.3=py38h0573a6f_0
pytorch=1.4.0=py3.8_cuda10.1.243_cudnn7.6.3_0
torchvision=0.5.0=py38_cu101
tqdm=4.48.0=pyh9f0ad1d_0
```