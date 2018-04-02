# InitConstructor Xcode

Just created this playground in order to automatically generate the init constructor of Xcode. 

Nowadays, Xcode did not generate automatically the init constructor as Android Studio does, so to save some time I have decided write some easy way to do it.

## How it works

1. Open the playgroung InitConstructor
2. Write the name and the types of the variables at the top dictionary as the following example

```swift
var constructor:[String: String] = [
    "startTime": "Int",
    "endTime": "Int",
    "frequencyNotification": "Int"
]
```

3. Run the playground
4. Copy the printed result and paste it on Xcode

Voilà!

*Swift*
