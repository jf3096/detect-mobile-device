# detect-mobile-device

> detect mobile site device type

[![NPM](https://img.shields.io/npm/v/detect-mobile-device.svg)](https://www.npmjs.com/package/detect-mobile-device) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save detect-mobile-device
```

## Usage

```javascript
  import { isWeiXin } from 'detect-mobile-device';

  console.log(isWeiXin());
  // true
```

## API

```typescript
/**
 * 获取 UA
 * @return {string}
 */
export declare function getUserAgent(): string;
/**
 * 判断是否是手机
 * @return {boolean}
 */
export declare function isMobile(): boolean;
/**
 * 判断是否是 android 设备
 */
export declare function isAndroid(): boolean;
/**
 * 判断是否 ios 设备
 */
export declare function isIOS(): boolean;
/**
 * 是否是 微信 设备
 */
export declare function isWeiXin(): boolean;
/**
 * 判断是否是 mobile 微信
 */
export declare function isMWeiXin(): boolean;
/**
 * 判断是否是手机qq
 * @return {boolean}
 */
export declare function isMQQ(): boolean;
/**
 * 判断是否是手机微博 UA
 * @return {boolean}
 */
export declare function isMWeibo(): boolean;
```

## License

MIT © [jf3096](https://github.com/jf3096)
