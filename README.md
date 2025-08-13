<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="readmeai/assets/logos/purple.svg" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>

# NN-TASK-1

<em>Bird Classification with Perceptron and Adaline</em>

<!-- BADGES -->
<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Python-3776AB.svg?style=default&logo=Python&logoColor=white" alt="Python">

</div>
<br>

---

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
    - [Project Index](#project-index)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Overview

NN-TASK-1 is a Python-based project for classifying bird species using a **Single-Layer Perceptron** and **Adaline** algorithms.  
It provides a **Tkinter GUI** for selecting features, classes, learning rates, epochs, and bias options, with visualization of decision boundaries.

---

## Features

- Interactive **Tkinter GUI** for feature and class selection  
- Supports **Perceptron** and **Adaline** classification  
- Normalizes numeric features with **MinMaxScaler**  
- Calculates **confusion matrix** and **accuracy**  
- Plots **decision boundary** for selected features  
- Handles missing values in the `gender` column  

---

## Project Structure

```sh
└── NN-Task-1/
    ├── birds.csv
    └── main.py

### Project Index

<details open>
	<summary><b><code>NN-TASK-1/</code></b></summary>
	<!-- __root__ Submodule -->
	<details>
		<summary><b>__root__</b></summary>
		<blockquote>
			<div class='directory-path' style='padding: 8px 0; color: #666;'>
				<code><b>⦿ __root__</b></code>
			<table style='width: 100%; border-collapse: collapse;'>
			<thead>
				<tr style='background-color: #f8f9fa;'>
					<th style='width: 30%; text-align: left; padding: 8px;'>File Name</th>
					<th style='text-align: left; padding: 8px;'>Summary</th>
				</tr>
			</thead>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='NN-Task-1/blob/master/main.py'>main.py</a></b></td>
					<td style='padding: 8px;'>Python script with Tkinter GUI to select features, classes, learning rate, epochs, and bias, then train and evaluate Perceptron and Adaline classifiers on bird dataset, including normalization, confusion matrix, and plotting decision boundaries.</td>
				</tr>
				<tr style='border-bottom: 1px solid #eee;'>
					<td style='padding: 8px;'><b><a href='NN-Task-1/blob/master/birds.csv'>birds.csv</a></b></td>
					<td style='padding: 8px;'>Dataset containing bird attributes including gender, body mass, beak length, beak depth, fin length, and bird category used for training and testing classifiers.</td>
				</tr>
			</table>
		</blockquote>
	</details>
</details>
## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** Python 3.x  
- **Libraries:** `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tkinter`  

### Installation

Build NN-Task-1 from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    git clone ../NN-Task-1
    ```

2. **Navigate to the project directory:**

    ```sh
    cd NN-Task-1
    ```

3. **Install the dependencies:**

    ```sh
    pip install numpy pandas matplotlib scikit-learn
    ```

### Usage

Run the project with:

```sh
python main.py
```
After running the project, use the GUI to configure the classification task:

- **Features:** Select `Feature 1` and `Feature 2` from the available bird attributes  
- **Classes:** Choose which classes to classify (`A & B`, `A & C`, or `B & C`)  
- **Learning Rate & Epochs:** Set the learning rate and number of training epochs  
- **Bias:** Optionally enable adding a bias term  
- **Algorithm:** Choose between **Perceptron** or **Adaline**  

The application will:

- Train the selected model on the dataset  
- Display the **confusion matrix** and **accuracy**  
- Plot the **decision boundary** for the chosen features  

### Testing

This project does not include an automated test suite.  
Testing is performed manually through the GUI by training classifiers and verifying the results and decision boundaries.
## Roadmap

- [X] **Task 1:** Implement Perceptron and Adaline classifiers with GUI  
- [ ] **Task 2:** Add support for more bird species  
- [ ] **Task 3:** Implement model saving and loading
## Contributing

- **💬 Join the Discussions:** Share your insights, provide feedback, or ask questions.  
- **🐛 Report Issues:** Submit bugs found or log feature requests for the `NN-Task-1` project.  
- **💡 Submit Pull Requests:** Review open PRs, and submit your own PRs.  

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository:** Start by forking the project repository to your LOCAL account.  
2. **Clone Locally:** Clone the forked repository to your local machine using a git client.  
    ```sh
    git clone NN-Task-1
    ```  
3. **Create a New Branch:** Always work on a new branch with a descriptive name.  
    ```sh
    git checkout -b new-feature-x
    ```  
4. **Make Your Changes:** Develop and test your changes locally.  
5. **Commit Your Changes:** Commit with a clear message describing your updates.  
    ```sh
    git commit -m 'Implemented new feature x.'
    ```  
6. **Push to LOCAL:** Push the changes to your forked repository.  
    ```sh
    git push origin new-feature-x
    ```  
7. **Submit a Pull Request:** Create a PR against the original project repository. Clearly describe the changes and motivations.  
8. **Review:** Once your PR is reviewed and approved, it will be merged into the main branch.

</details>
## Acknowledgments

- **Original Dataset:** `birds.csv`  
- **Inspiration:** Tutorials on Perceptron and Adaline algorithms  
- **Libraries Used:** `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tkinter`  

<div align="right">
[![][back-to-top]](#top)
</div>
