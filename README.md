# Predict-the-Introverts-from-the-Extroverts

Objective is to predict whether a person is an Introvert or Extrovert, given their social behavior and personality traits.

```bash
uv init .
.venv\Scripts\activate.bat
set KAGGLE_USERNAME=<USERNAME>
set KAGGLE_KEY=<KEY>
kaggle competitions download -c playground-series-s5e7
mkdir data
tar -xf playground-series-s5e7.zip -C data
del playground-series-s5e7.zip
```
