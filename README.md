# README.md

## **Support Vector Machines (SVM) Tutorial**

This tutorial demonstrates the use of Support Vector Machines (SVM) with different kernels on the Iris dataset. It highlights how kernel choice and hyperparameter tuning impact model performance, with detailed visualizations and explanations.

---

### **1. Purpose of the Tutorial**

The goal of this tutorial is to:

* Understand the theory and application of Support Vector Machines.
* Explore the impact of different SVM kernels (`linear`, `polynomial`, and `RBF`) on classification tasks.
* Visualize key aspects of SVM, such as feature importance and support vectors.
* Conduct sensitivity analysis for hyperparameters `C` and `gamma`.
* Provide a comprehensive guide to applying SVM to real-world datasets.

---

### **2. Features**

* **Dataset:** Iris dataset, containing three classes of flowers (`Setosa`, `Versicolor`, `Virginica`).
* **Preprocessing:**
  * Standardization of features.
  * Splitting data into training and testing subsets.
* **Kernel Exploration:**
  * `Linear`, `Polynomial`, and `RBF` kernels.
* **Hyperparameter Tuning:**
  * Uses `GridSearchCV` for parameter optimization.
* **Visualization:**
  * Confusion matrices.
  * Feature importance.
  * Support vector highlights using PCA.
  * Sensitivity analysis for `C` and `gamma`.

---

### **3. Instructions for Running the Code**

#### **Prerequisites**

Ensure you have the following installed:

* Python (>= 3.7)
* Libraries:
  * `pandas`
  * `numpy`
  * `scikit-learn`
  * `matplotlib`
  * `seaborn`

You can install the required libraries using the command:

<pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary select-none">bash</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center select-none py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-bash">pip install pandas numpy scikit-learn matplotlib seaborn
</code></div></div></pre>

#### **Steps to Run**

1. Clone this repository or copy the tutorial notebook to your local system.
2. Open the notebook or script in your preferred Python environment (e.g., Jupyter Notebook, VS Code).
3. Run the cells step-by-step to:
   * Load and preprocess the Iris dataset.
   * Train and evaluate SVM models using different kernels.
   * Visualize results and perform sensitivity analysis.
4. Modify hyperparameters or experiment with additional kernels as needed.

---

### **4. Folder Structure**

<pre class="!overflow-visible"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary dark:bg-gray-950"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary select-none">bash</div><div class="sticky top-9 md:top-[5.75rem]"><div class="absolute bottom-0 right-2 flex h-9 items-center"><div class="flex items-center rounded bg-token-sidebar-surface-primary px-2 font-sans text-xs text-token-text-secondary dark:bg-token-main-surface-secondary"><span class="" data-state="closed"><button class="flex gap-1 items-center select-none py-1"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-sm"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Copy code</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="!whitespace-pre hljs language-bash">.
├── README.md              # Documentation for the tutorial
├── svm_tutorial.ipynb     # Main Jupyter Notebook for the tutorial
└── LICENSE                # License file for usage conditions
</code></div></div></pre>

---

### **5. License**

This project is licensed under the MIT License. See the LICENSE file for details.

---

### **6. Contact**

If you have any questions or suggestions, feel free to reach out to the repository owner or contributor.
