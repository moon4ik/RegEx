# RegEx

```swift
let firstName = "^([A-Za-z][a-z]{1,18}[- ])?[A-Za-z][a-z]{2,18}$"
let lastName = "^([A-Za-z][a-z]*[- ']?)?[A-Za-z]?[a-z]{2,24}$"
let email = "^[A-Z0-9a-z._%+-]+@[A-Za-z0-9.-]+\\.[A-Za-z]{2,64}$"
let phone = "^[+]?[0-9() ]{10,16}$"
let password = "^(?=.*[a-z])(?=.*[A-Z])(?=.*\\d)(?=.*[{}.'@$!%*?&#])[A-Za-z\\d{}.'@$!%*?&#]{8,32}$"
```
