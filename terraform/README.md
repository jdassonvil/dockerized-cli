## Dockerized terraform CLI

If you don't want to install terraform directly on your machine you can use this docker image.

### Installation
You can prebuild the image (otherwise the script will do it for you on the first command usage).

### Usage

```
$ terraform --conf-dir [tf files directory] --region [region name] [terraform command]
```

### TODO
* support REGION option for aws
