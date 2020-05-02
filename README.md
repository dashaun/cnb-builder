# cnb-builder

A builder that uses [cnb-stack](https://github.com/dashaun/cnb-stack)

The cnb-stack provides shared library dependencies.

### Contains:

- [Bionic](bionic/)
  - Includes

### Prerequisites
* [Pack](https://buildpacks.io/docs/install-pack/)

#### Creating the builder

```bash
pack create-builder dashaun/cnb-builder:bionic --builder-config bionic/builder.toml
```

### Additional Resources

* [`pack create-builders` documentation](https://buildpacks.io/docs/using-pack/working-with-builders/)