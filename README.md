# Practical 8 --- Hello World iOS App with SwiftUI

A beginner-friendly iOS application practical demonstrating how to
create, understand, preview, and run a simple **Hello World** app using
**Swift** and **SwiftUI** in Xcode.

## 📘 Practical Details

-   **Subject:** Mobile Application Development (MAD)
-   **Practical No.:** 8
-   **Student:** Prince Prajapati
-   **Enrollment No.:** 24012011153
-   **App Name:** `hello world`
-   **Platform:** iOS
-   **IDE:** Xcode
-   **Programming Language:** Swift
-   **UI Framework:** SwiftUI

## 🎯 Objective

To create a basic iOS application in Xcode, understand its main SwiftUI
source files, display the text **"Hello, world!"**, and run the app
using an iOS simulator or SwiftUI preview.

## ✨ What This Practical Covers

-   Creating a new iOS project with Xcode's **App** template.
-   Choosing **SwiftUI** for the user interface and **Swift** as the
    programming language.
-   Understanding the app entry point in `hello_worldApp.swift`.
-   Creating a basic screen in `ContentView.swift`.
-   Displaying text with `Text("Hello, world!")`.
-   Applying spacing with the `.padding()` modifier.
-   Selecting and running an iOS simulator.
-   Previewing UI changes in Xcode without running the full app.
-   Initializing a local Git repository for version control.

## 🧱 Project Structure

The practical introduces two main source files:

``` text
hello world/
├── hello_worldApp.swift
└── ContentView.swift
```

> Xcode may generate additional project and configuration files
> depending on its version and the selected options.

### `hello_worldApp.swift`

This file is the app's entry point. The `@main` attribute identifies the
app structure that starts the application, while `WindowGroup` defines
the scene that displays `ContentView`.

``` swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

### `ContentView.swift`

This file defines the app's main screen. The `Text` view displays a
message, and `.padding()` adds space around it.

``` swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

## 🚀 How to Create and Run the App

1.  Open **Xcode** on a Mac.
2.  Select **File → New → Project**.
3.  Choose **App** under the iOS project templates.
4.  Set the product name to `hello world`.
5.  Select **SwiftUI** as the interface and **Swift** as the language.
6.  Leave **Core Data** and **unit testing** unchecked, as described in
    the practical.
7.  Optionally enable **Create Git repository on my Mac** and save the
    project.
8.  In the project navigator, open `ContentView.swift` and review the
    displayed text.
9.  Choose an available iOS simulator from the device selector.
10. Press the **Run (▶)** button to build and launch the app.
11. To see UI changes in the editor, open the SwiftUI preview and press
    **Resume** if required.

## 🧠 Key Concepts

  -----------------------------------------------------------------------
  Concept                             Simple Explanation
  ----------------------------------- -----------------------------------
  Swift                               Apple's programming language for
                                      building apps across its platforms.

  SwiftUI                             A declarative framework for
                                      building app interfaces with Swift
                                      code.

  `App` protocol                      Defines the main structure of a
                                      SwiftUI application.

  `@main`                             Marks the starting point of the
                                      application.

  `WindowGroup`                       Creates the app's main scene or
                                      window group.

  `View` protocol                     Represents a piece of user
                                      interface.

  `Text`                              Displays text on the screen.

  `.padding()`                        Adds space around a view.

  Simulator                           Runs an iOS app on a virtual Apple
                                      device.

  Preview                             Shows the view's appearance inside
                                      Xcode while developing.
  -----------------------------------------------------------------------

## 🖼️ Expected Output

When the app runs, it displays:

**Hello, world!**

The text appears with padding on the app's screen.

## ⚙️ Requirements and Notes

-   **A Mac with a compatible version of Xcode** is required to build
    and run the iOS project.
-   The iOS Simulator is included with Xcode; a physical iPhone is not
    required for this basic practical.
-   The exact options and preview interface may differ slightly between
    Xcode versions.
-   This practical is a minimal demonstration and does not require a
    database.

## 📚 Learning Outcome

After completing this practical, a student should be able to create a
basic SwiftUI project, identify the app entry point and content view,
display text on screen, and run or preview the app in Xcode.

## 🎓 Academic Use

Prepared as a **Mobile Application Development --- Practical 8**
learning submission.
