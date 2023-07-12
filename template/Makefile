.PHONY: init
init: git-init install

git-init:
	git init .

install:
	poetry install
	poetry run pre-commit install
