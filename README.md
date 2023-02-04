# Excalibur

Package ini adalah tools untuk memanggil sebuah tools backend bernama Excalibur.

## Instalasi

```bash
pnpm i excalibur-zen
```

## Penggunaan

```js
import excalibur from "excalibur-zen";

const server = "https://excalibur.kucing.com";
const id = "123";
const kunci = "ambil-semua-data";

const data = await excalibur(server, {
  id,
  kunci,
});
console.log(data);
```
