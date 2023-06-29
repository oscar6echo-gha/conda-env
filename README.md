# Create conda env

Using micromamba:

```sh
# from working env
micromamba env export > env.yml

# to create env from this file
micromamba create -f env.yml

```

## Github Enterprise

Ref <https://docs.github.com/en/github-ae@latest/admin/github-actions/managing-access-to-actions-from-githubcom/about-using-actions-in-your-enterprise>
