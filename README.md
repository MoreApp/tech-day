# MoreApp Techday

## Prerequisites
```
npm
node
```


## Setup Local Tunnel
See: `http://localtunnel.me/`

### Installation
```
$ npm install -g localtunnel
```

### Run
```
$ lt --port 3000
your url is: https://gqgh.localtunnel.me
```

## Server

### Installation

```
npm install
```

### Run Server
```
node index.js
```

## Developing a Plugin

### Configuration

#### Basic Information
The basic information can be edited in `config.json`.
You should place the url provided by `localtunnel` in this file.
You may choose your own `namespace`, `key` and `name` for your plugin. Make sure the following rules comply:

- namespace: `[a-z]+(\.[a-z]+)*`
- key: `[a-z]+`

#### Configure the definition
You can edit the information for your hook configuration in `hook/definition.json`. The documentation is located on Confluence (Space: `MORE`, Page: `Plugins`).


### Upload Package
```
$ node upload.js
```

