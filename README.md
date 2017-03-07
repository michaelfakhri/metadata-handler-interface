# FileMetadataHandler API

## Methods
#### `Promise store(hash, metadata)`
> returns a promise that resolves once the metadata is stored.

Where:
* `hash : String` - The hash of the contents of a file.
* `metadata : Object` - The metadata corresponding to the hash (file) provided.

#### `Promise get(hash)`
> returns a promise that resolves to the metadata that goes along with the hash provided.

Where:
* `hash : String` - The hash of the contents of a file.

#### `Promise query(query)`
> returns a promise that resolves to the query result.

Where:
* `query : String` - A string that represents the query to be processed.

#### `Promise delete(hash)`
> returns a promise that resolves once the metadata belonging to the provided hash is deleted.

Where:
* `hash : String` - The hash of the contents of a file.
