# 🧰 How to Complete The Assignments

You may complete the notebook using **any ONE** of the following methods:

---

## ✅ Option 1: Kaggle (Recommended for Beginners)

1. Go to Kaggle.

2. Open the dataset using the link provided in the task's readme.

3. Click **New Notebook**

4. Write your solution inside Kaggle Notebook.

5. Download the notebook as `.ipynb`

6. Push it to your GitHub repository.

Why choose this?

* No installation required
* Dataset already attached
* Fast and simple

---

## ✅ Option 2: Local Jupyter Notebook

1. Download the dataset from Kaggle.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open Jupyter:

```bash
jupyter notebook
```

4. Create `notebook.ipynb`
5. Place dataset in same folder
6. Work normally

Why choose this?

* Best for learning real development setup
* Good practice for future ML projects

---

## ✅ Option 3: Google Colab

1. Download dataset locally.
2. Upload dataset to:

   * Google Drive
3. Open Google Colab:
   [https://colab.research.google.com](https://colab.research.google.com)
4. Create new notebook.
5. Mount drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

6. Load dataset from Drive path.

Why choose this?

* No local installation
* Free GPU (not needed here, but useful later)

---

# 📌 Important Notes

* Your final submission must be pushed to GitHub.
* If using Kaggle or Colab, download the final notebook and upload it to your repository.
---