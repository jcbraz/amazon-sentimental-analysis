# tm-project

## TODO

- [x] Cross validation in TF-IDF vectorization & Logistic Regression
- [x] Accuracy Improvement
- [x] Task Number 14
- [ ] Check other metrics (F1-score, Precision, Recall)
  
#### Side Note: Even if two models have the same overall accuracy, they can make errors on different instances. The chi-square test checks whether the distribution of errors is independent for the two models. A p-value close to zero suggests that the errors are not distributed independently, meaning the models tend to make errors on different subsets of the data.

## Reproduce development environment

1. Clone the repository (recommend to clone though the terminal)
2. Access the repository folder
3. Run
   
    ```bash
    python3 -m venv .venv
    ```
4. Run
   
    ```bash
    source .venv/bin/activate
    ```
5. Install dependencies
   
    ```bash
    pip3 install -r requirements.txt
    ```
6. Open the notebook on vscode and select the .venv kernel
7. Done! You can now run the notebook and reproduce the development environment
