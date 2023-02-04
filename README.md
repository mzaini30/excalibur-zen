# Excalibur

Package ini adalah tools untuk memanggil sebuah tools backend bernama [Excalibur](https://github.com/mzaini30/excalibur).

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

[Join Komunitas](https://zenzen.web.id/komunitas-id)
