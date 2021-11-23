# 4020_ThesisB
Repository containing all code relating to the developement and creation of the MMAN4020 Thesis B Final Report


env\Scripts\activate.bat

python -m ipykernel install --name=env

jupyter nbextension enable --py --sys-prefix widgetsnbextension
jupyter nbextension enable --py --sys-prefix gmaps
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter lab build