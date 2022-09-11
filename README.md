# ML ZOOMCAMP
- Self-Paced ML ZoomCamp by Alex Grigorev of DataTalks.Club - https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp
- Youtube playlist - https://www.youtube.com/playlist?list=PL3MmuxUbc_hIhxl5Ji8t4O6lPAOpHaCLR

### Set up & Daily

#### Local Env
- Open GitBash, navigate to - `cd ~shiva/shiva_local`
- One time - Clone github repo `gh repo clone Shiva-Mantri/MLZoomCamp`
- `cd MLZoomCamp`
- One time - Set up venv - `~shiva/anaconda3/python -m venv ./venv_mlzc`
- Activate venv - `source ./venv_mlzc/Scripts/activate`
- One time - Configure Jupyter to use current kernel `ipython kernel install --name "venv_mlzc" --user`
  - Source: https://queirozf.com/entries/jupyter-kernels-how-to-add-change-remove


### Week 1 - Introduction to ML
- https://github.com/alexeygrigorev/mlbookcamp-code/tree/master/course-zoomcamp/01-intro 
- Come up with a model to make a prediction - g(X) ~ y
- Numpy vs Pandas
  - Numpy is for performing numerical calculations, Pandas is for processing tabular data.
  - Pandas is built-on top of Numpy. 
  - https://www.educba.com/pandas-vs-numpy/
  - https://www.geeksforgeeks.org/difference-between-pandas-vs-numpy/

#### Supervised Learning - Showing model different items and teach expected result (target variable) for each of the item
- Regression - If the prediction output is a number, e.g. cost of car, house etc
- Classification - If the prediction output is one of many classes/types, e.g. spam or not, what is image - car, cat, dog etc
  - Binary classification is when output is one of two types - e.g. spam or not
- Ranking - Score items 0 - 1 for all the list of provided, e.g. on an ecommerce site, rank items to display

#### CRISP-DM - Cross-Industry Standard Process for Data Mining
CRISP-DM, which stands for Cross-Industry Standard Process for Data Mining, is an industry-proven way to guide your data mining efforts. As a methodology, it includes descriptions of the typical phases of a project, the tasks involved with each phase, and an explanation of the relationships between these tasks. 
- Detailed introduction for CRISP-DM and alternate OSEMN model https://towardsdatascience.com/the-data-science-process-a19eb7ebc41b
- Includes a visual for substeps and a RACI matrix - https://towardsdatascience.com/crisp-dm-ready-for-machine-learning-projects-2aad9172056a
- Official IBM Site - https://www.ibm.com/docs/en/spss-modeler/saas?topic=guide-introduction-crisp-dm (use side frame in site for navigation). 
  - PDF version: https://www.ibm.com/docs/it/SS3RA7_18.3.0/pdf/ModelerCRISPDM.pdf

#### TO DO
- Reimplement vec_vec_mul, matrix_vec_mul, mat-mat mul and compare with numpy.dot mul
- HW