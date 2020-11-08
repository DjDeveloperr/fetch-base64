# fetch-base64
A simple module to fetch Base64 data of any image/gif, remote or local, for Deno.

Inspired from [fetch-base64](https://github.com/gamell/fetch-base64) for Node.js. I needed it in Deno, so I made a new small module.

## Usage
* `fetchRemote(url: string, onlyData?: boolean)`: to fetch base64 data from a remote server
  * **Params**
    * `url`:
      * URL of the resource
      * Type: string
    * `onlyData`:
      * Whether to fetch only data or complete URI
      * Type: boolean?

* `fetchLocal(url: string, onlyData?: boolean)`: to fetch base64 data from a local file
  * **Params**
    * `url`:
      * Path of the resource
      * Type: string
    * `onlyData`:
      * Whether to fetch only data or complete URI
      * Type: boolean?

* `fetchAuto(url: string, onlyData?: boolean)`: to fetch base64 data from a remote server / locally, identifies automatically.
  * **Params**
    * `url`:
      * URL/Path of the resource
      * Type: string
    * `onlyData`:
      * Whether to fetch only data or complete URI
      * Type: boolean?

## License
See [LICENSE](LICENSE) for more info.
Copyright 2020 @ DjDeveloper