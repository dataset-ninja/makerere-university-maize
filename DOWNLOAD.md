Dataset **Makerere University Maize** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMzODBfTWFrZXJlcmUgVW5pdmVyc2l0eSBNYWl6ZS9tYWtlcmVyZS11bml2ZXJzaXR5LW1haXplLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIml5YW44eDlOb2xRM2NFZUdxeGhaS2p0NncyMHR6NlpINU5KZ3NFSkl0dnM9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Makerere University Maize', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/LPGHKK#).