# Lint Stack Overflow repro

This project showcases a stack overflow crash in Android Lint when nesting modules.

To run into the crash, run `./gradlew lintDebug`, or just
`./gradlew :core:utils:testing:lintReportDebug`, which is the failing task in the chain.
