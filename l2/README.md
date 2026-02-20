get dataset
```sh
curl -Lo dataset.zip \
  https://www.kaggle.com/api/v1/datasets/download/kundanbedmutha/exam-score-prediction-dataset \
  && unzip dataset.zip \
  && rm dataset.zip
```

install kernel for notebook
```sh
. .venv/bin/activate
python -m ipykernel install --user --name l2 --display-name "Python (.venv l2)"
```