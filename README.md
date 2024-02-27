PSL Mobile Foundation
===
## PreemptiveLoginSwift
A sample application demonstrating implementation of Preemptive Login.

### Tutorials
https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/authentication-and-security/user-authentication/
### Usage

1. Use either Maven, MobileFoundation CLI or your IDE of choice to build and deploy the available `ResourceAdapter` and `UserLogin` adapters](https://pmf.persistentproducts.com/tutorials/en/foundation/9.0/adapters/creating-adapters/).


2. From a command-line window, navigate to the project's root folder and run the commands:
 - `pod update` followed by `pod install` - to add the MobileFoundation SDK.
 - `mfpdev app register` - to register the application.
 - `mfpdev app push` - to map the `accessRestricted` scope to the `UserLogin` security check.

> **Tip:** you can update the bundled SDK by running the command `pod update` from the project's root folder.

### Supported Levels
PSL Mobile Foundation 9.0

