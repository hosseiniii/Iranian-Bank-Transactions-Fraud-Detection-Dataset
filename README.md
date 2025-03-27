# Iranian Bank Transactions Fraud Detection (IBT-FD) Dataset

The **Iranian Bank Transactions Fraud Detection (IBT-FD)** dataset is prepared for research and development in fraud detection. The dataset consists of anonymized financial transaction features along with a binary fraud label.

## Dataset Description

The dataset contains **22 anonymized numerical features** along with a **Fraud** column, which indicates whether a transaction is fraudulent (`1`) or not (`0`). The original transaction details have been anonymized to protect privacy and comply with data security regulations.

### Features:

- `feature_0` to `feature_21`: Anonymized numerical features representing transaction attributes.
- `Fraud`: Target variable (`1` for fraudulent transactions, `0` for non-fraudulent transactions).

### Sample Data:
| feature_0 | feature_1 | ... | feature_21 | Fraud |
|-----------|-----------|-----|------------|-------|
| -0.21999  | -0.28898  | ... | -0.57917   | 0     |
| 1.87441   | -0.28898  | ... | -0.57917   | 0     |
| -0.28066  | 1.57993   | ... | -0.57917   | 0     |

## Disclaimer

- **The dataset features have been anonymized** and do not correspond to actual transaction attributes.
- The dataset is provided **for research purposes only** and should not be used for real-world financial decision-making.

## Citation

If you use this dataset in your research, please cite it as:

```Hosseini, Seyyed Sadegh. “Iranian Bank Transactions Fraud Detection (IBT-FD) Dataset”. Zenodo, March 27, 2025. https://doi.org/10.5281/zenodo.15097923.```
