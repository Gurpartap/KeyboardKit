## KeyboardKit

A drop-in framework for adding Custom Keyboard to your iOS 8+ app.

##### Requirements

* iOS 8.1+
* Xcode 6.1+

##### Installation

1. Create a containing app project with a *Custom Keyboard* extension. Consider you named it "Example Keyboard".
2. Add KeyboardKit.framework to the project navigator making sure it is added to the *Example Keyboard* target.
3. Add KeyboardKit.framework to Linked Frameworks and Libraries in Example Keyboard target.
4. Create a *New Copy Files Phase* with *Frameworks* as the *Destination* under Example Keyboard target's Build Phases.
5. Add KeyboardKit.framework to this Copy Files build phase.
6. Subclass `KeyboardKit.KeyboardViewController` and Run!

##### Usage

```Swift
// KeyboardViewController.swift

import KeyboardKit

class KeyboardViewController: KeyboardKit.KeyboardViewController {
    
}
```
##### Creator

* [Gurpartap Singh](http://gurpartap.com/) ([@Gurpartap](http://twitter.com/Gurpartap))

##### License

KeyboardKit is licensed under MIT license. See LICENSE for details.