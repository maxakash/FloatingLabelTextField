# FloatingLabelTextField
This Swift Package supports floating label for Text Field and Secure Field in SwiftUI



![Screenshot](./images/example.gif)


# Installation
Install through Swift Package Manager.

# Usage

```
import FloatingLabelTextField


@State var username = ""
@State var password = ""
var body: some View {
  VStack {
    FloatingLabelTextField(placeHolder: "Input your name", text: $username)
    FloatingLabelSecureField(placeHolder: "Input your age", text: $password)
  }
}

```

