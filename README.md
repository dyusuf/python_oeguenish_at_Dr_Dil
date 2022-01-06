# python_oeguenish_at_Dr_Dil

This cookiecutter creates a simple boilerplate for a Jupyter Book.

## Usage

### Building the book

If you'd like to develop and/or build the python_oeguenish_at_Dr_Dil book, you should:

1. Clone this repository
2. Run `pip install -r requirements.txt` (it is recommended you do this within a virtual environment)
3. (Optional) Edit the books source files located in the `python_oeguenish_at_dr_dil/` directory
4. Run `jupyter-book clean python_oeguenish_at_dr_dil/` to remove any existing builds
5. Run `jupyter-book build python_oeguenish_at_dr_dil/`

A fully-rendered HTML version of the book will be built in `python_oeguenish_at_dr_dil/_build/html/`.

### Hosting the book

Please see the [Jupyter Book documentation](https://jupyterbook.org/publish/web.html) to discover options for deploying a book online using services such as GitHub, GitLab, or Netlify.

For GitHub and GitLab deployment specifically, the [cookiecutter-jupyter-book](https://github.com/executablebooks/cookiecutter-jupyter-book) includes templates for, and information about, optional continuous integration (CI) workflow files to help easily and automatically deploy books online with GitHub or GitLab. For example, if you chose `github` for the `include_ci` cookiecutter option, your book template was created with a GitHub actions workflow file that, once pushed to GitHub, automatically renders and pushes your book to the `gh-pages` branch of your repo and hosts it on GitHub Pages when a push or pull request is made to the main branch.

## Contributors

We welcome and recognize all contributions. You can see a list of current contributors in the [contributors tab](https://github.com/dyusuf/python_oeguenish_at_dr_dil/graphs/contributors).

## Credits

This project is created using the excellent open source [Jupyter Book project](https://jupyterbook.org/) and the [executablebooks/cookiecutter-jupyter-book template](https://github.com/executablebooks/cookiecutter-jupyter-book).
