# Deep Learning For Biology

Welcome to the companion repository for **Deep Learning for Biology**, an O’Reilly book that explores how modern machine learning methods can be applied to DNA, RNA, proteins, and cellular data to investigate and model biological problems.

![Book Cover](assets/book-cover.png)

The goal of this repo is to make it easy for students, practitioners, and researchers to follow along with the book’s content, and also to experiment, extend, and apply the methods discussed in the book to their own biological problems.

This repo contains **Executable notebooks** for the five main project chapters of the book:
  - Chapter 2: *Learning the Language of Proteins*
  - Chapter 3: *Learning from DNA Sequences*
  - Chapter 4: *Understanding Drug–Drug Interactions Using Graphs*
  - Chapter 5: *Detecting Skin Cancer in Medical Images*
  - Chapter 6: *Learning Spatial Organization Patterns Within Cells*

⚠️ Note: the text content of the chapters has been stripped; the notebooks contain only the code blocks. Please consult the book (print or PDF) for the full content.

## Getting Started

You can run the notebooks directly on **Google Colab** and select a GPU backend (usage limits apply). Simply visit [colab](https://colab.research.google.com/) and upload one of the notebook files in `./notebooks`.

ℹ️ Instructions on how to run the notebooks in more controlled environments will be added in the future.

## Contributing

We welcome contributions!

- **Discussions**: Please use the Discussions tab for questions, clarifications, and sharing ideas.
- **Issues:** Use Issues only for reproducible bugs in the codebase (e.g. broken code, dependency errors, incorrect results). This separation helps keep bug reports from getting lost in general conversation.
- **Pull Requests:** Contributions that add new utilities, improve existing implementations, or expand the notebooks are very welcome! Please keep PRs focused and include a clear description of the change.

## Citations

If you use `dlfb` in your work and would like to cite it, you can cite the book like this:

```bibtex
@book{deep_learning_for_biology,
  title     = {Deep Learning for Biology},
  author    = {Ravarani, C. and Latysheva, N.},
  publisher = {O’Reilly Media},
  year      = {2025},
}
```

Or more plainly as "Ravarani & Latysheva, Deep Learning for Biology, O’Reilly Media, 2025."

## License

- The **code** in this repository (including the `dlfb` library and notebooks) is licensed under the Apache 2.0 License.
- The **book text** remains © 2025 Charles Ravarani and Natasha Latysheva, published by O’Reilly Media. All rights reserved.

## Troubleshooting

- Occasionally you will need to _Restart Session_ if an import is not working as expected (e.g. `numpy`).
