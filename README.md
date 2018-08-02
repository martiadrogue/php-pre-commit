# PHP PRE-COMMIT

Fancy pre-commit script designed for PHP projects. It lints all staged PHP
files. Change permissions to allow its execution and then move the file to
`.git/hooks/pre-commit`.

It's based on <https://gist.github.com/filipekiss/8340999>

```shell
sudo chmod +x pre-commit
mv pre-commit .git/hooks/pre-commit
```

**Happy coding**
