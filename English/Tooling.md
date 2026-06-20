# :triangular_ruler: Language toolkit

Newborn developers often have a limited understanding of the tools available to make working with code easier, increase efficiency, and protect against many mistakes. These tools are not a silver bullet for the difficulties the language may present, but they can significantly smooth out the rough edges. The following is a list of common and popular tools recognized by developers around the world, but it is only a small portion of what is available. Over time, you will become more familiar with these tools and discover new ones that suit your needs.

## :page_facing_up: Text editors

* :arrow_forward: **Visual Studio Code**

    Site: https://code.visualstudio.com/

    Price: free

    A powerful and efficient editor for text files and source code is available. It has a rich library of extensions that enables customization for personal preferences. It can also be configured to work with source code, allowing you to compile, run, and debug your code with ease. Additionally, it has a powerful search engine for files and folders, making it easier to search, read, and work with large projects.

* :arrow_forward: **Notepad++**

    Site: https://notepad-plus-plus.org/

    Price: free

    A lightweight editor for text files and source code, it supports syntax highlighting for common programming languages. Compared to Visual Studio Code, it is more convenient for quickly opening and viewing files and due to its lightweight design, it is comfortable to work with a large number of text files.

## :open_file_folder: IDE (Integrated Development Environment)

* :arrow_forward: **Microsoft Visual Studio IDE**

    Site: https://visualstudio.microsoft.com

    Price: Community Edition is free

    An integrated development environment (IDE) from Microsoft, providing a comprehensive set of tools including a code editor, compiler, debugger, and profiler, for various programming languages and cross-platform development. A great option for beginners, as its modern interface is user-friendly and requires minimal customization out of the box.

* :arrow_forward: **Qt Creator IDE**

    Site: https://www.qt.io/product/development-tools

    Price: free for open source projects (more details: [Qt Open Source](https://www.qt.io/download-open-source?hsCtaTracking=9f6a2170-a938-42df-a8e2-a9f0b1d6cdce%7C6cb0de4f-9bb5-4778-ab02-bfb62735f3e5))

    Initially, Qt Creator was positioned as an IDE for developing graphical interfaces for C++ applications. Over time, the framework has acquired numerous capabilities and evolved into a comprehensive ecosystem for cross-platform development. It offers a vast library of primitives for various needs such as networking, graphical interface, database work, and handling popular formats like images and text files. Today, Qt Creator serves as a competitor to Visual Studio and is particularly popular among developers creating applications for various Linux distributions.

* :arrow_forward: **Eclipse IDE**

    Site: https://www.eclipse.org/downloads/packages

    Price: free

    Eclipse is a highly capable multi-platform development environment, but it is also quite heavy. One of the key features of Eclipse is its modularity. The philosophy of Eclipse is that any developer can modify the development environment to fit their needs by connecting additional extensions. It is used as a foundation by some compiler developers for specialized OS or microcontrollers, such as the QNX real-time OS, Red-Hat Linux and more.

* :arrow_forward: **JetBrains CLion IDE**

    Site: https://www.jetbrains.com/clion

    Price: free for students and teachers

    Powerful multi-platform IDE from JetBrains. Like other IDEs, it provides a comprehensive set of tools for comfortable software development. It is convenient for cross-platform development in both C and C++.

## :flashlight: Extensions

* :arrow_forward: **JetBrains ReSharper C++**

    Site: https://www.jetbrains.com/resharper-cpp

    Price: free for students and teachers

    An extension for Microsoft Visual Studio, it adds advanced features for working with source code such as extended code highlighting and hints, building dependency diagrams between projects, recommendations for correcting common errors in code, enhanced information during debugging, improved searching and navigating within projects, etc. It competes with Visual Assist.

* :arrow_forward: **Visual Assist**

    Site: https://www.wholetomato.com

    An extension for Microsoft Visual Studio that provides additional features for working with source code, such as enhanced code highlighting and hints, increased information during debugging and coding, advanced search capabilities, and improved project navigation. It competes with JetBrains ReSharper.

* :arrow_forward: **Incredibuild**

    Site: https://www.incredibuild.com

    Price: have to contact incredibuild team to find the price

    Application/extension for distributed compilation of projects, which unites all developer workstations into a single network, providing the possibility of using dozens of machines to assemble and compile the source code. This speeds up the build process for large projects.

## :keyboard: Language services and formatting

* :arrow_forward: **clangd**

    Site: https://clangd.llvm.org/

    A language server for C and C++ that powers code completion, navigation, diagnostics, and refactoring in many editors, including Visual Studio Code and Vim/Neovim.

* :arrow_forward: **clang-format**

    Site: https://clang.llvm.org/docs/ClangFormat.html

    A source code formatter that helps teams keep a consistent style automatically. It is commonly used locally and in CI checks.

* :arrow_forward: **clang-tidy**

    Site: https://clang.llvm.org/extra/clang-tidy/

    A static analysis and linting tool from the LLVM project. It can find bug-prone patterns, modernization opportunities, readability issues, and style violations.

## :electric_plug: Package managers and build systems

* :arrow_forward: **CMake**

    Site: https://cmake.org

    A cross-platform automation system for building an application from source code, which generates the necessary artifacts for subsequent assembly on the target platform. It is currently considered the standard tool for building many C and C++ projects.

* :arrow_forward: **CMake Presets**

    Site: https://cmake.org/cmake/help/latest/manual/cmake-presets.7.html

    A CMake feature for storing common configure, build, test, and package settings in `CMakePresets.json`. It helps teams share repeatable local and CI build workflows.

* :arrow_forward: **Conan**

    Site: https://conan.io

    Price: free

    A package manager and dependency manager for organizing C++ libraries and frameworks. Modern Conan 2 workflows integrate well with CMake and are often used when teams need explicit control over binary packages, profiles, and build settings.

* :arrow_forward: **vcpkg**

    Site: https://learn.microsoft.com/en-us/vcpkg/

    Price: free

    A cross-platform C and C++ package manager. Its manifest mode lets a project declare dependencies in `vcpkg.json`, which makes dependencies easier to reproduce across developer machines and CI.

* :arrow_forward: **Ninja**

    Site: https://ninja-build.org

    Price: free

    Project build manager for C and C++ applications. The main advantage of this manager is quick project assembly. It supports cross-platform development and works with all popular compilers.

## :mag: Code analyzers and runtime checks

* :arrow_forward: **PVS Studio**

    Site: https://pvs-studio.com

    Price: 30 days trial

    Cross-platform (Windows, Linux, MacOS) static code analyzer by PVS-Studio. The main aim of the analyzer is to analyze the source code for various errors that may go undetected by compilers or during code review. It helps reduce the number of errors related to language syntax and pitfalls.

* :arrow_forward: **Cppcheck**

    Site: https://cppcheck.sourceforge.io

    Price: free

    A free code analyzer that helps you catch common errors in your source code that might be missed by the compiler or during code review. It is cross-platform and supports popular Linux distributions and Windows.

* :arrow_forward: **Valgrind**

    Site: https://www.valgrind.org

    Price: free

    A set of tools that can help you investigate various problems while the application is running, such as memory leaks and performance profiling. It is compatible with multiple Linux distributions.

* :arrow_forward: **Sanitizers**

    Site: https://clang.llvm.org/docs/

    Runtime checkers such as AddressSanitizer, UndefinedBehaviorSanitizer, ThreadSanitizer, and MemorySanitizer help catch memory, undefined behavior, and concurrency issues during development and CI.

* :arrow_forward: **CodeQL**

    Site: https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql

    A semantic code analysis engine that can be used in GitHub code scanning to find security and correctness issues in C and C++ projects.

## :test_tube: Testing and automation

* :arrow_forward: **GoogleTest**

    Site: https://google.github.io/googletest/

    A widely used C++ testing and mocking framework. It is a common choice for unit tests in commercial and open-source projects.

* :arrow_forward: **Catch2**

    Site: https://github.com/catchorg/Catch2

    A C++ testing framework that is convenient for small projects, examples, and readable test cases.

* :arrow_forward: **libFuzzer**

    Site: https://llvm.org/docs/LibFuzzer.html

    A coverage-guided fuzzing engine for finding crashes and edge cases by generating large numbers of inputs automatically.

* :arrow_forward: **GitHub Actions**

    Site: https://docs.github.com/en/actions

    A common CI platform for building, testing, linting, and packaging C++ projects on every change.

## :floppy_disk: Git clients

* :arrow_forward: **SmartGit**

    Site: https://www.syntevo.com/smartgit/

    Price: free for open source projects

    A complete, cross-platform tool for working with Git repositories. Out of the box, it provides the following features: receiving and sending changes to the repository, viewing the history of changes, a text editor for resolving conflicts, etc. Supports integration with all popular repositories like GitHub, Bitbucket, GitLab, etc.

* :arrow_forward: **Atlassian SourceTree**

    Site: https://www.sourcetreeapp.com/

    Price: free

    A great free alternative for working with Git using a GUI. It has the same functionality as SmartGit, with the exception of the absence of its own editor for conflict resolution. However, this can be easily fixed by integrating Visual Studio Code or any other editor that can compare files. In all other respects, it completely duplicates the functionality of SmartGit: it is cross-platform and supports integration with popular repositories such as GitHub, Bitbucket, GitLab, etc.

* :arrow_forward: **GitKraken**

    Site: https://www.gitkraken.com/

    Price: free for open source projects

    A cross-platform and highly efficient client for Windows, Linux, and macOS. It supports integration with GitHub, Bitbucket, and GitLab, and has all the necessary functionality for everyday work, such as viewing the change history, submitting and receiving changes, switching between branches, and a built-in conflict resolution editor.

---

[**To main page**](../README.md)
