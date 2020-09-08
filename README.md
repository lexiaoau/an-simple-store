# AnSimpleStore

// create project
ng new an-simple-store

// create a component under app folder
ng g component product-list
ng generate component product-list

// src/app/product-list/product-list.component.html
*ngFor 是一个 "结构型指令"。结构型指令会通过添加、删除和操纵它们的宿主元素等方式塑造或重塑 DOM 的结构。
任何带有 * 的指令都是结构型指令。

/
插值表达式 {{}} 允许你把属性值渲染为文本；而
属性绑定语法 [] 则允许你在模板表达式中使用属性值。

/
使用 *ngIf 指令，这样才能在当前商品有描述信息的情况下创建这个 p 元素。

/
把 button 的 click 事件绑定到我们替你定义好的 share() 事件上

//
app-product-alerts 中 product 是父对子传递参数
 (notify)="onNotify()"     是子对父的回调 。


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
# an-simple-store
