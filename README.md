# up-101

## Experimenting with up serverless deployment tool

### References

* [UP : deploy serverless apps in seconds](https://hackernoon.com/up-b3db1ca930ee)
* [Blueprints for up(1)](https://medium.com/@tjholowaychuk/blueprints-for-up-1-5f8197179275)
* https://github.com/apex/up
* [up documentation](https://github.com/apex/up/tree/master/docs)


* * *

### npm scripts:

```
  "scripts": {
    "test": "echo TODO",
    "deploy": "up",
    "open": "up url --open",
    "clipboard": "up url --copy",
    "teardown": "up stack delete",
    "up-version": "up version",
    "up-upgrade": "up upgrade"
  },
```

### npm commands

* __npm run deploy__ - deploys to AWS
* __npm run open__ - opens deployed site in browser
* __npm run teardown__ - removes from AWS

### Usage

To use you should edit ```up.json``` and define your own AWS IAM user.


