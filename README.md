# Google functions framework
Google's function framework to test google function in your local machine.

## Dependencies

```
$ npm install @google-cloud/functions-framework
```

## Execution
```
FUNCTION_TARGET=helloWorld npx @google-cloud/functions-framework
```

Open a browser, and goto to this [url](http://localhost:8080/).

## Deploy
```
gcloud functions deploy "helloWorld" --trigger-http --runtime="nodejs10"
```

Wait for some time, and access the given URL.
