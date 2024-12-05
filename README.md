# Expo CLI Error: Invariant Violation: requireNativeComponent... not found in UIManager

This repository demonstrates a common yet elusive bug in Expo CLI related to native module integration. The error message, "Invariant Violation: requireNativeComponent: ... was not found in the UIManager," is generic and points to several possible root causes. This makes debugging challenging, and this repo provides a reproducible example and a solution.

## The Problem
The main issue is a mismatch or conflict between the Expo CLI version, React Native version, and the native modules used in your project. This can happen due to:

* Incorrect or missing native module installations.
* Conflicts between different versions of native modules.
* Issues in `app.json` or `package.json` configuration.

## Reproducible Example (bug.js)
[Insert code reproducing the error]