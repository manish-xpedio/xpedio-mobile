
# Xpedio mobile for React Native apps

This is a library for react-native applications which has most frequently used functionalities. This library will provide you tonnes of utility functions which will simplify coding.

So enjoy the coding...


## Authors
Manish Bhavsar
- [manish.bhavsar@xpediolive.com](https://www.github.com/mvbhavsar)


## Installation

Install xpedio mobile library with npm

```bash
  npm install --save xpedio-mobile
```
    
![Logo](https://xpediolive.com/xpediolive-big.png)


## API Reference

#### Get all API details

```http
  POST /api/items
```

| Function name | Return type     | Description                |
| :-------- | :------- | :------------------------- |
| `getDeviceId` | `string` | Returns unique device id if device is registered |
| `registerDevice` | `boolean` | Register handset with unique ID which is also stored on server |




## Documentation

**getDeviceId(): string**

This function will return registered device ID which needs to be validated against the server entry.

**registerDevice({ deviceId: string, phone: string }): boolean**

Registers device on the server