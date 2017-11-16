# cipher-caesar

Encryption library for encrypt/decrypt of text, based on the alhorithm [Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher)

The API is as folows:

```
encrypt(offset, text);

decrypt(offset, cryptText);
```

## Options

 * offset - the number by which the chars are shiffted
 * text - original text
 * cryptText - text that requires decryption

## Examples

Encrypt text:

```
encrypt(3, 'sample'); // 'vdpsoh'
```

Decrypt crypted text:

```
decrypt(3, 'vdpsoh'); // 'sample'
```