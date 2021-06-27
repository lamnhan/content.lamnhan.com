### Cài đặt

Install globaly, as a CLI:

```sh
npm i -g @lamnhan/testea
```

Or localy:

```sh
npm i -D @lamnhan/testea
```

### Usage

Use the library:

```ts
import { mockService } from "@lamnhan/testea";

const mocked = mockService({
  a: () => 1,
  b: async () => 2,
});

// test begins
```

Use the CLI to generate spec files:

```sh
testea generate
```

### Documentation

See the documentation at: <https://testea.lamnhan.com>
