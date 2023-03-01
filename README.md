# Example Package

This is a simple example package. You can use
[Github-flavored Markdown](https://guides.github.com/features/mastering-markdown/)
to write your content.



# for future refernece
```bash
mkdir -p packaging_tutorial/src/example_package_arjundandagi
cd <esc> .
touch __init__.py
touch example.py
touch README.md
touch LICENSE
mkdir tests
python3 -m pip install --upgrade build
python3 -m build
ls dist
python3 -m pip install --upgrade twine
python3 -m twine upload --repository testpypi dist/*
```
 
