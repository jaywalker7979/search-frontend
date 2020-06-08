# app

├─ [core]
│   ├─ [authentication]
│   │   ├─ 
│   ├─ [bootstrap]
│   ├─ [interceptors]
│   ├─ core.module.ts
│   ├─ index.ts
│   ├─ module-import-guard.ts
│   └─ settings.ts
├─ [route]
├─ [shared]
├─ [theme]
├─ app.component.css
├─ app.component.ts
├─ app.module.ts
└─ material.module.ts

##### [core]-settings.ts

* export interface AppSettings : 선택할 수 있는 옵션에 대한 명세
* export const defaults: AppSettings : 실제 사용되는 설정들

# Others

├─ [src]
│   ├─ [app] --X
│   ├─ [assets]
│   │   ├─ [data]
│   │   │   ├─ dashboard.json
│   │   │   └─ menu.json
│   │   ├─ [fonts]
│   │   │   ├─ Material_Icons.css
│   │   │   └─ flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2
│   │   ├─ [i18n] : Expressions in different languages : This filename is used in the file [src]-[app]-[core]-settings.ts
│   │   │   ├─ en-US.json
│   │   │   ├─ zh-CN.json
│   │   │   └─ zh-TW.json
│   │   └─ [images] : There are two images which is used for default dashboard layout (user picture and site log)
│   ├─ [environments]
│   │   ├─ environment.hmr.ts
│   │   ├─ environment.prod.ts
│   │   └─ environment.ts
│   ├─ [styles]
│   ├─ favicon.ico
│   ├─ hmr.ts
│   ├─ index.html
│   ├─ main.ts
│   ├─ polyfills.ts
│   ├─ styles.css
│   ├─ styles.scss
│   ├─ test.ts
│   └─ typings.d.ts
├─ angular.json
├─ browserslist
├─ karma.conf.js
├─ package.json
├─ package-lock.json
├─ proxy.config.js
├─ tsconfig.app.json
├─ tsconfig.json
├─ tsconfig.spec.json
└─ tslint.json

##### tslint.json