# Zircon

<p align="center">
  <img width="150" height="150" src="https://i.imgur.com/1n0YVaA.png"> </br>
  <p align="center">
  Zircon is a File Uploader built with nodejs
</p>


[Official Zircon](http://Zircon.xyz/)

# :floppy_disk: Installation

```bash
# clone the repo
$ git clone https://github.com/MoptopX/Zircon.git

# install the node modules...
$ npm install
```

## Usage
```bash
npm start
```

### Working with your own DB ? modify config.js :
```javascript
module.exports = {
    dbURL: process.env.DATABASEURL || "mongodb://localhost/zircon"
}
```

### :whale: Docker Usage

Preparation:

1. Rename `docker-compose.yml.example` to `docker-compose.yml`
2. Rename `.env.example` to `.env`
3. Fill in the missing details in `.env` file

Boot:
```bash
docker-compose up -d
```
