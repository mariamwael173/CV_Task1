# Beans Dataset – Downloader

This ZIP contains a small downloader script, not the image dataset itself.
When you run the script, it downloads the public Beans dataset and creates:

Beans_Dataset/
  train/
    angular_leaf_spot/
    bean_rust/
    healthy/
  validation/
    angular_leaf_spot/
    bean_rust/
    healthy/
  test/
    angular_leaf_spot/
    bean_rust/
    healthy/

## Steps in Visual Studio Code

1. Extract this ZIP.
2. Open the extracted folder in Visual Studio Code.
3. Open Terminal > New Terminal.
4. Install the required libraries:

   pip install datasets pillow

5. Run:

   python download_beans.py

An internet connection is required for the download. The original train,
validation, and test splits are kept separate.
Dataset source: Hugging Face dataset `AI-Lab-Makerere/beans`.
