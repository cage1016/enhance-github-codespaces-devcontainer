# Github Codespaces DevContainer

**What's in the box?**

- [buildpacks/pack: CLI for building apps using Cloud Native Buildpacks](https://github.com/buildpacks/pack)
- [wagoodman/dive: A tool for exploring each layer in a docker image](https://github.com/wagoodman/dive)
  

Git clone `.devcontainer` directly

```bash
git init
git config core.sparseCheckout true
echo '/.devcontainer/*' >> .git/info/sparse-checkout
git remote add devcontainer git@github.com:cage1016/enhance-github-codespaces-devcontainer.git
git pull devcontainer master
```

This is based on the [GitHub Codespaces (Default Linux Universal)](https://github.com/microsoft/vscode-dev-containers/blob/v0.177.0/containers/codespaces-linux/README.md) from Microsoft.