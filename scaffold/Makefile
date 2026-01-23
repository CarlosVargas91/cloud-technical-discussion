install:
# Install dependencies
	pip install --upgrade pip &&\
	pip install -r requirements.txt

format:
# Format code using Black
	black *.py

lint:
# Lint code using Pylint, disabling certain warnings
	pylint --disable=R,C hello.py

test:
# Run tests with coverage
	python -m pytest -vv --cov=hello test_hello.py

all: install lint test