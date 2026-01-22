# blog
blog hosted by GitHub pages


## deploy

```bash
git clone git@github.com:baigemru/blog.git
git submodule update --init --recursive
```

## usage

### create post

```bash
# создаст черновик поста по шаблону из archetypes/post.md
hugo new --kind post <folder>/<name>.md
```

### embedded web server
http://localhost:1313/

```bash
hugo server -D
# -D` (или `--buildDrafts`) — включает черновики (draft posts) в сборку и отображение на сервере
```
