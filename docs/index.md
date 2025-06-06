<p align="center">
  <img width="600" src="static/cookiecutter.svg">
</p style = "margin-bottom: 2rem;">
<style>
  .md-typeset h1,
  .md-content__button {
    display: none;
  }
</style>

---

This is a modern Cookiecutter template that can be used to initiate a Python project with all the necessary tools for development, testing, and deployment. It supports the following features:

- [uv](https://docs.astral.sh/uv/) for dependency management
- Pre-commit hooks with [pre-commit](https://pre-commit.com/)
- Testing with [pytest](https://docs.pytest.org/en/7.1.x/)
- Documentation with [MkDocs](https://www.mkdocs.org/)
- Containerization with [Docker](https://www.docker.com/)

An example of a repository generated with this package can be found [here](https://github.com/fpgmaas/cookiecutter-uv-example).

## Quickstart

On your local machine, navigate to the directory in which you want to
create a project directory, and run the following command:

```bash
uvx cookiecutter https://github.com/fpgmaas/cookiecutter-uv.git
```

or if you don't have `uv` installed yet:

```bash
pip install cookiecutter
cookiecutter https://github.com/fpgmaas/cookiecutter-uv.git
```

Follow the prompts to configure your project. Once completed, a new directory containing your project will be created. Then navigate into your newly created project directory and follow the instructions in the `README.md` to complete the setup of your project.

### Acknowledgements

This project is partially based on [Audrey
Feldroy's](https://github.com/audreyfeldroy) great
[cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage).
