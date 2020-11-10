## demo of virtual mono-repo
1. install STL repo, which contains commom component and interfaces

`$ pip install ./stl`

2. install fairseq and pytext demo repos

`$ pip install ./fairseq`

`$ pip install ./pytext`

3. import models from stl, fairseq or pytext

`>>> from stl.text.model.fairseq_model import FairseqModel`
`>>> str(FairseqModel())`

`>>> from stl.text.model.pytext_model import PyTextModel`
`>>> str(PyTextModel())`

