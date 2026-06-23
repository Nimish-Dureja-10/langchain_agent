uv init -> initialize uv project

# create virtual environment
uv venv

# activate virtual environment
Activate with: source .venv/bin/activate (mac os command)

# create requirements.txt file 
add all the required libraries

# install dependencies from requirements.txt
uv add -r requirements.txt

# install jupiter notebook kernel
uv add ipykernel