# Stack Generator

Stack generator is a CLI tool that allows you to generate an application template in one command.

## Installation

```bash
pip install stack-gen
```

## Requirements

- A repository containing a [cookiecutter template](https://www.cookiecutter.io/templates) with:
  - 'requirements.txt' file containing required dependencies

    ```bash
    cookiecutter
    GitPython
    python-dotenv
    ```

## Usage

```bash
sg -r=fastapi-generator -u=valdo77
```

## Help

```bash
Options:
  -r,   --repository TEXT        Name of repository containing the template to generate
  -u    --user TEXT              Name of github's user owning the repository
  -gac  --access_token TEXT      Github access token used to manage branch protection on generation (optional)
                                  
  --help                      Show this message and exit.
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
