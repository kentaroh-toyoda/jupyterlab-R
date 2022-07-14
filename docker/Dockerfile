FROM jupyter/r-notebook:latest
USER jovyan
WORKDIR /home/jovyan

RUN pip install jupyterlab-vim
RUN pip install jupyterlab-fonts
RUN pip install tqdm
RUN pip install ipywidgets
RUN jupyter labextension install @jupyter-widgets/jupyterlab-manager
RUN jupyter labextension install jupyterlab_onedarkpro

ENTRYPOINT ["jupyter", "lab"]
