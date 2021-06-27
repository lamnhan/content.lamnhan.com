### Cài đặt

```sh
npm i -S @lamnhan/ngx-useful
```

### Sử dụng

Cung cấp dịch vụ trong mô-đun ứng dụng:

```ts
import { AppService } from '@lamnhan/ngx-useful';

@NgModule({
  provides: [AppService]
})
```

Thiết lập dịch vụ trong thành phần ứng dụng:

```ts
class AppComponent {
  constructor() {
    this.initialize();
  }

  private initialize() {
    this.appService
      .setOptions()
      .init();
  }
}
```

### Tài liệu

Xem tài liệu tại: <https://ngx-useful.lamnhan.com>