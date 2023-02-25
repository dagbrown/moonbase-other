export PYTHONDONTWRITEBYTECODE=1 &&

python -m build -w --skip-dependency-check &&

prepare_install &&
python -m installer -d / dist/*.whl
