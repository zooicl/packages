pip download  --python-version 36 --abi cp36m --platform win_amd64 --implementation cp  -r requirements.txt --only-binary=:all: --dest .
pip download  --python-version 36 --abi cp36m --platform manylinux1_x86_64 --implementation cp  -r requirements.txt --only-binary=:all: --dest .
