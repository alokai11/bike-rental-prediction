(base) @aakashvardhan ➜ /workspaces/bike-rental-prediction (main) $ conda activate iisc-miniproject
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction (main) $ ls
 LICENSE   M6_MP1_PartA_Instructions.pdf  'ReadMe - Module 06 - Mini-Project_1_PartA.pdf'   bikeshare_project
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction (main) $ cd bikeshare_project/
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ ls
MANIFEST.in  bike_sharing_api  bikeshare_model  mypy.ini  pyproject.toml  requirements  setup.py  tests
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ pip install -r requirements/requirements.txt 
Collecting joblib==1.4.2 (from -r requirements/requirements.txt (line 1))
  Downloading joblib-1.4.2-py3-none-any.whl.metadata (5.4 kB)
Collecting numpy==2.2.2 (from -r requirements/requirements.txt (line 2))
  Downloading numpy-2.2.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (62 kB)
Collecting pandas==2.2.3 (from -r requirements/requirements.txt (line 3))
  Downloading pandas-2.2.3-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (89 kB)
Collecting pydantic==2.10.5 (from -r requirements/requirements.txt (line 4))
  Downloading pydantic-2.10.5-py3-none-any.whl.metadata (30 kB)
Collecting ruamel.yaml==0.18.10 (from -r requirements/requirements.txt (line 5))
  Downloading ruamel.yaml-0.18.10-py3-none-any.whl.metadata (23 kB)
Collecting scikit-learn==1.6.1 (from -r requirements/requirements.txt (line 6))
  Downloading scikit_learn-1.6.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (18 kB)
Collecting strictyaml==1.7.3 (from -r requirements/requirements.txt (line 7))
  Downloading strictyaml-1.7.3-py3-none-any.whl.metadata (11 kB)
Collecting python-dateutil>=2.8.2 (from pandas==2.2.3->-r requirements/requirements.txt (line 3))
  Downloading python_dateutil-2.9.0.post0-py2.py3-none-any.whl.metadata (8.4 kB)
Collecting pytz>=2020.1 (from pandas==2.2.3->-r requirements/requirements.txt (line 3))
  Downloading pytz-2025.1-py2.py3-none-any.whl.metadata (22 kB)
Collecting tzdata>=2022.7 (from pandas==2.2.3->-r requirements/requirements.txt (line 3))
  Downloading tzdata-2025.1-py2.py3-none-any.whl.metadata (1.4 kB)
Collecting annotated-types>=0.6.0 (from pydantic==2.10.5->-r requirements/requirements.txt (line 4))
  Downloading annotated_types-0.7.0-py3-none-any.whl.metadata (15 kB)
Collecting pydantic-core==2.27.2 (from pydantic==2.10.5->-r requirements/requirements.txt (line 4))
  Downloading pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (6.6 kB)
Collecting typing-extensions>=4.12.2 (from pydantic==2.10.5->-r requirements/requirements.txt (line 4))
  Downloading typing_extensions-4.12.2-py3-none-any.whl.metadata (3.0 kB)
Collecting ruamel.yaml.clib>=0.2.7 (from ruamel.yaml==0.18.10->-r requirements/requirements.txt (line 5))
  Downloading ruamel.yaml.clib-0.2.12-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (2.7 kB)
Collecting scipy>=1.6.0 (from scikit-learn==1.6.1->-r requirements/requirements.txt (line 6))
  Downloading scipy-1.15.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (61 kB)
Collecting threadpoolctl>=3.1.0 (from scikit-learn==1.6.1->-r requirements/requirements.txt (line 6))
  Downloading threadpoolctl-3.6.0-py3-none-any.whl.metadata (13 kB)
Collecting six>=1.5 (from python-dateutil>=2.8.2->pandas==2.2.3->-r requirements/requirements.txt (line 3))
  Downloading six-1.17.0-py2.py3-none-any.whl.metadata (1.7 kB)
Downloading joblib-1.4.2-py3-none-any.whl (301 kB)
Downloading numpy-2.2.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (16.4 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 16.4/16.4 MB 54.6 MB/s eta 0:00:00
Downloading pandas-2.2.3-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (13.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 13.1/13.1 MB 59.7 MB/s eta 0:00:00
Downloading pydantic-2.10.5-py3-none-any.whl (431 kB)
Downloading ruamel.yaml-0.18.10-py3-none-any.whl (117 kB)
Downloading scikit_learn-1.6.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (13.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 13.5/13.5 MB 58.7 MB/s eta 0:00:00
Downloading strictyaml-1.7.3-py3-none-any.whl (123 kB)
Downloading pydantic_core-2.27.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.0/2.0 MB 47.1 MB/s eta 0:00:00
Downloading annotated_types-0.7.0-py3-none-any.whl (13 kB)
Downloading python_dateutil-2.9.0.post0-py2.py3-none-any.whl (229 kB)
Downloading pytz-2025.1-py2.py3-none-any.whl (507 kB)
Downloading ruamel.yaml.clib-0.2.12-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (739 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 739.1/739.1 kB 30.8 MB/s eta 0:00:00
Downloading scipy-1.15.2-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (37.6 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 37.6/37.6 MB 58.4 MB/s eta 0:00:00
Downloading threadpoolctl-3.6.0-py3-none-any.whl (18 kB)
Downloading typing_extensions-4.12.2-py3-none-any.whl (37 kB)
Downloading tzdata-2025.1-py2.py3-none-any.whl (346 kB)
Downloading six-1.17.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: pytz, tzdata, typing-extensions, threadpoolctl, six, ruamel.yaml.clib, numpy, joblib, annotated-types, scipy, ruamel.yaml, python-dateutil, pydantic-core, strictyaml, scikit-learn, pydantic, pandas
Successfully installed annotated-types-0.7.0 joblib-1.4.2 numpy-2.2.2 pandas-2.2.3 pydantic-2.10.5 pydantic-core-2.27.2 python-dateutil-2.9.0.post0 pytz-2025.1 ruamel.yaml-0.18.10 ruamel.yaml.clib-0.2.12 scikit-learn-1.6.1 scipy-1.15.2 six-1.17.0 strictyaml-1.7.3 threadpoolctl-3.6.0 typing-extensions-4.12.2 tzdata-2025.1
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ ls
MANIFEST.in  bike_sharing_api  bikeshare_model  mypy.ini  pyproject.toml  requirements  setup.py  tests
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ python bikeshare_model/
/opt/conda/envs/iisc-miniproject/bin/python: can't find '__main__' module in '/workspaces/bike-rental-prediction/bikeshare_project/bikeshare_model/'
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ python bikeshare_model/train_pipeline.py 
R2 score: 0.92
Mean squared error: 2716.920428209541
Model/pipeline saved successfully.
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ pip install -r requirements/test_requirements.txt 
Requirement already satisfied: joblib==1.4.2 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 1)) (1.4.2)
Requirement already satisfied: numpy==2.2.2 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 2)) (2.2.2)
Requirement already satisfied: pandas==2.2.3 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 3)) (2.2.3)
Requirement already satisfied: pydantic==2.10.5 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 4)) (2.10.5)
Requirement already satisfied: ruamel.yaml==0.18.10 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 5)) (0.18.10)
Requirement already satisfied: scikit-learn==1.6.1 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 6)) (1.6.1)
Requirement already satisfied: strictyaml==1.7.3 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from -r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 7)) (1.7.3)
Collecting pytest<8.0.0,>=7.2.0 (from -r requirements/test_requirements.txt (line 4))
  Downloading pytest-7.4.4-py3-none-any.whl.metadata (7.9 kB)
Requirement already satisfied: python-dateutil>=2.8.2 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pandas==2.2.3->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 3)) (2.9.0.post0)
Requirement already satisfied: pytz>=2020.1 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pandas==2.2.3->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 3)) (2025.1)
Requirement already satisfied: tzdata>=2022.7 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pandas==2.2.3->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 3)) (2025.1)
Requirement already satisfied: annotated-types>=0.6.0 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pydantic==2.10.5->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 4)) (0.7.0)
Requirement already satisfied: pydantic-core==2.27.2 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pydantic==2.10.5->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 4)) (2.27.2)
Requirement already satisfied: typing-extensions>=4.12.2 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from pydantic==2.10.5->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 4)) (4.12.2)
Requirement already satisfied: ruamel.yaml.clib>=0.2.7 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from ruamel.yaml==0.18.10->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 5)) (0.2.12)
Requirement already satisfied: scipy>=1.6.0 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from scikit-learn==1.6.1->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 6)) (1.15.2)
Requirement already satisfied: threadpoolctl>=3.1.0 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from scikit-learn==1.6.1->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 6)) (3.6.0)
Collecting iniconfig (from pytest<8.0.0,>=7.2.0->-r requirements/test_requirements.txt (line 4))
  Downloading iniconfig-2.1.0-py3-none-any.whl.metadata (2.7 kB)
Collecting packaging (from pytest<8.0.0,>=7.2.0->-r requirements/test_requirements.txt (line 4))
  Downloading packaging-24.2-py3-none-any.whl.metadata (3.2 kB)
Collecting pluggy<2.0,>=0.12 (from pytest<8.0.0,>=7.2.0->-r requirements/test_requirements.txt (line 4))
  Downloading pluggy-1.5.0-py3-none-any.whl.metadata (4.8 kB)
Requirement already satisfied: six>=1.5 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from python-dateutil>=2.8.2->pandas==2.2.3->-r /workspaces/bike-rental-prediction/bikeshare_project/requirements/requirements.txt (line 3)) (1.17.0)
Downloading pytest-7.4.4-py3-none-any.whl (325 kB)
Downloading pluggy-1.5.0-py3-none-any.whl (20 kB)
Downloading iniconfig-2.1.0-py3-none-any.whl (6.0 kB)
Downloading packaging-24.2-py3-none-any.whl (65 kB)
Installing collected packages: pluggy, packaging, iniconfig, pytest
Successfully installed iniconfig-2.1.0 packaging-24.2 pluggy-1.5.0 pytest-7.4.4
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ ls
MANIFEST.in  bike_sharing_api  bikeshare_model  mypy.ini  pyproject.toml  requirements  setup.py  tests
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ python bikeshare_model/predict.py 
{'predictions': array([688.]), 'version': '0.0.1', 'errors': None}
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ pytest
================================================================== test session starts ==================================================================
platform linux -- Python 3.11.11, pytest-7.4.4, pluggy-1.5.0
rootdir: /workspaces/bike-rental-prediction/bikeshare_project
configfile: pyproject.toml
testpaths: tests
collected 6 items                                                                                                                                       

tests/test_features.py .....                                                                                                                      [ 83%]
tests/test_predictions.py .                                                                                                                       [100%]

=================================================================== 6 passed in 0.75s ===================================================================
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ python -m build
/opt/conda/envs/iisc-miniproject/bin/python: No module named build
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ pip install --upgrade pip
ools wheel twineRequirement already satisfied: pip in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (25.0)
Collecting pip
  Downloading pip-25.0.1-py3-none-any.whl.metadata (3.7 kB)
Downloading pip-25.0.1-py3-none-any.whl (1.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.8/1.8 MB 30.5 MB/s eta 0:00:00
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 25.0
    Uninstalling pip-25.0:
      Successfully uninstalled pip-25.0
Successfully installed pip-25.0.1
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ pip install build setuptools wheel twine
Collecting build
  Downloading build-1.2.2.post1-py3-none-any.whl.metadata (6.5 kB)
Requirement already satisfied: setuptools in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (75.8.0)
Requirement already satisfied: wheel in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (0.45.1)
Collecting twine
  Downloading twine-6.1.0-py3-none-any.whl.metadata (3.7 kB)
Requirement already satisfied: packaging>=19.1 in /opt/conda/envs/iisc-miniproject/lib/python3.11/site-packages (from build) (24.2)
Collecting pyproject_hooks (from build)
  Downloading pyproject_hooks-1.2.0-py3-none-any.whl.metadata (1.3 kB)
Collecting readme-renderer>=35.0 (from twine)
  Downloading readme_renderer-44.0-py3-none-any.whl.metadata (2.8 kB)
Collecting requests>=2.20 (from twine)
  Downloading requests-2.32.3-py3-none-any.whl.metadata (4.6 kB)
Collecting requests-toolbelt!=0.9.0,>=0.8.0 (from twine)
  Downloading requests_toolbelt-1.0.0-py2.py3-none-any.whl.metadata (14 kB)
Collecting urllib3>=1.26.0 (from twine)
  Downloading urllib3-2.3.0-py3-none-any.whl.metadata (6.5 kB)
Collecting keyring>=15.1 (from twine)
  Downloading keyring-25.6.0-py3-none-any.whl.metadata (20 kB)
Collecting rfc3986>=1.4.0 (from twine)
  Downloading rfc3986-2.0.0-py2.py3-none-any.whl.metadata (6.6 kB)
Collecting rich>=12.0.0 (from twine)
  Downloading rich-13.9.4-py3-none-any.whl.metadata (18 kB)
Collecting id (from twine)
  Downloading id-1.5.0-py3-none-any.whl.metadata (5.2 kB)
Collecting SecretStorage>=3.2 (from keyring>=15.1->twine)
  Downloading SecretStorage-3.3.3-py3-none-any.whl.metadata (4.0 kB)
Collecting jeepney>=0.4.2 (from keyring>=15.1->twine)
  Downloading jeepney-0.9.0-py3-none-any.whl.metadata (1.2 kB)
Collecting importlib_metadata>=4.11.4 (from keyring>=15.1->twine)
  Downloading importlib_metadata-8.6.1-py3-none-any.whl.metadata (4.7 kB)
Collecting jaraco.classes (from keyring>=15.1->twine)
  Downloading jaraco.classes-3.4.0-py3-none-any.whl.metadata (2.6 kB)
Collecting jaraco.functools (from keyring>=15.1->twine)
  Downloading jaraco.functools-4.1.0-py3-none-any.whl.metadata (2.9 kB)
Collecting jaraco.context (from keyring>=15.1->twine)
  Downloading jaraco.context-6.0.1-py3-none-any.whl.metadata (4.1 kB)
Collecting nh3>=0.2.14 (from readme-renderer>=35.0->twine)
  Downloading nh3-0.2.21-cp38-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (2.0 kB)
Collecting docutils>=0.21.2 (from readme-renderer>=35.0->twine)
  Downloading docutils-0.21.2-py3-none-any.whl.metadata (2.8 kB)
Collecting Pygments>=2.5.1 (from readme-renderer>=35.0->twine)
  Downloading pygments-2.19.1-py3-none-any.whl.metadata (2.5 kB)
Collecting charset-normalizer<4,>=2 (from requests>=2.20->twine)
  Downloading charset_normalizer-3.4.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (35 kB)
Collecting idna<4,>=2.5 (from requests>=2.20->twine)
  Downloading idna-3.10-py3-none-any.whl.metadata (10 kB)
Collecting certifi>=2017.4.17 (from requests>=2.20->twine)
  Downloading certifi-2025.1.31-py3-none-any.whl.metadata (2.5 kB)
Collecting markdown-it-py>=2.2.0 (from rich>=12.0.0->twine)
  Downloading markdown_it_py-3.0.0-py3-none-any.whl.metadata (6.9 kB)
Collecting zipp>=3.20 (from importlib_metadata>=4.11.4->keyring>=15.1->twine)
  Downloading zipp-3.21.0-py3-none-any.whl.metadata (3.7 kB)
Collecting mdurl~=0.1 (from markdown-it-py>=2.2.0->rich>=12.0.0->twine)
  Downloading mdurl-0.1.2-py3-none-any.whl.metadata (1.6 kB)
Collecting cryptography>=2.0 (from SecretStorage>=3.2->keyring>=15.1->twine)
  Downloading cryptography-44.0.2-cp39-abi3-manylinux_2_28_x86_64.whl.metadata (5.7 kB)
Collecting more-itertools (from jaraco.classes->keyring>=15.1->twine)
  Downloading more_itertools-10.6.0-py3-none-any.whl.metadata (37 kB)
Collecting backports.tarfile (from jaraco.context->keyring>=15.1->twine)
  Downloading backports.tarfile-1.2.0-py3-none-any.whl.metadata (2.0 kB)
Collecting cffi>=1.12 (from cryptography>=2.0->SecretStorage>=3.2->keyring>=15.1->twine)
  Downloading cffi-1.17.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (1.5 kB)
Collecting pycparser (from cffi>=1.12->cryptography>=2.0->SecretStorage>=3.2->keyring>=15.1->twine)
  Downloading pycparser-2.22-py3-none-any.whl.metadata (943 bytes)
Downloading build-1.2.2.post1-py3-none-any.whl (22 kB)
Downloading twine-6.1.0-py3-none-any.whl (40 kB)
Downloading keyring-25.6.0-py3-none-any.whl (39 kB)
Downloading readme_renderer-44.0-py3-none-any.whl (13 kB)
Downloading requests-2.32.3-py3-none-any.whl (64 kB)
Downloading requests_toolbelt-1.0.0-py2.py3-none-any.whl (54 kB)
Downloading rfc3986-2.0.0-py2.py3-none-any.whl (31 kB)
Downloading rich-13.9.4-py3-none-any.whl (242 kB)
Downloading urllib3-2.3.0-py3-none-any.whl (128 kB)
Downloading id-1.5.0-py3-none-any.whl (13 kB)
Downloading pyproject_hooks-1.2.0-py3-none-any.whl (10 kB)
Downloading certifi-2025.1.31-py3-none-any.whl (166 kB)
Downloading charset_normalizer-3.4.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (143 kB)
Downloading docutils-0.21.2-py3-none-any.whl (587 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 587.4/587.4 kB 15.5 MB/s eta 0:00:00
Downloading idna-3.10-py3-none-any.whl (70 kB)
Downloading importlib_metadata-8.6.1-py3-none-any.whl (26 kB)
Downloading jeepney-0.9.0-py3-none-any.whl (49 kB)
Downloading markdown_it_py-3.0.0-py3-none-any.whl (87 kB)
Downloading nh3-0.2.21-cp38-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (739 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 739.0/739.0 kB 33.8 MB/s eta 0:00:00
Downloading pygments-2.19.1-py3-none-any.whl (1.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 39.1 MB/s eta 0:00:00
Downloading SecretStorage-3.3.3-py3-none-any.whl (15 kB)
Downloading jaraco.classes-3.4.0-py3-none-any.whl (6.8 kB)
Downloading jaraco.context-6.0.1-py3-none-any.whl (6.8 kB)
Downloading jaraco.functools-4.1.0-py3-none-any.whl (10 kB)
Downloading cryptography-44.0.2-cp39-abi3-manylinux_2_28_x86_64.whl (4.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.2/4.2 MB 52.3 MB/s eta 0:00:00
Downloading mdurl-0.1.2-py3-none-any.whl (10.0 kB)
Downloading zipp-3.21.0-py3-none-any.whl (9.6 kB)
Downloading backports.tarfile-1.2.0-py3-none-any.whl (30 kB)
Downloading more_itertools-10.6.0-py3-none-any.whl (63 kB)
Downloading cffi-1.17.1-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (467 kB)
Downloading pycparser-2.22-py3-none-any.whl (117 kB)
Installing collected packages: zipp, urllib3, rfc3986, pyproject_hooks, Pygments, pycparser, nh3, more-itertools, mdurl, jeepney, idna, docutils, charset-normalizer, certifi, backports.tarfile, requests, readme-renderer, markdown-it-py, jaraco.functools, jaraco.context, jaraco.classes, importlib_metadata, cffi, build, rich, requests-toolbelt, id, cryptography, SecretStorage, keyring, twine
Successfully installed Pygments-2.19.1 SecretStorage-3.3.3 backports.tarfile-1.2.0 build-1.2.2.post1 certifi-2025.1.31 cffi-1.17.1 charset-normalizer-3.4.1 cryptography-44.0.2 docutils-0.21.2 id-1.5.0 idna-3.10 importlib_metadata-8.6.1 jaraco.classes-3.4.0 jaraco.context-6.0.1 jaraco.functools-4.1.0 jeepney-0.9.0 keyring-25.6.0 markdown-it-py-3.0.0 mdurl-0.1.2 more-itertools-10.6.0 nh3-0.2.21 pycparser-2.22 pyproject_hooks-1.2.0 readme-renderer-44.0 requests-2.32.3 requests-toolbelt-1.0.0 rfc3986-2.0.0 rich-13.9.4 twine-6.1.0 urllib3-2.3.0 zipp-3.21.0
(iisc-miniproject) @aakashvardhan ➜ /workspaces/bike-rental-prediction/bikeshare_project (main) $ python -m build
* Creating isolated environment: venv+pip...
* Installing packages in isolated environment:
  - setuptools>=42
  - wheel
* Getting build dependencies for sdist...
/workspaces/bike-rental-prediction/bikeshare_project
/tmp/build-env-_yk4pz_s/lib/python3.11/site-packages/setuptools/dist.py:760: SetuptoolsDeprecationWarning: License classifiers are deprecated.
!!

        ********************************************************************************
        Please consider removing the following classifiers in favor of a SPDX license expression:

        License :: OSI Approved :: MIT License

        See https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#license for details.
        ********************************************************************************

!!
  self._finalize_license_expression()
running egg_info
creating bikeshare_model.egg-info
writing bikeshare_model.egg-info/PKG-INFO
writing dependency_links to bikeshare_model.egg-info/dependency_links.txt
writing requirements to bikeshare_model.egg-info/requires.txt
writing top-level names to bikeshare_model.egg-info/top_level.txt
writing manifest file 'bikeshare_model.egg-info/SOURCES.txt'
reading manifest file 'bikeshare_model.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
warning: no files found matching '*.txt'
warning: no files found matching '*.md'
warning: no files found matching '*.pkl'
warning: no files found matching 'bikeshare_model/datasets/test.csv'
warning: no previously-included files found matching '*.log'
warning: no previously-included files found matching '*.cfg'
warning: no previously-included files matching '__pycache__' found under directory '*'
writing manifest file 'bikeshare_model.egg-info/SOURCES.txt'
* Building sdist...
/workspaces/bike-rental-prediction/bikeshare_project
/tmp/build-env-_yk4pz_s/lib/python3.11/site-packages/setuptools/dist.py:760: SetuptoolsDeprecationWarning: License classifiers are deprecated.
!!

        ********************************************************************************
        Please consider removing the following classifiers in favor of a SPDX license expression:

        License :: OSI Approved :: MIT License

        See https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#license for details.
        ********************************************************************************

!!
  self._finalize_license_expression()
running sdist
running egg_info
writing bikeshare_model.egg-info/PKG-INFO
writing dependency_links to bikeshare_model.egg-info/dependency_links.txt
writing requirements to bikeshare_model.egg-info/requires.txt
writing top-level names to bikeshare_model.egg-info/top_level.txt
reading manifest file 'bikeshare_model.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
warning: no files found matching '*.txt'
warning: no files found matching '*.md'
warning: no files found matching '*.pkl'
warning: no files found matching 'bikeshare_model/datasets/test.csv'
warning: no previously-included files found matching '*.log'
warning: no previously-included files found matching '*.cfg'
warning: no previously-included files matching '__pycache__' found under directory '*'
writing manifest file 'bikeshare_model.egg-info/SOURCES.txt'
warning: sdist: standard file not found: should have one of README, README.rst, README.txt, README.md

running check
creating bikeshare_model-0.0.1
creating bikeshare_model-0.0.1/bikeshare_model
creating bikeshare_model-0.0.1/bikeshare_model.egg-info
creating bikeshare_model-0.0.1/bikeshare_model/config
creating bikeshare_model-0.0.1/bikeshare_model/datasets
creating bikeshare_model-0.0.1/bikeshare_model/processing
creating bikeshare_model-0.0.1/bikeshare_model/trained_models
creating bikeshare_model-0.0.1/requirements
creating bikeshare_model-0.0.1/tests
copying files to bikeshare_model-0.0.1...
copying MANIFEST.in -> bikeshare_model-0.0.1
copying pyproject.toml -> bikeshare_model-0.0.1
copying setup.py -> bikeshare_model-0.0.1
copying bikeshare_model/VERSION -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model/__init__.py -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model/config.yml -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model/pipeline.py -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model/predict.py -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model/train_pipeline.py -> bikeshare_model-0.0.1/bikeshare_model
copying bikeshare_model.egg-info/PKG-INFO -> bikeshare_model-0.0.1/bikeshare_model.egg-info
copying bikeshare_model.egg-info/SOURCES.txt -> bikeshare_model-0.0.1/bikeshare_model.egg-info
copying bikeshare_model.egg-info/dependency_links.txt -> bikeshare_model-0.0.1/bikeshare_model.egg-info
copying bikeshare_model.egg-info/requires.txt -> bikeshare_model-0.0.1/bikeshare_model.egg-info
copying bikeshare_model.egg-info/top_level.txt -> bikeshare_model-0.0.1/bikeshare_model.egg-info
copying bikeshare_model/config/__init__.py -> bikeshare_model-0.0.1/bikeshare_model/config
copying bikeshare_model/config/core.py -> bikeshare_model-0.0.1/bikeshare_model/config
copying bikeshare_model/datasets/__init__.py -> bikeshare_model-0.0.1/bikeshare_model/datasets
copying bikeshare_model/datasets/bike-rental-dataset.csv -> bikeshare_model-0.0.1/bikeshare_model/datasets
copying bikeshare_model/processing/__init__.py -> bikeshare_model-0.0.1/bikeshare_model/processing
copying bikeshare_model/processing/data_manager.py -> bikeshare_model-0.0.1/bikeshare_model/processing
copying bikeshare_model/processing/features.py -> bikeshare_model-0.0.1/bikeshare_model/processing
copying bikeshare_model/processing/validation.py -> bikeshare_model-0.0.1/bikeshare_model/processing
copying bikeshare_model/trained_models/__init__.py -> bikeshare_model-0.0.1/bikeshare_model/trained_models
copying bikeshare_model/trained_models/bikeshare__model_output_v0.0.1.pkl -> bikeshare_model-0.0.1/bikeshare_model/trained_models
copying requirements/requirements.txt -> bikeshare_model-0.0.1/requirements
copying requirements/test_requirements.txt -> bikeshare_model-0.0.1/requirements
copying tests/test_features.py -> bikeshare_model-0.0.1/tests
copying tests/test_predictions.py -> bikeshare_model-0.0.1/tests
copying bikeshare_model.egg-info/SOURCES.txt -> bikeshare_model-0.0.1/bikeshare_model.egg-info
Writing bikeshare_model-0.0.1/setup.cfg
Creating tar archive
removing 'bikeshare_model-0.0.1' (and everything under it)
* Building wheel from sdist
* Creating isolated environment: venv+pip...
* Installing packages in isolated environment:
  - setuptools>=42
  - wheel
* Getting build dependencies for wheel...
/tmp/build-via-sdist-95mjwvrr/bikeshare_model-0.0.1
/tmp/build-env-lc7byt1t/lib/python3.11/site-packages/setuptools/dist.py:760: SetuptoolsDeprecationWarning: License classifiers are deprecated.
!!

        ********************************************************************************
        Please consider removing the following classifiers in favor of a SPDX license expression:

        License :: OSI Approved :: MIT License

        See https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#license for details.
        ********************************************************************************

!!
  self._finalize_license_expression()
running egg_info
writing bikeshare_model.egg-info/PKG-INFO
writing dependency_links to bikeshare_model.egg-info/dependency_links.txt
writing requirements to bikeshare_model.egg-info/requires.txt
writing top-level names to bikeshare_model.egg-info/top_level.txt
reading manifest file 'bikeshare_model.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
warning: no files found matching '*.txt'
warning: no files found matching '*.md'
warning: no files found matching '*.pkl'
warning: no files found matching 'bikeshare_model/datasets/test.csv'
warning: no previously-included files found matching '*.log'
warning: no previously-included files matching '__pycache__' found under directory '*'
warning: no previously-included files matching '*.py[co]' found under directory '*'
writing manifest file 'bikeshare_model.egg-info/SOURCES.txt'
* Building wheel...
/tmp/build-via-sdist-95mjwvrr/bikeshare_model-0.0.1
/tmp/build-env-lc7byt1t/lib/python3.11/site-packages/setuptools/dist.py:760: SetuptoolsDeprecationWarning: License classifiers are deprecated.
!!

        ********************************************************************************
        Please consider removing the following classifiers in favor of a SPDX license expression:

        License :: OSI Approved :: MIT License

        See https://packaging.python.org/en/latest/guides/writing-pyproject-toml/#license for details.
        ********************************************************************************

!!
  self._finalize_license_expression()
running bdist_wheel
running build
running build_py
creating build/lib/bikeshare_model
copying bikeshare_model/predict.py -> build/lib/bikeshare_model
copying bikeshare_model/pipeline.py -> build/lib/bikeshare_model
copying bikeshare_model/train_pipeline.py -> build/lib/bikeshare_model
copying bikeshare_model/__init__.py -> build/lib/bikeshare_model
creating build/lib/bikeshare_model/processing
copying bikeshare_model/processing/features.py -> build/lib/bikeshare_model/processing
copying bikeshare_model/processing/data_manager.py -> build/lib/bikeshare_model/processing
copying bikeshare_model/processing/__init__.py -> build/lib/bikeshare_model/processing
copying bikeshare_model/processing/validation.py -> build/lib/bikeshare_model/processing
creating build/lib/bikeshare_model/datasets
copying bikeshare_model/datasets/__init__.py -> build/lib/bikeshare_model/datasets
creating build/lib/bikeshare_model/config
copying bikeshare_model/config/core.py -> build/lib/bikeshare_model/config
copying bikeshare_model/config/__init__.py -> build/lib/bikeshare_model/config
creating build/lib/bikeshare_model/trained_models
copying bikeshare_model/trained_models/__init__.py -> build/lib/bikeshare_model/trained_models
running egg_info
writing bikeshare_model.egg-info/PKG-INFO
writing dependency_links to bikeshare_model.egg-info/dependency_links.txt
writing requirements to bikeshare_model.egg-info/requires.txt
writing top-level names to bikeshare_model.egg-info/top_level.txt
reading manifest file 'bikeshare_model.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
warning: no files found matching '*.txt'
warning: no files found matching '*.md'
warning: no files found matching '*.pkl'
warning: no files found matching 'bikeshare_model/datasets/test.csv'
warning: no previously-included files found matching '*.log'
warning: no previously-included files matching '__pycache__' found under directory '*'
warning: no previously-included files matching '*.py[co]' found under directory '*'
writing manifest file 'bikeshare_model.egg-info/SOURCES.txt'
copying bikeshare_model/VERSION -> build/lib/bikeshare_model
copying bikeshare_model/config.yml -> build/lib/bikeshare_model
copying bikeshare_model/datasets/bike-rental-dataset.csv -> build/lib/bikeshare_model/datasets
copying bikeshare_model/trained_models/bikeshare__model_output_v0.0.1.pkl -> build/lib/bikeshare_model/trained_models
installing to build/bdist.linux-x86_64/wheel
running install
running install_lib
creating build/bdist.linux-x86_64/wheel
creating build/bdist.linux-x86_64/wheel/bikeshare_model
copying build/lib/bikeshare_model/config.yml -> build/bdist.linux-x86_64/wheel/./bikeshare_model
creating build/bdist.linux-x86_64/wheel/bikeshare_model/processing
copying build/lib/bikeshare_model/processing/features.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/processing
copying build/lib/bikeshare_model/processing/data_manager.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/processing
copying build/lib/bikeshare_model/processing/__init__.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/processing
copying build/lib/bikeshare_model/processing/validation.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/processing
creating build/bdist.linux-x86_64/wheel/bikeshare_model/datasets
copying build/lib/bikeshare_model/datasets/bike-rental-dataset.csv -> build/bdist.linux-x86_64/wheel/./bikeshare_model/datasets
copying build/lib/bikeshare_model/datasets/__init__.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/datasets
copying build/lib/bikeshare_model/predict.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model
creating build/bdist.linux-x86_64/wheel/bikeshare_model/config
copying build/lib/bikeshare_model/config/core.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/config
copying build/lib/bikeshare_model/config/__init__.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/config
copying build/lib/bikeshare_model/pipeline.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model
copying build/lib/bikeshare_model/train_pipeline.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model
copying build/lib/bikeshare_model/__init__.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model
creating build/bdist.linux-x86_64/wheel/bikeshare_model/trained_models
copying build/lib/bikeshare_model/trained_models/bikeshare__model_output_v0.0.1.pkl -> build/bdist.linux-x86_64/wheel/./bikeshare_model/trained_models
copying build/lib/bikeshare_model/trained_models/__init__.py -> build/bdist.linux-x86_64/wheel/./bikeshare_model/trained_models
copying build/lib/bikeshare_model/VERSION -> build/bdist.linux-x86_64/wheel/./bikeshare_model
running install_egg_info
Copying bikeshare_model.egg-info to build/bdist.linux-x86_64/wheel/./bikeshare_model-0.0.1-py3.11.egg-info
running install_scripts
creating build/bdist.linux-x86_64/wheel/bikeshare_model-0.0.1.dist-info/WHEEL
creating '/workspaces/bike-rental-prediction/bikeshare_project/dist/.tmp-rri07khi/bikeshare_model-0.0.1-py3-none-any.whl' and adding 'build/bdist.linux-x86_64/wheel' to it
adding 'bikeshare_model/VERSION'
adding 'bikeshare_model/__init__.py'
adding 'bikeshare_model/config.yml'
adding 'bikeshare_model/pipeline.py'
adding 'bikeshare_model/predict.py'
adding 'bikeshare_model/train_pipeline.py'
adding 'bikeshare_model/config/__init__.py'
adding 'bikeshare_model/config/core.py'
adding 'bikeshare_model/datasets/__init__.py'
adding 'bikeshare_model/datasets/bike-rental-dataset.csv'
adding 'bikeshare_model/processing/__init__.py'
adding 'bikeshare_model/processing/data_manager.py'
adding 'bikeshare_model/processing/features.py'
adding 'bikeshare_model/processing/validation.py'
adding 'bikeshare_model/trained_models/__init__.py'
adding 'bikeshare_model/trained_models/bikeshare__model_output_v0.0.1.pkl'
adding 'bikeshare_model-0.0.1.dist-info/METADATA'
adding 'bikeshare_model-0.0.1.dist-info/WHEEL'
adding 'bikeshare_model-0.0.1.dist-info/top_level.txt'
adding 'bikeshare_model-0.0.1.dist-info/RECORD'
removing build/bdist.linux-x86_64/wheel
Successfully built bikeshare_model-0.0.1.tar.gz and bikeshare_model-0.0.1-py3-none-any.whl