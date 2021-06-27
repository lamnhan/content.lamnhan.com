### Cài đặt

Cài đặt CLI chung:

```sh
npm i -g @lamnhan/testea
```

Hoặc cài đặt theo dự án:

```sh
npm i -D @lamnhan/testea
```

### Sử dụng

Sử dụng như viện:

```ts
import { mockService } from "@lamnhan/testea";

const mocked = mockService({
  a: () => 1,
  b: async () => 2,
});

// test begins
```

Sử dụng CLI để tạo tệp kiểm thử:

```sh
testea generate
```

### Tài liệu

Xem thêm tài liệu tại: <https://testea.lamnhan.com>
