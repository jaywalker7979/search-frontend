# app

├─ [core]
│   ├─ [authentication]
│   │   ├─ auth.guard.ts
│   │   ├─ interface.ts
│   │   └─ token.service.ts
│   ├─ [bootstrap]
│   │   ├─ menu.service.ts
│   │   ├─ preloader.service.ts
│   │   ├─ settings.service.ts
│   │   ├─ startup.service.ts
│   │   └─ translate-lang.service.ts
│   ├─ [interceptors]
│   │   └─ default.interceptor.ts
│   ├─ core.module.ts
│   ├─ index.ts
│   ├─ module-import-guard.ts
│   └─ settings.ts
├─ [route]
│   ├─ [dashboard]
│   │   ├─ dashboard.component.html
│   │   └─ dashboard.component.ts
│   ├─ [sessions]
│   │   ├─ [login]
│   │   ├─ [register]
│   │   ├─ 403.component.ts
│   │   ├─ 404.component.ts
│   │   ├─ 500.component.ts
│   │   ├─ sessions.module.ts
│   │   └─ sessions-routing.module.ts
│   ├─ routes.module.ts
│   └─ routes-routing.module.ts
├─ [shared]
│   ├─ [components]
│   │   ├─ [breadcrumb]
│   │   │   ├─ breadcrumb.component.html
│   │   │   ├─ breadcrumb.component.scss
│   │   │   └─ breadcrumb.component.ts
│   │   ├─ [error-code]
│   │   │   ├─ error-code.component.html
│   │   │   ├─ error-code.component.scss
│   │   │   └─ error-code.component.ts
│   │   └─ [page-header]
│   │   │   ├─ page-header.component.html
│   │   │   ├─ page-header.component.scss
│   │   │   └─ page-header.component.ts
│   ├─ [services]
│   │   │   ├─ directionality.service.ts
│   │   │   └─ storage.service.ts
│   ├─ [utils]
│   │   │   ├─ colors.ts
│   │   │   ├─ icons.ts
│   │   │   └─ utils.ts
│   ├─ index.ts
│   └─ shared.module.ts
├─ [theme]
│   ├─ [admin-layout]
│   │   ├─ admin-layout.component.html
│   │   └─ admin-layout.component.ts
│   ├─ [auth-layout]
│   │   ├─ auth-layout.component.html
│   │   └─ auth-layout.component.ts
│   ├─ [header]
│   │   ├─ branding.component.ts
│   │   ├─ header.component.html
│   │   ├─ header.component.ts
│   │   ├─ notification.component.ts
│   │   ├─ translate.component.ts
│   │   └─ user.component.ts
│   ├─ [sidebar]
│   │   ├─ sidebar.component.html
│   │   ├─ sidebar.component.ts
│   │   └─ user-panel.component.ts
│   ├─ [sidebar-notice]
│   │   ├─ sidebar-notice.component.html
│   │   └─ sidebar-notice.component.ts
│   ├─ [sidemenu]
│   │   ├─ accordion.directive.ts
│   │   ├─ accordionanchor.directive.ts
│   │   ├─ accordionlink.directive.ts
│   │   ├─ sidemenu.component.html
│   │   └─ sidemenu.component.ts
│   ├─ [style]
│   ├─ [topmenu]
│   │   ├─ topmenu.component.html
│   │   └─ topmenu.component.ts
│   └─ theme.module.ts
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