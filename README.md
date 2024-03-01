# Reproducibility challenge
Network AI course project

## Code changes
ai_models.py modified version of userQuery function.

```
    try:
        ret = json.loads(json_string)
        print("correct json format")
    except json.JSONDecodeError:
        print("Incorrect json format")
        continue
    #ret = json.loads(json_string)
    if ret is None:
        continue
```

## Datasets

node10c1.json generated with the following command.

```
python3 mock_graph_data.py -n=10 -v=10 -c=1 -o=data/graph_data/node10c1.json

```

## Results

Separated folders for GPT3.5/GPT-4 generated logs and command line screenshots
