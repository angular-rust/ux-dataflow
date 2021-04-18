<div align="center">

[![](https://dudochkin-victor.github.io/assets/ux-dataflow/logo-wide.svg)](#top)
# UX Dataflow

[![API Docs][docrs-badge]][docrs-url]
[![Crates.io][crates-badge]][crates-url]
[![Code coverage][codecov-badge]][codecov-url]
[![Tests][tests-badge]][tests-url]
[![MPL-2.0 licensed][license-badge]][license-url]
[![Gitter chat][gitter-badge]][gitter-url]
[![loc][loc-badge]][loc-url]
</div>

[docrs-badge]: https://img.shields.io/docsrs/ux-dataflow?style=flat-square
[docrs-url]: https://docs.rs/ux-dataflow/
[crates-badge]: https://img.shields.io/crates/v/ux-dataflow.svg?style=flat-square
[crates-url]: https://crates.io/crates/ux-dataflow
[license-badge]: https://img.shields.io/badge/license-MPL--2.0-blue.svg?style=flat-square
[license-url]: https://github.com/angular-rust/ux-dataflow/blob/master/LICENSE
[gitter-badge]: https://img.shields.io/gitter/room/angular_rust/community.svg?style=flat-square
[gitter-url]: https://gitter.im/angular_rust/community
[tests-badge]: https://img.shields.io/github/workflow/status/angular-rust/ux-dataflow/Tests?label=tests&logo=github&style=flat-square
[tests-url]: https://github.com/angular-rust/ux-dataflow/actions/workflows/tests.yml
[codecov-badge]: https://img.shields.io/codecov/c/github/angular-rust/ux-dataflow?logo=codecov&style=flat-square&token=M7BW7mahNb
[codecov-url]: https://codecov.io/gh/angular-rust/ux-dataflow
[loc-badge]: https://img.shields.io/tokei/lines/github/angular-rust/ux-dataflow?style=flat-square
[loc-url]: https://github.com/angular-rust/ux-dataflow

**UX Dataflow** is a streaming capable data multiplexer that allows you to aggregate data and then process it using a Chain of Responsibility design pattern.

UX Dataflow was originally an attempt to implement a DataTable-like structure from Python's powerful data analysis library - Pandas. 

But during the development process, it became clear that a data processing mechanism was needed that would allow data to be extended by adding new data channels and the ability to handle asynchronous data streams.

**UX Dataflow** is part of the Angular Rust framework.

**Angular Rust** is a high productivity, `platform-agnostic` frontend framework for the [Rust language](https://www.rust-lang.org/). It now supports desktop and web development. Angular Rust currently uses Clutter for desktop development and WebAssembly for web development. We are planning to add support for mobile development.

![Angular Rust structure](https://dudochkin-victor.github.io/assets/angular-rust/structure.svg)

## Features

- [x] DataFrame abstraction for extending data-feeds (channels)
- [x] Metadata describing DataStream channels
- [ ] Streaming capability
- [ ] Composite data channel support.
- [ ] Support for heterogeneous data links such as dataset of OHLCV, f64, i64 and U256 in the same DataStream.

> The unimplemented features depend on `User-Experience` during the development of the [UX Indicators](https://github.com/angular-rust/ux-indicators) crate. So far, we have implemented the features required for the [UX Charts](https://github.com/angular-rust/ux-charts) crate.

## Quick Start

Install UX Dataflow:

	cargo add ux-dataflow

## Learn More

* [Manual, Docs, etc](https://angular-rust.github.io/)
* [Samples](https://github.com/angular-rust/ux-samples)
* [Apps using Angular Rust](https://github.com/angular-rust/ux-dataflow/wiki/Apps-in-the-Wild)
* [Articles Featuring Angular Rust](https://github.com/angular-rust/ux-dataflow/wiki/Articles)

## Community

 [![](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/groups/angular.rust) 
 [![](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/questions/tagged/angular-rust) 
 [![](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCBJTkSl_JWShuolUy4JksTQ) 
 [![](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@angular.rust) 
 [![](https://img.shields.io/gitter/room/angular_rust/angular_rust?style=for-the-badge)](https://gitter.im/angular_rust/community)


## Contributing

We believe the wider community can create better code. The first tool for improving the community is to tell the developers about the project by giving it a star. More stars - more members.

  [![](https://dudochkin-victor.github.io/assets/star-me-wide.svg)](https://github.com/angular-rust/ux-dataflow#top)
 
Angular Rust is a community effort and we welcome all kinds of contributions, big or small, from developers of all backgrounds. We want the Angular Rust community to be a fun and friendly place, so please review our [Code of Conduct](CODE_OF_CONDUCT.md) to learn what behavior will not be tolerated.

### New to Angular Rust?

Start learning about the framework by helping us improve our [documentation](https://angular-rust.github.io/). Pull requests which improve test coverage are also very welcome.

### Looking for inspiration?

Check out the community curated list of awesome things related to Angular Rust / WebAssembly at [awesome-angular-rust](https://github.com/angular-rust/awesome-angular-rust).

### Confused about something?

Feel free to drop into our [Gitter chatroom](https://gitter.im/angular_rust/community) or open a [new "Question" issue](https://github.com/angular-rust/ux-dataflow/issues/new/choose) to get help from contributors. Often questions lead to improvements to the ergonomics of the framework, better documentation, and even new features!

### Ready to dive into the code?

After reviewing the [Contributing Code Guidelines](CONTRIBUTING.md), check out the ["Good First Issues"](https://github.com/angular-rust/ux-dataflow/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) (they are eager for attention!). Once you find one that interests you, feel free to assign yourself to an issue and don't hesitate to reach out for guidance, the issues vary in complexity.

### Let's help each other!

Come help us on the [issues that matter that the most](https://github.com/angular-rust/ux-dataflow/labels/%3Adollar%3A%20Funded%20on%20Issuehunt) and receive a small cash reward for your troubles. We use [Issuehunt](https://issuehunt.io/r/angular-rust/ux-dataflow/) to fund issues from our Open Collective funds. If you really care about an issue, you can choose to add funds yourself! 

### Found a bug?

Please [report all bugs!](https://github.com/angular-rust/ux-dataflow/issues/new/choose) We are happy to help support developers fix the bugs they find if they are interested and have the time.

## Todo
- [ ] Documentation
- [ ] DataStream controller infographics
