```python
import sys
!{sys.executable} -m pip install plotly
!{sys.executable} -m pip install Dash
!{sys.executable} -m pip install jupyter-dash
```

    Requirement already satisfied: plotly in c:\users\tomas\anaconda3\lib\site-packages (5.9.0)
    Requirement already satisfied: tenacity>=6.2.0 in c:\users\tomas\anaconda3\lib\site-packages (from plotly) (8.0.1)
    Requirement already satisfied: Dash in c:\users\tomas\anaconda3\lib\site-packages (2.9.3)
    Requirement already satisfied: plotly>=5.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from Dash) (5.9.0)
    Requirement already satisfied: dash-html-components==2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from Dash) (2.0.0)
    Requirement already satisfied: dash-core-components==2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from Dash) (2.0.0)
    Requirement already satisfied: dash-table==5.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from Dash) (5.0.0)
    Requirement already satisfied: Flask>=1.0.4 in c:\users\tomas\anaconda3\lib\site-packages (from Dash) (1.1.2)
    Requirement already satisfied: itsdangerous>=0.24 in c:\users\tomas\anaconda3\lib\site-packages (from Flask>=1.0.4->Dash) (2.0.1)
    Requirement already satisfied: Werkzeug>=0.15 in c:\users\tomas\anaconda3\lib\site-packages (from Flask>=1.0.4->Dash) (2.0.3)
    Requirement already satisfied: click>=5.1 in c:\users\tomas\anaconda3\lib\site-packages (from Flask>=1.0.4->Dash) (8.0.4)
    Requirement already satisfied: Jinja2>=2.10.1 in c:\users\tomas\anaconda3\lib\site-packages (from Flask>=1.0.4->Dash) (2.11.3)
    Requirement already satisfied: tenacity>=6.2.0 in c:\users\tomas\anaconda3\lib\site-packages (from plotly>=5.0.0->Dash) (8.0.1)
    Requirement already satisfied: colorama in c:\users\tomas\anaconda3\lib\site-packages (from click>=5.1->Flask>=1.0.4->Dash) (0.4.5)
    Requirement already satisfied: MarkupSafe>=0.23 in c:\users\tomas\anaconda3\lib\site-packages (from Jinja2>=2.10.1->Flask>=1.0.4->Dash) (2.0.1)
    Collecting jupyter-dash
      Downloading jupyter_dash-0.4.2-py3-none-any.whl (23 kB)
    Collecting ansi2html
      Downloading ansi2html-1.8.0-py3-none-any.whl (16 kB)
    Requirement already satisfied: flask in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (1.1.2)
    Requirement already satisfied: ipykernel in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (6.15.2)
    Requirement already satisfied: nest-asyncio in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (1.5.5)
    Collecting retrying
      Downloading retrying-1.3.4-py3-none-any.whl (11 kB)
    Requirement already satisfied: requests in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (2.28.1)
    Requirement already satisfied: dash in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (2.9.3)
    Requirement already satisfied: ipython in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-dash) (7.31.1)
    Requirement already satisfied: plotly>=5.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from dash->jupyter-dash) (5.9.0)
    Requirement already satisfied: dash-html-components==2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from dash->jupyter-dash) (2.0.0)
    Requirement already satisfied: dash-core-components==2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from dash->jupyter-dash) (2.0.0)
    Requirement already satisfied: dash-table==5.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from dash->jupyter-dash) (5.0.0)
    Requirement already satisfied: itsdangerous>=0.24 in c:\users\tomas\anaconda3\lib\site-packages (from flask->jupyter-dash) (2.0.1)
    Requirement already satisfied: Werkzeug>=0.15 in c:\users\tomas\anaconda3\lib\site-packages (from flask->jupyter-dash) (2.0.3)
    Requirement already satisfied: Jinja2>=2.10.1 in c:\users\tomas\anaconda3\lib\site-packages (from flask->jupyter-dash) (2.11.3)
    Requirement already satisfied: click>=5.1 in c:\users\tomas\anaconda3\lib\site-packages (from flask->jupyter-dash) (8.0.4)
    Requirement already satisfied: debugpy>=1.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (1.5.1)
    Requirement already satisfied: pyzmq>=17 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (23.2.0)
    Requirement already satisfied: jupyter-client>=6.1.12 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (7.3.4)
    Requirement already satisfied: matplotlib-inline>=0.1 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (0.1.6)
    Requirement already satisfied: packaging in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (21.3)
    Requirement already satisfied: tornado>=6.1 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (6.1)
    Requirement already satisfied: psutil in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (5.9.0)
    Requirement already satisfied: traitlets>=5.1.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter-dash) (5.1.1)
    Requirement already satisfied: jedi>=0.16 in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (0.18.1)
    Requirement already satisfied: decorator in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (5.1.1)
    Requirement already satisfied: pygments in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (2.11.2)
    Requirement already satisfied: pickleshare in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (0.7.5)
    Requirement already satisfied: colorama in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (0.4.5)
    Requirement already satisfied: backcall in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (0.2.0)
    Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (3.0.20)
    Requirement already satisfied: setuptools>=18.5 in c:\users\tomas\anaconda3\lib\site-packages (from ipython->jupyter-dash) (63.4.1)
    Requirement already satisfied: idna<4,>=2.5 in c:\users\tomas\anaconda3\lib\site-packages (from requests->jupyter-dash) (3.3)
    Requirement already satisfied: certifi>=2017.4.17 in c:\users\tomas\anaconda3\lib\site-packages (from requests->jupyter-dash) (2022.9.14)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in c:\users\tomas\anaconda3\lib\site-packages (from requests->jupyter-dash) (1.26.11)
    Requirement already satisfied: charset-normalizer<3,>=2 in c:\users\tomas\anaconda3\lib\site-packages (from requests->jupyter-dash) (2.0.4)
    Requirement already satisfied: six>=1.7.0 in c:\users\tomas\anaconda3\lib\site-packages (from retrying->jupyter-dash) (1.16.0)
    Requirement already satisfied: parso<0.9.0,>=0.8.0 in c:\users\tomas\anaconda3\lib\site-packages (from jedi>=0.16->ipython->jupyter-dash) (0.8.3)
    Requirement already satisfied: MarkupSafe>=0.23 in c:\users\tomas\anaconda3\lib\site-packages (from Jinja2>=2.10.1->flask->jupyter-dash) (2.0.1)
    Requirement already satisfied: entrypoints in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-client>=6.1.12->ipykernel->jupyter-dash) (0.4)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-client>=6.1.12->ipykernel->jupyter-dash) (2.8.2)
    Requirement already satisfied: jupyter-core>=4.9.2 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-client>=6.1.12->ipykernel->jupyter-dash) (4.11.1)
    Requirement already satisfied: tenacity>=6.2.0 in c:\users\tomas\anaconda3\lib\site-packages (from plotly>=5.0.0->dash->jupyter-dash) (8.0.1)
    Requirement already satisfied: wcwidth in c:\users\tomas\anaconda3\lib\site-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->ipython->jupyter-dash) (0.2.5)
    Requirement already satisfied: pyparsing!=3.0.5,>=2.0.2 in c:\users\tomas\anaconda3\lib\site-packages (from packaging->ipykernel->jupyter-dash) (3.0.9)
    Requirement already satisfied: pywin32>=1.0 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-core>=4.9.2->jupyter-client>=6.1.12->ipykernel->jupyter-dash) (302)
    Installing collected packages: retrying, ansi2html, jupyter-dash
    Successfully installed ansi2html-1.8.0 jupyter-dash-0.4.2 retrying-1.3.4
    


```python
import sys
!{sys.executable} -m pip install hide_code
!{sys.executable} -m jupyter nbextension install --py --user hide_code
!{sys.executable} -m jupyter nbextension enable --py --user hide_code
!{sys.executable} -m jupyter serverextension enable --py --user hide_code
```

    Requirement already satisfied: hide_code in c:\users\tomas\anaconda3\lib\site-packages (0.7.0)
    Requirement already satisfied: jupyter<2.0.0,>=1.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from hide_code) (1.0.0)
    Requirement already satisfied: pdfkit<2.0.0,>=1.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from hide_code) (1.0.0)
    Requirement already satisfied: notebook<7.0.0,>=6.4.12 in c:\users\tomas\anaconda3\lib\site-packages (from hide_code) (6.4.12)
    Requirement already satisfied: ipykernel in c:\users\tomas\anaconda3\lib\site-packages (from jupyter<2.0.0,>=1.0.0->hide_code) (6.15.2)
    Requirement already satisfied: qtconsole in c:\users\tomas\anaconda3\lib\site-packages (from jupyter<2.0.0,>=1.0.0->hide_code) (5.2.2)
    Requirement already satisfied: jupyter-console in c:\users\tomas\anaconda3\lib\site-packages (from jupyter<2.0.0,>=1.0.0->hide_code) (6.4.3)
    Requirement already satisfied: ipywidgets in c:\users\tomas\anaconda3\lib\site-packages (from jupyter<2.0.0,>=1.0.0->hide_code) (7.6.5)
    Requirement already satisfied: nbconvert in c:\users\tomas\anaconda3\lib\site-packages (from jupyter<2.0.0,>=1.0.0->hide_code) (6.4.4)
    Requirement already satisfied: terminado>=0.8.3 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (0.13.1)
    Requirement already satisfied: argon2-cffi in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (21.3.0)
    Requirement already satisfied: Send2Trash>=1.8.0 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (1.8.0)
    Requirement already satisfied: jupyter-core>=4.6.1 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (4.11.1)
    Requirement already satisfied: tornado>=6.1 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (6.1)
    Requirement already satisfied: pyzmq>=17 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (23.2.0)
    Requirement already satisfied: traitlets>=4.2.1 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (5.1.1)
    Requirement already satisfied: jupyter-client>=5.3.4 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (7.3.4)
    Requirement already satisfied: prometheus-client in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (0.14.1)
    Requirement already satisfied: ipython-genutils in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (0.2.0)
    Requirement already satisfied: nbformat in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (5.5.0)
    Requirement already satisfied: nest-asyncio>=1.5 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (1.5.5)
    Requirement already satisfied: jinja2 in c:\users\tomas\anaconda3\lib\site-packages (from notebook<7.0.0,>=6.4.12->hide_code) (2.11.3)
    Requirement already satisfied: entrypoints in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-client>=5.3.4->notebook<7.0.0,>=6.4.12->hide_code) (0.4)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-client>=5.3.4->notebook<7.0.0,>=6.4.12->hide_code) (2.8.2)
    Requirement already satisfied: pywin32>=1.0 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-core>=4.6.1->notebook<7.0.0,>=6.4.12->hide_code) (302)
    Requirement already satisfied: testpath in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.6.0)
    Requirement already satisfied: defusedxml in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.7.1)
    Requirement already satisfied: mistune<2,>=0.8.1 in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.8.4)
    Requirement already satisfied: nbclient<0.6.0,>=0.5.0 in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.5.13)
    Requirement already satisfied: pandocfilters>=1.4.1 in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (1.5.0)
    Requirement already satisfied: pygments>=2.4.1 in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (2.11.2)
    Requirement already satisfied: bleach in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (4.1.0)
    Requirement already satisfied: beautifulsoup4 in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (4.11.1)
    Requirement already satisfied: jupyterlab-pygments in c:\users\tomas\anaconda3\lib\site-packages (from nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.1.2)
    Requirement already satisfied: MarkupSafe>=0.23 in c:\users\tomas\anaconda3\lib\site-packages (from jinja2->notebook<7.0.0,>=6.4.12->hide_code) (2.0.1)
    Requirement already satisfied: jsonschema>=2.6 in c:\users\tomas\anaconda3\lib\site-packages (from nbformat->notebook<7.0.0,>=6.4.12->hide_code) (4.16.0)
    Requirement already satisfied: fastjsonschema in c:\users\tomas\anaconda3\lib\site-packages (from nbformat->notebook<7.0.0,>=6.4.12->hide_code) (2.16.2)
    Requirement already satisfied: pywinpty>=1.1.0 in c:\users\tomas\anaconda3\lib\site-packages (from terminado>=0.8.3->notebook<7.0.0,>=6.4.12->hide_code) (2.0.2)
    Requirement already satisfied: argon2-cffi-bindings in c:\users\tomas\anaconda3\lib\site-packages (from argon2-cffi->notebook<7.0.0,>=6.4.12->hide_code) (21.2.0)
    Requirement already satisfied: psutil in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (5.9.0)
    Requirement already satisfied: matplotlib-inline>=0.1 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.1.6)
    Requirement already satisfied: debugpy>=1.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (1.5.1)
    Requirement already satisfied: ipython>=7.23.1 in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (7.31.1)
    Requirement already satisfied: packaging in c:\users\tomas\anaconda3\lib\site-packages (from ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (21.3)
    Requirement already satisfied: widgetsnbextension~=3.5.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipywidgets->jupyter<2.0.0,>=1.0.0->hide_code) (3.5.2)
    Requirement already satisfied: jupyterlab-widgets>=1.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from ipywidgets->jupyter<2.0.0,>=1.0.0->hide_code) (1.0.0)
    Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in c:\users\tomas\anaconda3\lib\site-packages (from jupyter-console->jupyter<2.0.0,>=1.0.0->hide_code) (3.0.20)
    Requirement already satisfied: qtpy in c:\users\tomas\anaconda3\lib\site-packages (from qtconsole->jupyter<2.0.0,>=1.0.0->hide_code) (2.2.0)
    Requirement already satisfied: jedi>=0.16 in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.18.1)
    Requirement already satisfied: pickleshare in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.7.5)
    Requirement already satisfied: setuptools>=18.5 in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (63.4.1)
    Requirement already satisfied: decorator in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (5.1.1)
    Requirement already satisfied: backcall in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.2.0)
    Requirement already satisfied: colorama in c:\users\tomas\anaconda3\lib\site-packages (from ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.4.5)
    Requirement already satisfied: pyrsistent!=0.17.0,!=0.17.1,!=0.17.2,>=0.14.0 in c:\users\tomas\anaconda3\lib\site-packages (from jsonschema>=2.6->nbformat->notebook<7.0.0,>=6.4.12->hide_code) (0.18.0)
    Requirement already satisfied: attrs>=17.4.0 in c:\users\tomas\anaconda3\lib\site-packages (from jsonschema>=2.6->nbformat->notebook<7.0.0,>=6.4.12->hide_code) (21.4.0)
    Requirement already satisfied: wcwidth in c:\users\tomas\anaconda3\lib\site-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->jupyter-console->jupyter<2.0.0,>=1.0.0->hide_code) (0.2.5)
    Requirement already satisfied: six>=1.5 in c:\users\tomas\anaconda3\lib\site-packages (from python-dateutil>=2.8.2->jupyter-client>=5.3.4->notebook<7.0.0,>=6.4.12->hide_code) (1.16.0)
    Requirement already satisfied: cffi>=1.0.1 in c:\users\tomas\anaconda3\lib\site-packages (from argon2-cffi-bindings->argon2-cffi->notebook<7.0.0,>=6.4.12->hide_code) (1.15.1)
    Requirement already satisfied: soupsieve>1.2 in c:\users\tomas\anaconda3\lib\site-packages (from beautifulsoup4->nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (2.3.1)
    Requirement already satisfied: webencodings in c:\users\tomas\anaconda3\lib\site-packages (from bleach->nbconvert->jupyter<2.0.0,>=1.0.0->hide_code) (0.5.1)
    Requirement already satisfied: pyparsing!=3.0.5,>=2.0.2 in c:\users\tomas\anaconda3\lib\site-packages (from packaging->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (3.0.9)
    Requirement already satisfied: pycparser in c:\users\tomas\anaconda3\lib\site-packages (from cffi>=1.0.1->argon2-cffi-bindings->argon2-cffi->notebook<7.0.0,>=6.4.12->hide_code) (2.21)
    Requirement already satisfied: parso<0.9.0,>=0.8.0 in c:\users\tomas\anaconda3\lib\site-packages (from jedi>=0.16->ipython>=7.23.1->ipykernel->jupyter<2.0.0,>=1.0.0->hide_code) (0.8.3)
    

    Installing C:\Users\tomas\anaconda3\lib\site-packages\hide_code\ -> hide_code
    Making directory: C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\auto-load-server-extension.txt -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\auto-load-server-extension.txt
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\auto-load.txt -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\auto-load.txt
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code.js -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code.js
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_config.json -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_config.json
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_config.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_config.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_html_exporter.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_html_exporter.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_latexpdf_exporter.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_latexpdf_exporter.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_latex_exporter.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_latex_exporter.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_pdf_exporter.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_pdf_exporter.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_preprocessor.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_preprocessor.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\hide_code_slides_exporter.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\hide_code_slides_exporter.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\LICENSE -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\LICENSE
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\utils.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\utils.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__init__.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__init__.py
    Making directory: C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\Templates\hide_code_article.tplx -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates\hide_code_article.tplx
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\Templates\hide_code_base_style.tplx -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates\hide_code_base_style.tplx
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\Templates\hide_code_basic.tpl -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates\hide_code_basic.tpl
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\Templates\hide_code_full.tpl -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates\hide_code_full.tpl
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\Templates\hide_code_slides.tpl -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\Templates\hide_code_slides.tpl
    Making directory: C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\test\test_hide_code.py -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test\test_hide_code.py
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\test\utf-8 test.html -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test\utf-8 test.html
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\test\utf-8 test.ipynb -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test\utf-8 test.ipynb
    Making directory: C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test\__pycache__
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\test\__pycache__\test_hide_code.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\test\__pycache__\test_hide_code.cpython-39.pyc
    Making directory: C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_config.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_config.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_html_exporter.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_html_exporter.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_latexpdf_exporter.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_latexpdf_exporter.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_latex_exporter.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_latex_exporter.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_pdf_exporter.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_pdf_exporter.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_preprocessor.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_preprocessor.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\hide_code_slides_exporter.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\hide_code_slides_exporter.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\utils.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\utils.cpython-39.pyc
    Copying: C:\Users\tomas\anaconda3\lib\site-packages\hide_code\__pycache__\__init__.cpython-39.pyc -> C:\Users\tomas\AppData\Roaming\jupyter\nbextensions\hide_code\__pycache__\__init__.cpython-39.pyc
    - Validating: ok
    
        To initialize this nbextension in the browser every time the notebook (or other app) loads:
        
              jupyter nbextension enable hide_code --user --py
        
    Enabling notebook extension hide_code/hide_code...
          - Validating: ok
    Enabling: hide_code
    - Writing config: C:\Users\tomas\.jupyter
        - Validating...
          hide_code  ok
    


```python
from IPython.display import display
from IPython.display import HTML
import IPython.core.display as di # Example: di.display_html('<h3>%s:</h3>' % str, raw=True)

# This line will hide code by default when the notebook is exported as HTML
di.display_html('<script>jQuery(function() {if (jQuery("body.notebook_app").length == 0) { jQuery(".input_area").toggle(); jQuery(".prompt").toggle();}});</script>', raw=True)

# This line will add a button to toggle visibility of code blocks, for use with the HTML export version
# di.display_html('''<button onclick="jQuery('.input_area').toggle(); jQuery('.prompt').toggle();">Toggle code</button>''', raw=True)
```


<script>jQuery(function() {if (jQuery("body.notebook_app").length == 0) { jQuery(".input_area").toggle(); jQuery(".prompt").toggle();}});</script>



```python
from dash import Dash, dcc, html, Input, Output
from jupyter_dash import JupyterDash
import plotly.express as px

app = JupyterDash(__name__)


app.layout = html.Div([
    html.H4('Interactive scatter plot with Iris dataset'),
    dcc.Graph(id="scatter-plot"),
    html.P("Filter by petal width:"),
    dcc.RangeSlider(
        id='range-slider',
        min=0, max=2.5, step=0.1,
        marks={0: '0', 2.5: '2.5'},
        value=[0.5, 2]
    ),
])


@app.callback(
    Output("scatter-plot", "figure"), 
    Input("range-slider", "value"))

def update_bar_chart(slider_range):
    df = px.data.iris() # replace with your own data source
    low, high = slider_range
    mask = (df['petal_width'] > low) & (df['petal_width'] < high)
    fig = px.scatter(
        df[mask], x="sepal_width", y="sepal_length", 
        color="species", size='petal_length', 
        hover_data=['petal_width'])
    return fig


app.run_server(mode="inline",debug=True, port=2223)
```

    Dash is running on http://127.0.0.1:2223/
    
    



<iframe
    width="100%"
    height="650"
    src="http://127.0.0.1:2223/"
    frameborder="0"
    allowfullscreen

></iframe>




```python
import pandas as pd
import numpy as np
import jupyter_dash as JupyterDash
import plotly.express as px
import os
```


```python
current_path = os.getcwd()
files = os.listdir(current_path + '\\Data\\')
df = pd.DataFrame()
for file in files:
    temp = pd.read_csv(current_path + '\\Data\\'+ file)
    temp['file_name'] = file
    df = pd.concat([df,temp])
df[['city','type']] = df.file_name.str.split('_', expand = True)
df.type = df.type.str[:-4]
df = df.drop(columns = 'file_name')
```


```python
print(df.columns)
print(len(df))
```

    Index(['Unnamed: 0', 'realSum', 'room_type', 'room_shared', 'room_private',
           'person_capacity', 'host_is_superhost', 'multi', 'biz',
           'cleanliness_rating', 'guest_satisfaction_overall', 'bedrooms', 'dist',
           'metro_dist', 'attr_index', 'attr_index_norm', 'rest_index',
           'rest_index_norm', 'lng', 'lat', 'city', 'type'],
          dtype='object')
    51707
    


```python


import plotly.graph_objects as go
import plotly.io as pio
pio.renderers.default = "notebook_connected"

fig1 = go.Figure()

cities = df["city"].drop_duplicates()


fig1.add_trace(go.Violin(x=df['city'][df['type'] == 'weekdays'],
                        y=df['realSum'][df['type'] == 'weekdays'],
                        legendgroup='weekdays',
                     
                        name='weekdays',
                        side='negative',
                        line_color='blue',
                        box_visible=True,
                        meanline_visible=True))


fig1.add_trace(go.Violin(x=df['city'][df['type'] == 'weekends'],
                    y=df['realSum'][df['type'] == 'weekends'],
                    legendgroup='weekends',
      
                    name='weekends',
                    side='positive',
                    line_color='orange',
                    box_visible=True,
                    meanline_visible=True))


#added spanmode to limit the density (before it was showing negative values due to kernel density estimation)
fig1.update_traces(meanline_visible=True, spanmode = 'hard')
fig1.update_layout(violingap=0, violingroupgap=0, violinmode='overlay', title ='AirBnB price distribution per city and weekday/weekend')
fig1.show()


```


<script type="text/javascript">
window.PlotlyConfig = {MathJaxConfig: 'local'};
if (window.MathJax && window.MathJax.Hub && window.MathJax.Hub.Config) {window.MathJax.Hub.Config({SVG: {font: "STIX-Web"}});}
if (typeof require !== 'undefined') {
require.undef("plotly");
requirejs.config({
    paths: {
        'plotly': ['https://cdn.plot.ly/plotly-2.12.1.min']
    }
});
require(['plotly'], function(Plotly) {
    window._Plotly = Plotly;
});
}
</script>





var gd = document.getElementById('8639239a-1726-497c-882a-7dba7fa32663');
var x = new MutationObserver(function (mutations, observer) {{
        var display = window.getComputedStyle(gd).display;
        if (!display || display === 'none') {{
            console.log([gd, 'removed!']);
            Plotly.purge(gd);
            observer.disconnect();
        }}
}});

// Listen for the removal of the full notebook cells
var notebookContainer = gd.closest('#notebook-container');
if (notebookContainer) {{
    x.observe(notebookContainer, {childList: true});
}}

// Listen for the clearing of the current output cell
var outputEl = gd.closest('.output');
if (outputEl) {{
    x.observe(outputEl, {childList: true});
}}

                        })                };                });            </script>        </div>


We can see that outliers of expensive AirBnB locations make the graph less readable.

**However, because the graph is interactive we can zoom in on the section of the graph that doesn't include outliers by selecting specific area on the graph.**
* We can also zoom into specific cities
* Hovering over each corresponding violin plot will also show us key labels for min/max/mean/median and interquartile ranges of prices for each city

**However let's plot the same graph after dropping outliers with values that are in the 0.5% of top values**


```python
di.display_html('<script>jQuery(function() {if (jQuery("body.notebook_app").length == 0) { jQuery(".input_area").toggle(); jQuery(".prompt").toggle();}});</script>', raw=True)

# search for outliers, which are largely represented at price data
for city in df.city.unique():
    df.loc[df.city == city, 'outliers'] = df.loc[df.city == city, 'realSum'] > df.loc[df.city == city, 'realSum'].quantile(0.995)

dflen1=len(df)
df1 = df.drop(df[df.outliers == True].index)
dflen2=len(df1)
print(f'Dropped ' + str(dflen1-dflen2) + ' outliers')
```


<script>jQuery(function() {if (jQuery("body.notebook_app").length == 0) { jQuery(".input_area").toggle(); jQuery(".prompt").toggle();}});</script>


    Dropped 3636 outliers
    


```python



import plotly.graph_objects as go
import plotly.io as pio
pio.renderers.default = "notebook_connected"

fig1 = go.Figure()

cities = df1["city"].drop_duplicates()


fig1.add_trace(go.Violin(x=df1['city'][df1['type'] == 'weekdays'],
                        y=df1['realSum'][df1['type'] == 'weekdays'],
                        legendgroup='weekdays',
                     
                        name='weekdays',
                        side='negative',
                        line_color='blue',
                        box_visible=True,
                        meanline_visible=True))


fig1.add_trace(go.Violin(x=df1['city'][df1['type'] == 'weekends'],
                    y=df1['realSum'][df1['type'] == 'weekends'],
                    legendgroup='weekends',
      
                    name='weekends',
                    side='positive',
                    line_color='orange',
                    box_visible=True,
                    meanline_visible=True))


#added spanmode to limit the density (before it was showing negative values due to kernel density estimation)
fig1.update_traces(meanline_visible=True, spanmode = 'hard')
fig1.update_layout(violingap=0, violingroupgap=0, violinmode='overlay', title ='AirBnB price distribution per city and weekday/weekend')
fig1.show()


```


      File "C:\Users\tomas\AppData\Local\Temp\ipykernel_28592\688385009.py", line 1
        <script>
        ^
    SyntaxError: invalid syntax
    
