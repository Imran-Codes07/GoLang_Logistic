# Logistic Regression in GoLang

This repository contains a basic implementation of a Logistic Regression model in Go (Golang). The model is evaluated on the Titanic dataset, achieving an accuracy of 0.7333, which is comparable to scikit-learn's 0.737 on the same data.

## Features

* Built from scratch in Go, without external machine learning libraries.
* Evaluated on a cleaned version of the Titanic dataset (non-null rows only).
* Simple and educational codebase for learning purposes.

## Files

* `main.go` – Core implementation of the logistic regression model.
* `data.csv` – Preprocessed Titanic dataset used for training and evaluation.
* `go.mod` – Go module file for dependency management.
* `README.md` – Project documentation.

## Getting Started

### Prerequisites

* Go 1.16 or higher installed on your system.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Imran-Codes07/GoLang_Logistic.git
   cd GoLang_Logistic
   ```



2. Run the program:

   ```bash
   go run main.go
   ```



## Model Evaluation

* Accuracy on Titanic dataset: **0.7333**
* For comparison, scikit-learn's logistic regression yields: **0.737**

*Note: This implementation does not include regularization.*

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, such as adding regularization, enhancing data preprocessing, or optimizing performance.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

For more projects and tutorials, visit [Imran Codes](https://imrancodes.com/).

