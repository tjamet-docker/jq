# A container for jq command line

## Usage

### Default behaviour
`curl 'https://api.ipify.org?format=json' | docker run --rm -i tjamet/jq`

### Customize filter

`curl 'https://api.ipify.org?format=json' | docker run --rm -i tjamet/jq '.ip'`

### Get help
`docker run --rm tjamet/jq --help`

Note: `docker run --rm tjamet/jq` without argument may hang

## Install using [whalebrew](https://github.com/bfirsh/whalebrew)

`whalebrew install tjamet/jq`

### Usage

#### Default behaviour
`curl 'https://api.ipify.org?format=json' | jq`

#### Customize filter

`curl 'https://api.ipify.org?format=json' | jq '.ip'`

#### Get help
`jq --help`
