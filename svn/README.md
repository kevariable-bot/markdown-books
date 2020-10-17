# SVN Checkout

If you are using `svn` instead of git, there is a straightforward way to do this. Simply cd into your working directory and replace the `“/tree/master”` path within the `url` with `trunk`. To clone the subdirectory `examples` in the point cloudgit repo for example, using `svn`, we would do the following in terminal

```shell
svn checkout https://github.com/kevinaltaf/directory/trunk/examples
```

more option

```shell
svn --help
```
