# Installation
```
git clone https://github.com/NatsumiKubo/operator.git
cd operator
conda env create -f env.yaml
conda activate py37
```

# Excel to json
```
jupyter notebook
python excel2json.py
```

# Upload json to hubot
```
docker cp result.json hubot:/home/hubot/scripts/
docker cp example.coffee hubot:/home/hubot/scripts/example.coffee
docker restart hubot
```
