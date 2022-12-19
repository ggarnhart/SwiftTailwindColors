# TailwindColors

This package implements the latest (as of Dec 19, 2022) background colors from TailwindCSS in Swift. 

It was largely possible due to the earlier work of [this package](https://github.com/joemasilotti/TailwindCSS-SwiftUI).

To use, add this package to XCode using the repository URL. (https://github.com/ggarnhart/SwiftTailwindColors)

If, for example, you'd like to color a button, you can do so like this:

```swift

Button(action: {print("Hello, World!"}){
                Text("Say Hi")
            }
            .buttonStyle(.borderedProminent).tint(Tailwind.Color.blue300).buttonBorderShape(.roundedRectangle)
            

```
