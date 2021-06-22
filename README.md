

## Setup

See: https://gohugo.io/getting-started/quick-start/


### Installing

```
brew install hugo
```

### Checking version

```
hugo version
```

### Running

```
hugo server -D
```



## Create a new post

```
hugo new posts/my-first-post.md
```


## Deploy

```
hugo -d ./docs
```

https://gohugo.io/hosting-and-deployment/hosting-on-github/



## Theme

https://github.com/lxndrblz/anatole

## Troubleshooting

`found no layout file for "HTML" for kind "page"`?

```
git submodule init
git submodule update
```
