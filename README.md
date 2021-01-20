# Named Entity Recognition

<!-- A deployable Named Entity Recognition tool (A team project for Aggregate Intellect's workshop in April, 2020). The team consisted of four members (including myself). -->

```bash
cd src/bert
make build
make run
# open localhost:5000
```

### Model
- spaCy as base model
- LSTMs/BERT as advanced model

### Packaging
- MLFlow with pyfunc

### Cloud platform
- Azure App Service for containers

### Dataset
- Wikigold
- BERT was pretrained on Wikigold with model cached on [S3](https://github.com/ditadi/ner/blob/master/src/bert/Dockerfile#L54)

<!--

### Devops
- [![Build Status](https://dev.azure.com/ditadi/ner/_apis/build/status/ditadi.ner?branchName=master)](https://dev.azure.com/ditadi/ner/_build/latest?definitionId=1&branchName=master)
- [Interactive Demo](https://bertmodel-ner.azurewebsites.net/)
- [NER on CNN Headlines](https://bertmodel-ner.azurewebsites.net/headlines)

https://www.youtube.com/watch?v=AKVMHytQZnI\&t=506s

-->
