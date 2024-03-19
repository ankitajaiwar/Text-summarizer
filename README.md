# Text Summarization 

## Overview

This project aims to develop an automated text summarization system using advanced techniques in natural language processing. The system condenses lengthy documents into concise summaries, facilitating efficient information extraction and comprehension.

## Technologies Used

- **AWS**: Utilized for workflow automation and cloud-based services.
- **Docker**: Used for containerization, ensuring consistency across different environments.
- **Python**: The primary programming language for implementing text summarization functionalities.
- **Git**: Employed for version control, enabling collaboration and tracking of project changes.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ankitajaiwar/Text-summarizer.git

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   python app.py

## AWS Deployment

1. Build the Docker image:
   ```bash
   docker build -t text-summarization .

2. Tag the Docker image:
   ```bash
   docker tag text-summarization:latest <aws_account_id>.dkr.ecr.<region>.amazonaws.com/text-summarization:latest

3. Push the Docker image to Amazon ECR:
  ```bash
     docker push <aws_account_id>.dkr.ecr.<region>.amazonaws.com/text-summarization:latest
```


## Project Structure

### `.github/workflows`
- Contains the AWS workflow configuration for automating project tasks.

### `artifacts`
- Directory for storing project artifacts and outputs.

### `config`
- Holds configuration files, including pipelines for workflow management.

### `research`
- Directory for research-related documents and findings.

### `src/textSummarizer`
- Source code for the text summarization functionalities.

### `app.py`, `main.py`
- Application files containing scripts for various project components.

### `params.yaml`, `requirements.txt`, `setup.py`
- Configuration and dependency management files for the project.

### `Dockerfile`
- Configuration for building the Docker container for the project.

### `.gitignore`
- Specifies files and directories to be ignored by version control.

### `README.md`
- Provides project documentation, including an overview, usage instructions, and technology stack.

## Contributors

- Ankita Jaiwar (@ankitajaiwar)


