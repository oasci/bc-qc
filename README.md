<h1 align="center">Quantum Chemistry</h1>

<p align="center">
    <a href="https://github.com/oasci/bc-qc/actions">
        <img src="https://github.com/oasci/bc-qc/actions/workflows/pages.yaml/badge.svg" alt="Build Status ">
    </a>
    <a href="https://creativecommons.org/licenses/by/4.0/">
        <img src="https://img.shields.io/badge/License-CC_BY_NC_SA_4.0-lightgrey.svg" alt="License">
    </a>
</p>

## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone git@github.com:oasci/bc-qc.git

# Change directory
cd bc-qc

# Install modules
hugo mod tidy

# Start the server
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.
