# Register your broom
Example of the GOV.UK Prototype KIT in action


## build image

```
pack build register-your-broom --builder heroku/buildpacks:20
```

[//]: # (or)

[//]: # (```)

[//]: # (docker build -t register-your-broom .)

[//]: # (```)

## run image

```
docker run --rm -p 3000:3000 register-your-broom
```
or
```
docker-compose up
```
