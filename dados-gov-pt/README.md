# dados.gov.pt open data portal

## Exploring datasets

Accessing/exploration of the datasets available in the Portuguese Governmental open data portal.

The jupyter notebook *localizacao_pontos_atendimento_ap.ipynb* is meant to collect geographical data (location of public services) and to map it.

The jupyter notebook *api-demos-dados-gov.ipynb* shows some examples on how to use the portal's API.

### Installing

To run the *localizacao_pontos_atendimento_ap.ipynb* notebook, you will need to install the Open Data Team's udata-explorer:

```
git clone https://github.com/opendatateam/udata-explorer.git
cd udata-explorer
python3 -m venv pyenv
. pyenv/bin/activate
pip install -e .
```

## Acknowledgements

* Open Data Team: https://github.com/opendatateam/udata-explorer