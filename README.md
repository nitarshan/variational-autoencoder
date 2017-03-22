Installation
------------

```bash
virtualenv venv
source venv/bin/activate
# Install appropriate PyTorch package for your distro from pytorch.org
pip install http://download.pytorch.org/whl/torch-0.1.10.post1-cp36-cp36m-macosx_10_7_x86_64.whl
pip install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
jupyter notebook
```
