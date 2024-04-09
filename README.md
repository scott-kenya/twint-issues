# twint-issues
ERROR: Could not build wheels for cchardet, which is required to install pyproject.toml-based projects
Collecting twint
  Using cached twint-2.1.20-py3-none-any.whl
Collecting aiohttp (from twint)
  Using cached aiohttp-3.9.3-cp311-cp311-win_amd64.whl.metadata (7.6 kB)
Collecting aiodns (from twint)
  Using cached aiodns-3.2.0-py3-none-any.whl.metadata (4.0 kB)
Requirement already satisfied: beautifulsoup4 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from twint) (4.12.3)
Collecting cchardet (from twint)
  Using cached cchardet-2.1.7.tar.gz (653 kB)
  Preparing metadata (setup.py) ... done
Collecting elasticsearch (from twint)
  Using cached elasticsearch-8.13.0-py3-none-any.whl.metadata (6.3 kB)
Requirement already satisfied: pysocks in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from twint) (1.7.1) 
Requirement already satisfied: pandas in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from twint) (2.2.1)  
Collecting aiohttp-socks (from twint)
  Using cached aiohttp_socks-0.8.4-py3-none-any.whl.metadata (3.1 kB)
Collecting schedule (from twint)
  Using cached schedule-1.2.1-py2.py3-none-any.whl.metadata (3.3 kB)
Collecting geopy (from twint)
  Using cached geopy-2.4.1-py3-none-any.whl.metadata (6.8 kB)
Collecting fake-useragent (from twint)
  Using cached fake_useragent-1.5.1-py3-none-any.whl.metadata (15 kB)
Collecting googletransx (from twint)
  Using cached googletransx-2.4.2-py3-none-any.whl
Collecting pycares>=4.0.0 (from aiodns->twint)
  Using cached pycares-4.4.0-cp311-cp311-win_amd64.whl.metadata (4.5 kB)
Collecting aiosignal>=1.1.2 (from aiohttp->twint)
  Using cached aiosignal-1.3.1-py3-none-any.whl.metadata (4.0 kB)
Collecting attrs>=17.3.0 (from aiohttp->twint)
  Using cached attrs-23.2.0-py3-none-any.whl.metadata (9.5 kB)
Collecting frozenlist>=1.1.1 (from aiohttp->twint)
  Using cached frozenlist-1.4.1-cp311-cp311-win_amd64.whl.metadata (12 kB)
Collecting multidict<7.0,>=4.5 (from aiohttp->twint)
  Using cached multidict-6.0.5-cp311-cp311-win_amd64.whl.metadata (4.3 kB)
Collecting yarl<2.0,>=1.0 (from aiohttp->twint)
  Using cached yarl-1.9.4-cp311-cp311-win_amd64.whl.metadata (32 kB)
Collecting python-socks<3.0.0,>=2.4.3 (from python-socks[asyncio]<3.0.0,>=2.4.3->aiohttp-socks->twint)
  Using cached python_socks-2.4.4-py3-none-any.whl.metadata (7.1 kB)
Requirement already satisfied: soupsieve>1.2 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from beautifulsoup4->twint) (2.5)
Collecting elastic-transport<9,>=8.13 (from elasticsearch->twint)
  Using cached elastic_transport-8.13.0-py3-none-any.whl.metadata (3.7 kB)
Collecting geographiclib<3,>=1.52 (from geopy->twint)
  Using cached geographiclib-2.0-py3-none-any.whl.metadata (1.4 kB)
Requirement already satisfied: requests in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from googletransx->twint) (2.31.0)
Requirement already satisfied: numpy<2,>=1.23.2 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from pandas->twint) (1.26.4)
Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from 
pandas->twint) (2.8.2)
Requirement already satisfied: pytz>=2020.1 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from pandas->twint) (2023.3)
Requirement already satisfied: tzdata>=2022.7 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from pandas->twint) (2024.1)
Requirement already satisfied: urllib3<3,>=1.26.2 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from elastic-transport<9,>=8.13->elasticsearch->twint) (1.26.9)
Requirement already satisfied: certifi in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from elastic-transport<9,>=8.13->elasticsearch->twint) (2023.5.7)
Requirement already satisfied: cffi>=1.5.0 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from pycares>=4.0.0->aiodns->twint) (1.15.1)
Requirement already satisfied: six>=1.5 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from python-dateutil>=2.8.2->pandas->twint) (1.16.0)
Collecting async-timeout>=3.0.1 (from python-socks[asyncio]<3.0.0,>=2.4.3->aiohttp-socks->twint)
  Using cached async_timeout-4.0.3-py3-none-any.whl.metadata (4.2 kB)
Requirement already satisfied: idna>=2.0 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from yarl<2.0,>=1.0->aiohttp->twint) (3.4)
Requirement already satisfied: charset-normalizer<4,>=2 in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from requests->googletransx->twint) (3.1.0)
Requirement already satisfied: pycparser in c:\users\scott\appdata\local\packages\pythonsoftwarefoundation.python.3.11_qbz5n2kfra8p0\localcache\local-packages\python311\site-packages (from cffi>=1.5.0->pycares>=4.0.0->aiodns->twint) (2.21)
Using cached aiodns-3.2.0-py3-none-any.whl (5.7 kB)
Using cached aiohttp-3.9.3-cp311-cp311-win_amd64.whl (365 kB)
Using cached aiohttp_socks-0.8.4-py3-none-any.whl (9.6 kB)
Using cached elasticsearch-8.13.0-py3-none-any.whl (451 kB)
Using cached fake_useragent-1.5.1-py3-none-any.whl (17 kB)
Using cached geopy-2.4.1-py3-none-any.whl (125 kB)
Using cached schedule-1.2.1-py2.py3-none-any.whl (11 kB)
Using cached aiosignal-1.3.1-py3-none-any.whl (7.6 kB)
Using cached attrs-23.2.0-py3-none-any.whl (60 kB)
Using cached elastic_transport-8.13.0-py3-none-any.whl (64 kB)
Using cached frozenlist-1.4.1-cp311-cp311-win_amd64.whl (50 kB)
Using cached geographiclib-2.0-py3-none-any.whl (40 kB)
Using cached multidict-6.0.5-cp311-cp311-win_amd64.whl (28 kB)
Using cached pycares-4.4.0-cp311-cp311-win_amd64.whl (76 kB)
Using cached python_socks-2.4.4-py3-none-any.whl (52 kB)
Using cached yarl-1.9.4-cp311-cp311-win_amd64.whl (76 kB)
Using cached async_timeout-4.0.3-py3-none-any.whl (5.7 kB)
Building wheels for collected packages: cchardet
  Building wheel for cchardet (setup.py) ... error
  error: subprocess-exited-with-error

  × python setup.py bdist_wheel did not run successfully.
  │ exit code: 1
  ╰─> [12 lines of output]
      cythonize: ['src/cchardet\\_cchardet.pyx']
      running bdist_wheel
      running build
      running build_py
      creating build
      creating build\lib.win-amd64-cpython-311
      creating build\lib.win-amd64-cpython-311\cchardet
      copying src\cchardet\version.py -> build\lib.win-amd64-cpython-311\cchardet
      copying src\cchardet\__init__.py -> build\lib.win-amd64-cpython-311\cchardet
      running build_ext
      building 'cchardet._cchardet' extension
      error: Microsoft Visual C++ 14.0 or greater is required. Get it with "Microsoft C++ Build Tools": https://visualstudio.microsoft.com/visual-cpp-build-tools/
      [end of output]

  note: This error originates from a subprocess, and is likely not a problem with pip.
  ERROR: Failed building wheel for cchardet
  Running setup.py clean for cchardet
Failed to build cchardet
ERROR: Could not build wheels for cchardet, which is required to install pyproject.toml-based projects
