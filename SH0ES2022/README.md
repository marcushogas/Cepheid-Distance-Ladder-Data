## SH0ES2022
In this folder, we store the data files pertaining to the baseline 2022 SH0ES team ([Riess et al. 2022a](https://iopscience.iop.org/article/10.3847/2041-8213/ac5c5b)) calibration of the cosmic distance ladder.
- **[y_R22.txt](/SH0ES2022/y_R22.txt)** is the data vector
- **[C_R22.txt](/SH0ES2022/C_R22.txt)** is the covariance matrix
- **[L_R22.txt](/SH0ES2022/L_R22.txt)** is the design matrix
- **[q_R22.txt](/SH0ES2022/q_R22.txt)** is a list of the model parameters

We use the following SNIa ID convention:
- CC SNe: the format is ''hostgalaxy\_SN\_ID''
- HF SNe: the format is ''SN\_ID''

ID is a number representing the SN survey. Following the Pantheon+ convention, the identification is the following:

{1:'SDSS', 4:'SNLS', 5:'CSP', 10:'DES', 15:'PS1MD', 18:’CNIa0.02’, 50:'LOWZ/JRK07', 51:'LOSS1', 56:'SOUSA', 57:’LOSS2’, 61:'CFA1', 62:'CFA2', 63:'CFA3S', 64:'CFA3K' ,65:'CFA4p2', 66:'CFA4p3', 100:'HST', 101:'SNAP', 106:'CANDELS', 150:'FOUND'}.

The Jupyter notebook **[Read_and_Fit_R22.ipynb](/SH0ES2022/Read_and_Fit_R22.ipynb)** can be used to read the files and also provides a linear fit.
