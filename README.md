# multiple singles

distributed dating site


## hosting a single.single

see [brian.singles](https://github.com/btford/brian.singles)


## JSON spec

**the following fields are required:**

### `name`
or whatever people call ya

### `twitter`
whatever internet people call ya

### `single`
you can probably guess what this means; boolean for simple cases, a string for everything else

**the following are optional:**

### `fetishes`
an array of strings

### `interestedIn`
whatever you're into

you can also add any other fields you like – that's cool


## API

cuz programmers

### querying a profile

```shell
curl -H 'Accept: application/json' http://brian.singles
```

### querying relationship status

```shell
curl -H 'Accept: application/json' http://is.brian.singles
```

## License
MIT
