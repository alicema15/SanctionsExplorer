# SanctionsExplorer
https://sanctionsexplorer.org

SanctionsExplorer is an improved version of the [OFAC SDN website](https://sanctionssearch.ofac.treas.gov).  For more details, visit our [About page](https://sanctionsexplorer.org/about).


# notes:
- disabled sentry sdk
- uncommented all parts related to exporting to elastic search
- installed packages with pip not pip3; includes `pip install feedparser` and `pip install sentry_sdk`
- created empty requirements.txt file, no content in it yet
- created empty credentials.py file

# to grab sdn data
```cp -v SanctionsExplorer/data/update_files/sdn.json data-loader/sdn/sdn.json```
