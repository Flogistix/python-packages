# python_packages

This is the Flogistix python package index.  

You can use pip to install packages from this repo with the following syntax:  

`pip install test_package --extra-index-url=https://flogistix.github.io/python_packages/`

If you want to leave off the `--extra-index-url` flag, you can run the following commands to add it to your pip config:

```
pip config --user set global.index-url https://flogistix.github.io/python_packages
pip config --user set global.trusted-host flogistix.github.io
```

Currently, adding a new package to the repo is a manual process.  Either review the simple html of this repo and follow the same pattern, and/or review this [blog-post](https://www.freecodecamp.org/news/how-to-use-github-as-a-pypi-server-1c3b0d07db2/)
