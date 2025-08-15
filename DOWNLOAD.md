Dataset **ZhangLabData: Chest X-Ray** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMzIyNl9aaGFuZ0xhYkRhdGE6IENoZXN0IFgtUmF5L3poYW5nbGFiZGF0YS1jaGVzdC14cmF5LURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogInZmeG5UZmlVOXZ2K2lTWVNWdlpPZDlTaG1nSmo0NVhoRTN4MWRLbmpYZUU9In0=?response-content-disposition=attachment%3B%20filename%3D%22zhanglabdata-chest-xray-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='ZhangLabData: Chest X-Ray', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://prod-dcd-datasets-cache-zipfiles.s3.eu-west-1.amazonaws.com/rscbjbr9sj-3.zip).