
# Replacing Multiple Commit Authors

Steps to change all commits:

*bash*
```
git clone --bare https://github.com/AnderVicario/MaputoMods.git
```

```
cd MaputoMods.git
bash /c/Users/ander/Escritorio/replace-commits.sh
```

```
git push --force --tags origin 'refs/heads/*'
```
