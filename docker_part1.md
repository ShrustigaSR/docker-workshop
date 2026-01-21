| # | Command |
|---|---|
| 1 | `git config user.email` |
| 2 | `git push --dry-run` |
| 3 | `docker` |
| 4 | `docker run hello-world` |
| 5 | `docker run ubuntu` |
| 6 | `docker run -it ubuntu` |
| 7 | `ls` |
| 8 | `docker run -it python:3.13.11-slim` |
| 9 | `docker run --entrypoint=bash python:3.13.11-slim` |
| 10 | `docker run -it --entrypoint=bash python:3.13.11-slim` |
| 11 | `docker ps -a` |
| 12 | `docker ps -aq` |
| 13 | `docker rm `docker ps -aq`` |
| 14 | `docker ps -a` |
| 15 | `mkdir test` |
| 16 | `cd test/` |
| 17 | `ls` |
| 18 | `touch file1.txt file2.txt file3.txt` |
| 19 | `echo "Hello from host" > file1.txt` |
| 20 | `ls` |
| 21 | `cat file1.txt` |
| 22 | `cat file2.txt` |
| 23 | `python script.py` |
| 24 | `ls` |
| 25 | `cd ..` |
| 26 | `ls` |
| 27 | `pwd` |
| 28 | `docker run -it --entrypoint=bash -v $(pwd)^Cython:3.13.11-slim` |
| 29 | `docker run -it --entrypoint=bash -v $(pwd)/test:/app/test python:3.13.11-slim` |
| 30 | `mkdir pipeline` |
| 31 | `cd pipeline` |
| 32 | `python pipeline.py` |
| 33 | `python pipeline.py 12` |
| 34 | `pip install pandas` |
| 35 | `python pipeline.py 12` |
| 36 | `pip install uv` |
| 37 | `ls` |
| 38 | `pwd` |
| 39 | `uv init --python 3.13` |
| 40 | `which python` |
| 41 | `python -V` |
| 42 | `uv run python -V` |
| 43 | `uv run which python` |
| 44 | `which python` |
| 45 | `uv run python` |
| 46 | `uv add pandas pyarrow` |
| 47 | `uv run python pipeline.py 12` |
| 48 | `git status` |
| 49 | `git add .` |
| 50 | `git commit -m "pipeline first version"` |
| 51 | `docker run -t test:pandas` |
| 52 | `docker build -t test:pandas .` |
| 53 | `docker run -it --entrypoint=bash test:pandas ` |
| 54 | `docker build -t test:pandas .` |
| 55 | `docker run -it --rm test:pandas 12` |

