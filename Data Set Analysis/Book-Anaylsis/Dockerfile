FROM jupyter/datascience-notebook
WORKDIR /Cloud_Assignment
COPY books.csv /Cloud_Assignment
COPY Book_series_analysis.ipynb /Cloud_Assignment
EXPOSE 8080


CMD ["jupyter", "notebook", "--ip='0.0.0.0'", "--port=8080", "--no-browser", "--allow-root"]
