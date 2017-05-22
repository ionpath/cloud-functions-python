# cloud-functions-python
`go-cloud-fn` is a tool that allows you to write and deploy [Google cloud functions](https://cloud.google.com/functions/) in pure python.

Run `pip install python-cloud-functions` to get it.
You need to have [Google cloud SDK](https://cloud.google.com/sdk/downloads) installed, as well as
the [Cloud functions emulator](https://github.com/GoogleCloudPlatform/cloud-functions-emulator/).
Currently the emulator does not seem to work though :(

# Usage
Usage is meant to be pretty idiomatic:

### Handling a http request
```
testing
```

### Handling a bucket event
```
testing
```

### Handling a pubsub message
```
testing
```

Run `py-cloud-fn build <function_name> <trigger_type>` to deploy your finished function.
Run with `-h` to get some guidance.

## License

Copyright © 2017 Martin Sahlen

Distributed under the MIT License
