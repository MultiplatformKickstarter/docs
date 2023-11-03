---
title: Overview
description: Multiplatform Kickstarter is a template that allows creating cross-platform apps for desktop, web, and mobile devices.
weight: 1
---

{{% pageinfo %}}
The Kotlin Multiplatform technology is designed to simplify the development of cross-platform projects. It reduces time
spent writing and maintaining the same code for [different platforms](#kotlin-multiplatform-use-cases)
while retaining the flexibility and benefits of native programming.
{{% /pageinfo %}}

## Kotlin Multiplatform use cases

### Android and iOS applications

Sharing code between mobile platforms is a major Kotlin Multiplatform use cases. With Kotlin Multiplatform,
you can build cross-platform mobile applications that share code between Android and iOS to implement networking,
data storage and data validation, analytics, computations, and other application logic.

Check out the [Get started with Kotlin Multiplatform](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-getting-started.html) and
[Create a multiplatform app using Ktor and SQLDelight](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-ktor-sqldelight.html) tutorials,
where you will create applications for Android and iOS that include a module with shared code for both platforms.

Thanks to [Compose Multiplatform](https://www.jetbrains.com/lp/compose-multiplatform/),
a Kotlin-based declarative UI framework developed by JetBrains,
you can also share UIs across Android and iOS to create fully cross-platform apps.

### Desktop applications

Compose Multiplatform helps share UIs across desktop platforms like Windows, macOS, and Linux. Many applications,
including the [JetBrains Toolbox app](https://blog.jetbrains.com/kotlin/2021/12/compose-multiplatform-toolbox-case-study/),
have already adopted this approach.

Try this [Compose Multiplatform desktop application](https://github.com/JetBrains/compose-multiplatform-desktop-template#readme)
template to create your own project with UIs shared among desktop platforms.

## Code sharing between platforms

Multiplatform Kickstarter allows you to maintain a single codebase of the application logic for different platforms and the Backend.

## Get started

* Begin with the [Get started with Multiplatform Kickstarter](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-getting-started.html) if you want to create iOS and Android applications with shared code
* Explore the [Template code](https://github.com/MultiplatformKickstarter/kmp-template) if you want to know more about how it works.
