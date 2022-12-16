# Software-Bugs-detection-using-SMLT
In this project, we are going to find whether our software is buggy or not with the best accuracy using machine learning techniques. In this project, we will be having 4 modules. In these modules,  we will be doing data pre processing, data visualization, and other two modules about implementing the algorithms.


Dataset:

https://www.kaggle.com/semustafacevik/software-defect-prediction?select=jm1.csv


Attribute Information:

loc : numeric % McCabe's line count of code
v(g) : numeric % McCabe "cyclomatic complexity"
ev(g) : numeric % McCabe "essential complexity"
iv(g) : numeric % McCabe "design complexity"
n : numeric % Halstead total operators + operands
v : numeric % Halstead "volume"
l : numeric % Halstead "program length"
d : numeric % Halstead "difficulty"
i : numeric % Halstead "intelligence"
e : numeric % Halstead "effort"
b : numeric % Halstead
t : numeric % Halstead's time estimator
lOCode : numeric % Halstead's line count
lOComment : numeric % Halstead's count of lines of comments
lOBlank : numeric % Halstead's count of blank lines
lOCodeAndComment : numeric
uniq_Op : numeric % unique operators
uniq_Opnd : numeric % unique operands
total_Op : numeric % total operators
total_Opnd : numeric % total operands
branchCount : numeric % of the flow graph
defects : {false,true} % module has/has not one or more reported defects

