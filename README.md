# Shower presentations команды CD

Форк репозитория https://gitlab.2gis.local/shower/shower-2gis-theme
Вся документация о работе с движком в [README](https://gitlab.2gis.local/shower/shower-2gis-theme/blob/master/README.md)

## Порядок действий

```sh
git checkout master
git pull
git checkout -b $(date +"%Y-%m-%d")
# правим index.html

# пушим новую ветку
git commit -am "My new shiny presentation"
git push -u origin
```
