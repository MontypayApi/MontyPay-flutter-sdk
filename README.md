# MontyPay-flutter-sdk
![](https://jitpack.io/v/MontyPay/MontyPay-android-sdk.svg) | [View SDK Wiki](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki) | [Report new issue](https://github.com/MontypayApi/MontyPay-flutter-sdk/issues/new)

# MontyPay Flutter SDK

Monty Pay Is a global payment gateway founded as a subsidiary of Monty Capital with a HQ in Switzerland and offices in UK, Cyprus, Lebanon, Nigeria, and UAE. It is a smart and powerful payment gateway solution that aims to help merchants grow and develop their payment methods. We allow for a better and unified online commerce experience for shoppers and merchants alike, aiming to simplify the complexities of payments to help you grow.

<p align="center">
  <a href="https://montypay.com">
      <img src="https://user-images.githubusercontent.com/85153851/147742859-67b127e7-2fc6-418a-ac14-5f7eeca10eca.jpg" alt="MontyPay" width="400px"/>
  </a>
</p>

MontyPay Flutter SDK was developed and designed with one purpose: to help the Flutter developers easily integrate the MontyPay API Payment Platform for a specific merchant. 

To properly set up the SDK, read [Wiki](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki) first.

To get used to the SDK, download a [sample app](https://github.com/MontypayApi/MontyPay-flutter-sdk/blob/main/montypay_sdk-1.0.9.zip).

## Setup and Installation

This Flutter plugin is based on iOS and Android native libraries. You need to add the jitpack repository support and credentials to the gradle to access the secured Android library. Follow Below

**Setup Android** Add to the root build.gradle in Android Project at Path:(${ProjectRoot}/android/build.gradle):

```groovy

allprojects {
    repositories {
        ...
        jcenter()
        maven {
            url 'https://jitpack.io'
            credentials { username 'jp_tjnosefflebgig8l3i0q6cgf09' }
        }
    }
}
```

Setup iOS iOS does not required any setup just install flutter plugin where the iOS framewework is embedded within the plugin in iOS plaform directory. If you need to enable Apple Pay in your app it can be enable by following the instructions at [Link](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki/MontyPay)

## Installting Flutter Plugin

In the dependencies: section of your pubspec.yaml, add the following lines:

```groovy

dependencies:
  intl: ^0.17.0
  montypay_sdk: any
  
```

## Initialize SDK

```groovy

MontypaySdk.instance.config(
    key: MERCHANT_CLIENT_KEY, // Your Secret Merchant Key
    password: MERCHANT_CLIENT_PASSWORD,  // Your Secret Merchant Password
    enableDebug: true
);

``` 
[More Details](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki)

##Quick Payment Implementation

[Card Payment for IOS/Android](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki/MontyPay-Quick-Card-Payment) Start the card payment with one click, easy and short line of codes. It will help the developer to easily implement the payment using card in thier application. click the link for easy steps to start payments.

[ApplePay Payment for IOS](https://github.com/MontypayApi/MontyPay-flutter-sdk/wiki/MontyPay-ApplePay-Payment) Start the Apple Pay payment with one click, easy and short line of codes. It will help the developer to easily implement the payment using ApplePay in thier application. the developer just need to configure and enable the Apple Pay in thier AppleDeveloper Account and call the simple function. click the link for easy steps to start payments with ApplePay.

## Getting help

To report a specific issue or feature request, open a [new issue](https://github.com/MontypayApi/MontyPay-flutter-sdk/issues).

Or write a direct letter to the [support@montypay.com](mailto:support@montypay.com).

## License

MIT License. See the [LICENSE](https://github.com/MontypayApi/MontyPay-flutter-sdk/blob/main/LICENSE) file for more details.

## Contacts



Website: [https://www.montypay.com](https://www.montypay.com)

Phone: +961-1-748847

Email: support@montypay.com

Address: MontyPay - UK 



© 2021 MontyPay. All rights reserved

