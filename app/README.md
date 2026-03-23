
# Q1 Compose State and Recomposition

This project is a simple counter app made with Jetpack Compose.

The screen shows a number that starts at `0`.

It has two buttons:

- **Increment**: adds 1 to the number
- **Reset**: changes the number back to 0

When the number changes, the screen updates right away.
This works because the app uses Compose state.

The app also keeps the number after screen rotation.
This is done by using `rememberSaveable`.

## What this app does

This app demonstrates:

- basic state in Jetpack Compose
- recomposition when state changes
- saving state during screen rotation
- button click actions


`mutableStateOf(0)` creates a state value starting at 0.

`rememberSaveable` helps save that value when the screen rotates.

## How AI was used in this question

AI was used for learning support and syntax help.

AI helped me about:

* the difference between `remember` and `rememberSaveable`
* the syntax of `mutableStateOf`
* the syntax of a `Button` in Jetpack Compose
* to generate this README

AI helped explain the ideas and syntax, and I used that help to complete the work.

