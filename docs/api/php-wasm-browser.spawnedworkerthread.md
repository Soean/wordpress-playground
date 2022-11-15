<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## SpawnedWorkerThread class
<b>Signature:</b>

```typescript
class SpawnedWorkerThread 
```
## Constructors

### SpawnedWorkerThread<!-- -->(<!-- -->messageChannel<!-- -->: [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)<!-- -->, serverUrl<!-- -->: [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)<!-- -->)


Constructs a new instance of the `SpawnedWorkerThread` class

## Properties

* `messageChannel`    [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)
* `serverUrl`    [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)

## Methods

### eval<!-- -->(<!-- -->code<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[PHPOutput](./php-wasm.phpoutput.md)<!-- -->&gt;

* `code` – The PHP code to run.
* Returns: The result of the PHP code.


Runs PHP code.
### HTTPRequest<!-- -->(<!-- -->request<!-- -->: [PHPRequest](./php-wasm.phprequest.md)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[PHPResponse](./php-wasm.phpresponse.md)<!-- -->&gt;

* `request` – The request to dispatch.
* Returns: The response from the PHPServer.


Dispatches a request to the PHPServer.
### internalUrlToPath<!-- -->(<!-- -->internalUrl<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

* `internalUrl` – An absolute URL based at the PHPServer root.
* Returns: The relative path.


Converts an absolute URL based at the PHPServer to a relative path
without the server pathname and scope.


### pathToInternalUrl<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

* `path` – The server path to convert to an absolute URL.
* Returns: The absolute URL.


Converts a path to an absolute URL based at the PHPServer
root.


