# Example Jupyter notebook with Binder integration

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jperkel/example_notebook/master)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jperkel/example_notebook/blob/master/My_sample_notebook.ipynb)

This simple [Jupyter](https://jupyter.org/) notebook demonstrates how the computational notebook format allows users to interleave text, code, and results in a single file.

But, unless you have Jupyter notebook installed on your computer, all you can do is view the notebooks, not play with them. (See for yourself: If you click `My_sample_notebook.ipynb` in this GitHub repository, you will be able to read the notebook, but only as a static document.) This is where [Binder](https://mybinder.org) comes in. Binder is a free, open-source, web service that packages Jupyter notebooks inside an executable container, which can be run within a web browser, no installation required.

1. Click the `launch binder` button above. Once the demo launches, click `My_sample_notebook.ipynb` in the file listing.
2. Run the notebook by selecting `Cell > Run All`.
3. Take a look at the graph below the fourth cell (labeled 'In [4]').
4. Uncomment the line in the fourth cell that reads `# ax.plot (range(25), ar)` by removing the leading hashtag (`#`)
5. Click `Cell > Run All` again. You should see a change in the graph below that cell.
