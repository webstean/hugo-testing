== How to use this template ==

https://gohugo.io/getting-started/quick-start/

Clone Repo
hugo version
cd docs
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

echo "theme = 'ananke'" >> hugo.toml
echo "baseURL = 'https://example.org/'" >> hugo.toml
echo "languageCode = 'en-us'" >> hugo.toml
echo "title = \'My New Hugo Site\'" >> hugo.toml

hugo new site quickstart


