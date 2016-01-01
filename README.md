一款基于[kui](https://github.com/kui/k-ui-octopress-theme)的[Octopress](http://octopress.org/) 主题。

可查看[我的博客](http://liubin.github.io/)查看该主题。

A Chinese version [Octopress](http://octopress.org/) Theme for [my blog](http://liubin.github.io/), inspired by [kui](https://github.com/kui/k-ui-octopress-theme). But it's not only an i18n of the `kui`, but has some my customization.

The name `l-ui` succeeds the name `k-ui`。Thanks `k-ui`

Install
----------------------------------------------------------------

```sh
$ git clone git://github.com/liubin/l-ui-octopress-theme.git .theme/lui
$ rake install["lui"]
```

Optional Functions
----------------------------------------------------------------

extra functions to the original theme.

`_config.yml.example` may be of sume help.

### tunbr photos

you can add recent tumblr posts.

add "asides/tumblr_photos.html" to `default_asides` of `_config.yml` as belows 
and configurations about tumbr_post.html.

```yml
default_asides: [ asides/tumblr.html, ... ]
```

```yml
tumblr_user: daftbeats # your domain (daftbeats.tumblr.com -> daftbeats)
tumblr_post_num: 5
```

### github api v3

you can specify a item for sorting repository links, the sort direction and
a repository type to be listed.

add [list-user-repositories params](http://developer.github.com/v3/repos/#list-user-repositories)
to your `_config.yml`

```yml
# github api v3 params
# see http://developer.github.com/v3/repos/#list-user-repositories
github_type: all
github_sort: updated
github_direction: desc
```
