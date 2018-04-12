# Dat Badge

[![Dat](https://dat-badge.glitch.me/badge-krismuniz.hashbase.io/badge.svg)](dat://badge-krismuniz.hashbase.io) [![License:MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](/LICENSE.md)

Add a cool badge to your [Dat](https://datproject.org/) project that includes the latest [archive version](https://docs.datproject.org/concepts#version-history) and a shorthand key ID.


* Fetches the latest version available
* If your Dat is offline, the badge displays `Offline` status
* Supports Dat-DNS links (e.g. `dat://www.krismuniz.com`)
* Displays Dat-DNS errors
* Useful for `README.md` files and P2P websites
* ***Looks cool***

#### Example:

[![Dat](/assets/badge-example.svg)](dat://badge-krismuniz.hashbase.io)

## How to Get a Badge

### Using the Badge Generator

You can use the **Badge Generator** to generate a Dat badge with any given `dat://` link. Go to [dat://badge-krismuniz.hashbase.io](dat://badge-krismuniz.hashbase.io) or [https://badge-krismuniz.hashbase.io](https://badge-krismuniz.hashbase.io) to get your badge code!

### Creating a badge link Manually

You can generate a badge link manually by using the following URL scheme:

```
https://dat-badge.glitch.me/<DAT-LINK>/badge.svg
```

#### Example A (`dat://82d079126548e37ce6466961077273401473bb8d4b4548d45e52015834e79644`)

```
                                              Dat-link (exclude dat://)                   
                            ┌──────────────────────────────────────────────────────────────┐
https://dat-badge.glitch.me/82d079126548e37ce6466961077273401473bb8d4b4548d45e52015834e79644/badge.svg
```

#### Example B (`dat://www.krismuniz.com`)

```
                                 Dat-link
                            ┌───────────────┐
https://dat-badge.glitch.me/www.krismuniz.com/badge.svg
```

## License

[MIT](/LICENSE.md)
