# API for MGTS router Sercomm RV6699

[![status](https://api.travis-ci.org/timmson/sercomm-rv6699.svg?branch=master)](https://travis-ci.org/timmson/sercomm-rv6699)
[![codecov](https://codecov.io/gh/timmson/sercomm-rv6699/branch/master/graph/badge.svg)](https://codecov.io/gh/timmson/sercomm-rv6699)
[![codacy](https://api.codacy.com/project/badge/Grade/71d7aeeb05e940028f7ac1766d6fff30)](https://www.codacy.com/app/timmson666/sercomm-rv6699)
[![version](https://img.shields.io/npm/v/sercomm-rv6699.svg)](https://www.npmjs.com/package/sercomm-rv6699)
[![license](https://img.shields.io/npm/l/sercomm-rv6699.svg)](https://www.npmjs.com/package/sercomm-rv6699)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Ftimmson%2Fsercomm-rv6699.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Ftimmson%2Fsercomm-rv6699?ref=badge_shield)

## Installation
```bash
npm i sercomm-rv6699
```

## Examples
```js
const SerCommRv6699Api = ("sercomm-rv6699");

const options = {
    url: "http://your-route-ip",
    login: "login",
    password: "password"
};

let api = new SerCommRv6699Api(options);

api.getDeviceList().then(console.log, console.error);
```
