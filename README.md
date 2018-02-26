# [React Native](https://facebook.github.io/react-native/) &middot;  [![Circle CI Status](https://circleci.com/gh/facebook/react-native.svg?style=shield)](https://circleci.com/gh/facebook/react-native) [![npm version](https://badge.fury.io/js/react-native.svg)](https://badge.fury.io/js/react-native) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md#pull-requests)

This is a patch to react-native that implements importantForAccessibility in iOS. The purpose is to fix a bug causing voiceover to read elements that should be hidden. More detail can be found at [this issue](https://github.com/facebook/react-native/issues/9725) and [this PR](https://github.com/facebook/react-native/pull/11788).

Thanks to sdg9, omeid, and others for detailing the problem in the github PR and issue threads. Also thanks to awseeley for putting up a fork of react-navigation that fixed the problem on android. [awseeley's fork](https://github.com/awseeley/react-navigation) can be used in conjunction with this fork of react-native to fix the problem on iOS as well. Thanks for sdg9 for providing the code used in this fork.

---

## License

React Native is [MIT licensed](./LICENSE).

React Native documentation is [Creative Commons licensed](./LICENSE-docs).

---

<img src="https://avatars2.githubusercontent.com/u/69631?s=200&v=4" width="50"></img>
