### Installation

```sh
npm i -S @lamnhan/ngx-useful
```

### Usage

Provide in app module:

```ts
import { AppService } from '@lamnhan/ngx-useful';

@NgModule({
  provides: [AppService]
})
```

Config in app component:

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

### Documentation

See the documentation at: <https://ngx-useful.lamnhan.com>