# SOP_documentation
CAFE Public Data Standard Operating Procedure

The rendered handbook is located at [https://climate-cafe.github.io/SOP_documentation/](https://climate-cafe.github.io/SOP_documentation/).

## How to contribute to this SOP handbook?

If you have read/write access to this page, you can directly open a new feature and add your changes. However, we strongly suggest opening a PR and letting others review your code before merging it into the final version. If you do not have access to this page, please fork the repo and submit a PR.

## Adding a New Sidebar Link

To add a new sidebar link to the handbook, follow these steps:

1. Edit the `_toc.yml` file in the `handbook` folder.
2. Make sure the name in `_toc.yml` is the same as your `.md` file name (e.g., `tutorial.md`).
3. Add the necessary content to your new `.md` file.
4. Ensure your new sidebar link is correctly configured in `_toc.yml`.

For more help on using JupyterBook for documentation, refer to the [JupyterBook documentation](https://jupyterbook.org/en/stable/intro.html).

## Test your contribution on your local system

Run the following commands in the terminal:

```bash
git clone https://github.com/Climate-CAFE/SOP_documentation.git
cd SOP_documentation
mkdir .env
python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
jupyter-book build --all handbook
```

Navigate to the browser to see the SOP handbook with your contribution. Make sure everything looks good before opening a pull request.
```