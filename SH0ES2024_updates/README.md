## SH0ES2024_updates
In this folder, we store the data files pertaining to the updated 2024 SH0ES-team calibration, as described in more detail in [arXiv:YYMM.NNNNN](link-to-paper). Including
- MW cluster Cepheids ([Riess et al. 2022b](https://iopscience.iop.org/article/10.3847/1538-4357/ac8f24))
- Updated MW metallicities ([Bhardwaj et al. 2023](https://iopscience.iop.org/article/10.3847/2041-8213/acf710))
- Updated SN covariance ([Murakami et al. 2023](https://iopscience.iop.org/article/10.1088/1475-7516/2023/11/046))
- SMC as an anchor galaxy ([Breuval et al. 2024](https://iopscience.iop.org/article/10.3847/1538-4357/ad630e))

File content:
- **y_R24.txt** is the data vector
- **C_R24.txt** is the covariance matrix
- **L_R24.txt** is the design matrix
- **q_R24.txt** is a list of the model parameters

We use the following SNIa ID convention:
- CC SNe: the format is ''hostgalaxy\_SN\_ID''
- HF SNe: the format is ''SN\_ID''

ID is a number representing the SN survey. Following the Pantheon+ convention, the identification is the following:

{1:'SDSS', 4:'SNLS', 5:'CSP', 10:'DES', 15:'PS1MD', 18:’CNIa0.02’, 50:'LOWZ/JRK07', 51:'LOSS1', 56:'SOUSA', 57:’LOSS2’, 61:'CFA1', 62:'CFA2', 63:'CFA3S', 64:'CFA3K' ,65:'CFA4p2', 66:'CFA4p3', 100:'HST', 101:'SNAP', 106:'CANDELS', 150:'FOUND'}.
