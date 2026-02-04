To run the application locally, follow these steps:

1. clone the repository 
    ```bash
    git clone https://github.com/Lavanay07/devops-LG.git
    ```
2. Navigate to the prohject directory
    ```bash
    cd devops-LG
    ```
3. Install the dependecies:
    ```bash
    pip install requirements.txt
    ```
4. Run the application:
    ``` bash
    uvicorn app app --host 0.0.0.0 --port 8000
    ```