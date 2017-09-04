# ws-web-utils
Can only be used internally for the project

## Installation

```bash
$ npm install --save ws-web-utils
```

## stateHoc API (props , params)

### Params Config

| Param | Default | Type | Description |
| :------------ |:---------------:| :---------------:| :-----|
| LoadingView | `LoadingView` | `Class/Func` | 等待状态 |
| FailureView | `FailureView` | `Class/Func` | 失败状态 |
| ErrorView | `ErrorView` | `Class/Func` | 错误状态 |
| detail | `false` | `Boolean` | 使用场景是多个state |
| keyFunc | `undefined` | `Func` | detail==true时有效，捆绑key生效 |
| key | `undefined` | `String` | detail==true时有效，取值唯一标识 |
| height | `undefined` | `Number` | LoadingView的height props |

### Props Config

| Prop | Default | Type | Description |
| :------------ |:---------------:| :---------------:| :-----|
| fetchStatus | `undefined` | `String` | 详见内部FetchStatus |
| orther props | `...this.props` | `Object` | ... |