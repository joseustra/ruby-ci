# ruby-ci

Docker images to be used when testing ruby.

### Ruby versions available
- 2.5.1
- 2.6.1

### includes
- Mysql and Postgres libs
- node
- yarn
- Chrome

### How to use
```bash
docker run --rm -it -v $PWD:/app ustrajunior/ruby-ci:2.5.1 bash
docker run --rm -it -v $PWD:/app ustrajunior/ruby-ci:2.6.1 bash
```