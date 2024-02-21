# How to make SQL agent using langchain for postgress database

## Installation procedure for local development

- Install [Miniconda](https://repo.anaconda.com/miniconda/Miniconda3-py310_23.3.1-0-Windows-x86_64.exe) from https:/.conda.io/en/latest/miniconda.html#windows-installers (for python)

- After Anaconda installation, go to search and run Anaconda Prompt and create virtual environment using following commands

    `conda create -y -n gpt python=3.11.0`

- Activate the conda environment

    `conda activate gpt`
    
- Clone the repository to your local machine. 

    `git clone https://github.com/ashishkrb7/SQL-gent-using-langchain.git sqlagent` 

- Go to working directory

    `cd sqlagent`

- Install the required dependencies using 

    `python -m pip install -r requirements.txt`

- Create .env file in the project root and add the following environment variables:

```txt
api_type = ""
api_base = ""
api_version = ""
OPENAI_API_KEY = 
PG_URI = 
LANGCHAIN_TRACING_V2=
LANGCHAIN_API_KEY = ""
LANGCHAIN_PROJECT = ""
```

## Project Structure

```txt
    .env
    .gitignore
    notebook.ipynb
    README.md
    requirements.txt
```

## Contributing

We welcome contributions to improve this project! If you find any issues or want to add new features, please feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to get in touch for any collaborative work in the AI/ML and tech domain!

## Acknowledgments

If you have any questions or need further assistance, please don't hesitate to reach out.

Happy coding!
