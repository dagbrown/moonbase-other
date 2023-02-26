export PYTHONDONTWRITEBYTECODE=1 &&

PYTHONPATH=$(pwd)/src python -m build -w &&

prepare_install &&

python -m installer --destdir=/ dist/*.whl
