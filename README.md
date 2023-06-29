# Create conda env

Using micromamba:

```sh
# from working env
micromamba env export > env.yml

# to create env from this file
create -f env.yml

```
