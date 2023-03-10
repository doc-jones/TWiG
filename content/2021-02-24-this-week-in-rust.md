Title: This Week in Rust 379
Number: 379
Date: 2021-02-24
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a systems language pursuing the trifecta: safety, concurrency, and speed.
This is a weekly summary of its progress and community.
Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

# Updates from Rust Community

No newsletters or official blog posts this week.

### Project/Tooling Updates
* [MoonZoon - New Rust fullstack framework](https://moonzoon.rs)
* [rust-analyzer Changelog #65](https://rust-analyzer.github.io/thisweek/2021/02/22/changelog-65.html)
* [Knurling-rs changelog #17](https://ferrous-systems.com/blog/knurling-changelog-17/)

### Observations/Thoughts
* [Rust for web development: 2 years later](https://kerkour.com/blog/rust-for-web-development-2-years-later/)
* [Integrating Rust and C++ in Firefox](https://manishearth.github.io/blog/2021/02/22/integrating-rust-and-c-plus-plus-in-firefox/)
* [Building a telnet chat server with Rust and Lunatic](https://dev.to/bkolobara/how-i-built-a-telnet-chat-server-in-2021-with-webassembly-2711)
* [Against Packaging Rust Crates](https://fy.blackhats.net.au/blog/html/2021/02/16/against_packaging_rust_crates.html)
* [Why building a front-end framework in Rust is hard](https://lik.ai/blog/why-building-a-front-end-framework-in-rust-is-hard)
* [Oxidizing Kraken](https://blog.kraken.com/post/7964/oxidizing-kraken/?)
* [Maybe We Can Have Nice Things](https://noncombatant.org/2021/02/16/maybe-we-can-have-nice-things/)
* [Three Things I Miss About Rust](https://bennett.dev/)
* [Storages: an alternative to allocators](https://www.reddit.com/r/rust/comments/lp0i5r/storages_an_alternative_to_allocators/)

### Rust Walkthroughs
* [Rust ownership, the hard way](https://chrismorgan.info/blog/rust-ownership-the-hard-way/)
* [Handling Unix Kill Signals in Rust](https://dev.to/talzvon/handling-unix-kill-signals-in-rust-55g6)
* [Replacing FastAPI with Rust: Part 5 - Rocket 0.5](https://dev.to/dbanty/replacing-fastapi-with-rust-part-5-rocket-0-5-3kb3)
* [Running ML models in a game (and in Wasm!)](https://dev.to/mockersf/running-ml-models-in-a-game-and-in-wasm-12i2)
* [What would SQLite look like if written in Rust? - Part 2](https://dev.to/joaoh82/what-would-sqlite-look-like-if-written-in-rust-part-2-4g66)
* [A primer on code generation in Cranelift](https://blog.benj.me/2021/02/17/cranelift-codegen-primer/)
* [Testing a Hardware Abstraction Layer (HAL)](https://ferrous-systems.com/blog/defmt-test-hal/)
* [Cross Compiling Rust GTK Projects for Windows](https://nivethan.dev/devlog/cross-compiling-rust-gtk-projects-for-windows.html)
* [Procedural Macros: A simple derive macro](https://blog.turbo.fish/proc-macro-simple-derive/)
* [Building an OpenStreetMap app in Rust, Part III](https://blogg.bekk.no/building-an-openstreetmap-app-in-rust-part-iii-ab9ad4b83bd8)
* [Generalizing over Generics in Rust (Part 1.5): Mechanisms](https://rustyyato.github.io/type/system,type/families/2021/02/22/Type-Families-1_5.html)
* [Macros in Rust: A tutorial with examples](https://blog.logrocket.com/macros-in-rust-a-tutorial-with-examples/)
* [ES] [Pipelines en Rust(II)](https://yorodm.is-a.dev/blog/rust-pipeline-pattern-ii/)
* [video] [Rust for Windows](https://youtu.be/LajquCjHXK4)
* [video] [Crust of Rust: Subtyping and Variance](https://youtu.be/iVYWDIW71jk)
* [video] [Learning Rust: Web Server with Actix Web](https://youtu.be/PMa2m0Fe-Q4)
* [video] [series] [Rust For Beginners - Watch me code the Rustlings Tutorial](https://youtube.com/playlist?list=PLauX9TuJ8sfyaLPZ1udS3zS_V9YXdsbtc)
* [video] [series] [Easy Rust - learn to program in Rust with simple English](https://youtube.com/playlist?list=PLfllocyHVgsRwLkTAhG0E-2QxCf-ozBkk)

### Miscellaneous
* [Python cryptography, Rust, and Gentoo](https://lwn.net/Articles/845535/)
* [Mitigating Memory Safety Issues in Open Source Software](https://security.googleblog.com/2021/02/mitigating-memory-safety-issues-in-open.html)
* [matklad @ NEAR](https://matklad.github.io/2021/02/15/NEAR.html)
* [Application-wide panic handling](https://domwillia.ms/panik/)
* [Benchmarking low-level I/O: C, C++, Rust, Golang, Java, Python](https://medium.com/star-gazers/benchmarking-low-level-i-o-c-c-rust-golang-java-python-9a0d505f85f7)
* [video] [Ask the Expert: Rust at Microsoft](https://youtu.be/1uAsA1hm52I)
* [video] [AWS re:Invent 2020: Next-gen networking infrastructure with Rust and Tokio](https://youtu.be/MZyleK8elPk)
* [video] [Interview Part 2/2 with Ashley Williams, Rust Foundation Interim Executive Director](https://youtu.be/eFQVxQsYcJ8)

# Crate of the Week

This week's crate is [lever](https://crates.io/crates/lever), a library for writing transactional systems.

Thanks to [Mahmud Bulut](https://users.rust-lang.org/t/crate-of-the-week/2704/882) for the suggestion!

[Submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

# Call for Participation

Always wanted to contribute to open-source projects but didn't know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

[starlight - Support for "unsafe" cases of `finally`](https://github.com/Starlight-JS/starlight/issues/7)

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

# Updates from Rust Core

329 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2021-02-15..2021-02-22

* [suggest to create a new `const` item if the `fn` in the array is a `const fn`](https://github.com/rust-lang/rust/pull/81503)
* [fixing bad suggestion for `_` in `const` type when a function](https://github.com/rust-lang/rust/pull/81914)
* [simplify `eat_digits`](https://github.com/rust-lang/rust/pull/81427)
* [precompute ancestors when checking privacy](https://github.com/rust-lang/rust/pull/81574)
* [optimize counting digits in line numbers during error reporting](https://github.com/rust-lang/rust/pull/82248)
* [only store a `LocalDefId` in some HIR nodes](https://github.com/rust-lang/rust/pull/81611)
* [to digit simplification](https://github.com/rust-lang/rust/pull/82094)
* [reduce size of `InterpErrorInfo` to 8 bytes](https://github.com/rust-lang/rust/pull/82116)
* [pass large interpreter types by reference, not value](https://github.com/rust-lang/rust/pull/82124)
* [improve `assert_eq!` and `assert_ne!`](https://github.com/rust-lang/rust/pull/79100)
* [add `Mutex::unlock`](https://github.com/rust-lang/rust/pull/81873)
* [stabilize `Arguments::as_str`](https://github.com/rust-lang/rust/pull/82120)
* [futures: `FuturesUnordered`: do not poll the same future twice per iteration](https://github.com/rust-lang/futures-rs/pull/2333)
* [remove `unsafe impl Send for CompletedTest` & `TestResult`](https://github.com/rust-lang/rust/pull/82302)
* [test: print test name only once on timeout](https://github.com/rust-lang/rust/pull/82349)
* [cargo: propagate `lto=off` harder](https://github.com/rust-lang/cargo/pull/9182)

## Rust Compiler Performance Triage

Overall, a positive week for compiler performance with only one moderate regression. The change that introduced the regression leads to significantly improved [bootstrap speed](https://github.com/rust-lang/rust/pull/70951#issuecomment-766292996) of the compiler as well as easier maintainability.

Triage done by **@rylev**.
Revision range: [f1c47c..301ad8a](https://perf.rust-lang.org/?start=f1c47c79fe8438ed241630f885797eebef3a6cab&end=301ad8a4fa3ea56fb980443b7997c8f9d72dd717&absolute=false&stat=instructions%3Au)

1 Regression, 5 Improvements, 0 Mixed
0 of them in rollups

## Approved RFCs

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* [RFC: Checking conditional compilation at compile time](https://github.com/rust-lang/rfcs/pull/3013)

## Final Comment Period

Every week [the team](https://www.rust-lang.org/team.html) announces the
'final comment period' for RFCs and key PRs which are reaching a
decision. Express your opinions now.

### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)


* [RFC - cargo templates](https://github.com/rust-lang/rfcs/pull/2922)
* [rfc: make cargo install extensible](https://github.com/rust-lang/rfcs/pull/2376)

### [Tracking Issues & PRs](https://github.com/rust-lang/rust/labels/final-comment-period)

* [disposition: merge] [Allow specifying alignment for functions](https://github.com/rust-lang/rust/pull/81234)
* [disposition: merge] [Make rustdoc lints a tool lint instead of built-in](https://github.com/rust-lang/rust/pull/80527)
* [disposition: merge] [Stabilize `unsafe_op_in_unsafe_fn` lint](https://github.com/rust-lang/rust/pull/79208)
* [disposition: merge] [[librustdoc] Only split lang string on `,`, ` `, and `\t`](https://github.com/rust-lang/rust/pull/78429)
* [disposition: merge] [Lint for unused borrows as part of `UNUSED_MUST_USE` ](https://github.com/rust-lang/rust/pull/76894)
* [disposition: merge] [Tracking Issue for str_split_once](https://github.com/rust-lang/rust/issues/74773)
* [disposition: merge] [Tracking Issue for ASCII methods on OsStr](https://github.com/rust-lang/rust/issues/70516)

## New RFCs

* [RFC: An edition-compatible system for "removing" deprecated items from the standard library](https://github.com/rust-lang/rfcs/pull/3088)
* [RFC: Declarative macro metavariable expressions](https://github.com/rust-lang/rfcs/pull/3086/files)
* [RFC: 2021 Edition](https://github.com/rust-lang/rfcs/pull/3085)
* [Add filename information to `std::io::Error` to improve `std::io` error messages ](https://github.com/rust-lang/rfcs/pull/3084)
* [Multi-part examples in rustdoc](https://github.com/rust-lang/rfcs/pull/3081)

# Upcoming Events

### Online
* [February 27, London, UK - Rust (Remote) Hack & Learn - Rust London](https://github.com/rust-ldn/rust-hack-and-learn)
* [March 1, Cardiff, UK - Rust and Cpp Cardiff :: v1.9 - Rust and C++ Cardiff](https://www.meetup.com/rust-and-c-plus-plus-in-cardiff)
* [March 2, Dublin, IE - March Remote Meetup - Luca Palmieri - Rust Dublin](https://www.meetup.com/Rust-Dublin/events/276334977/)
* [March 3, Indianapolis, IN, US - Indy.rs - with Social Distancing - Indy Rust](https://www.meetup.com/indyrs/events/jhfstryccfbfb/)
* [March 3, Denver, CO, US - Building a Runtime Reflection System for Rust by Sam Scott - Rust Denver](https://www.meetup.com/Rust-Boulder-Denver/events/275738407/)
* [March 4, Berlin, DE - Rust Hack and Learn - Berline.rs](https://www.meetup.com/opentechschool-berlin/events/txcprryccfbgb/)
* [March 9, Saarb??cken, Saarland, DE - Meetup: 9u16 (virtual) - Rust Saar](https://www.meetup.com/de-DE/Rust-Saar/events/276401469/)
* [March 9, Seattle, WA, US - Monthly meetup - Seattle Rust Meetup](https://www.meetup.com/Seattle-Rust-Meetup/events/gskksryccfbmb/)

### North America
* [March 10, Atlanta, GA, US - Grab a beer with fellow Rustaceans - Rust Atlanta](https://www.meetup.com/Rust-ATL/events/qxqdgryccfbnb/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

# Rust Jobs

**ForAllSecure**

* [Senior/Staff Engineer, Backend - RUST](https://boards.greenhouse.io/forallsecure/jobs/5086295002)

**NZXT**

* [Senior Software Engineer (Rust & C++) (Remote)](https://nzxt.bamboohr.com/jobs/view.php?id=259)

**Parity**

* [Several Rust Engineering Positions (Berlin, DE)](https://www.parity.io/jobs/#jobs)

*Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) to get your job offers listed here!*

# Quote of the Week

> Finally, I feel it is necessary to debunk the ???*fighting the borrow checker*??? legend, a story depicting the Rust compiler as a boogeyman: in my experience, it happens mostly to beginners and the 1% trying to micro-optimize code or push the boundaries. Most experienced Rust developers know exactly how to model their code in a way that no time is wasted fighting the compiler on design issues, and can spot anti-patterns at a glance, just like most people know how to drive their car on the correct side of the road to avoid accidents, and notice those who don???t!

??? [Simon Chemouil on the Kraken blog](https://blog.kraken.com/post/7964/oxidizing-kraken/)

Thanks to [scottmcm](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1004) for the suggestion.

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), and [cdmistman](https://github.com/cdmistman).*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/lrw51r/this_week_in_rust_379/)</small>
