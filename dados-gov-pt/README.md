# dados.gov.pt open data portal

## Exploring datasets

Accessing/exploration of the datasets available in the Portuguese Governmental open data portal.

The jupyter notebook *localizacao_pontos_atendimento.ipynb* is meant to collect geographical data (location of public services) and to map it.

### Installing

For more convience, since the portal was developed from the uData engine, you will need to install the Open Data Team's udata-explorer:

```
git clone https://github.com/opendatateam/udata-explorer.git
cd udata-explorer
python3 -m venv pyenv
. pyenv/bin/activate
pip install -e .
```

## Acknowledgements

* Open Data Team: https://github.com/opendatateam/udata-explorer