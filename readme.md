## set up notebooks folder (done)
uv init notebooks
cd notebooks
uv add --dev ipykernel
## to add a package to the environment
uv add --dev {package_name}