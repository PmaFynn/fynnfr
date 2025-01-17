---
title: 'td'
date: 2024-10-13T14:28:59+02:00
tags: ['Rust', 'Projects', 'Terminal User Interface', 'CLI']
# weight: 1
# aliases: ["/first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
hideAuthor: true
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: false
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowWordCount: false
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---
My motivation for this project was rather primitive.
Quite often while working on something I had an idea or generally just remembered something I had to do.
Before this I had to either write it down in my notes on my phone or pc which took ages (making up your mind where to save it, opening application, file to save it in etc. etc.) which sometimes resulted in me not bothering to write it down at all thinking I could just remember it again (you can imagine how well that worked).
To be honest, I did not use any other todo application beforehand because just by briefly looking through them they did not fullfill my needs at all.
The biggest requirement was a cli tool since I spend most of my time in the terminal and even if I was not currently in the terminal it is the program which I can reach the fastest (Mod + Enter in my case). 
And while there are some good solutions out there [^1].
I mean, a todo applicaton is one of the classic beginner projects, so there gotta be quite a few out there lol.
No one hit all my requirements and nice-to-haves.
I have also wanted to learn or at least try out Rust so I thought I just as well do it myself. Well, here we are. Enjoy the readme...

[^1]: e.g. [todo.txt-cli](https://github.com/todotxt/todo.txt-cli) and
## Rust todo Application: [Github](https://github.com/pmafynn/td)

<!--![Build Status](https://img.shields.io/github/workflow/status/yourusername/yourprojectname/CI)-->
<!-- ![License](https://img.shields.io/github/license/yourusername/yourprojectname)-->
<!--![Version](https://img.shields.io/github/v/release/yourusername/yourprojectname)-->

![Showcase](/blog/td/tdShowcase.gif)

A simple, fast, and efficient TUI todo application written in Rust with *vim bindings*.

### Features

#### CLI Features

- Add new tasks **FAST** (see usage below)

#### TUI Features - Keybinds

| Action                                                                      | Keybind    |
|-----------------------------------------------------------------------------|------------|
| quit application                                                            | q, Esc     |
| exit out of help                                                            | Esc        |
| down                                                                        | j          |
| up                                                                          | k          |
| toggle visible todos                                                        | h, l, tab  |
| goTop                                                                       | g          |
| completly delete a finished todo                                            | d          |
| add new todo                                                                | a          |
| rename selected todo                                                        | n          |
| goBottom                                                                    | G          |
| search for *input* <- highlights all but selects only the last found        | /          |
| switch status of selected todo                                              | enter      |

### Installation

#### Prerequisites

- Ensure you have [Rust](https://www.rust-lang.org/tools/install) installed on your machine.

#### Clone the repository

```sh
git clone https://github.com/pmafynn/td.git
cd td
```

#### Build the application

```sh
cargo build --release
```

#### Run the application

```sh
./target/release/td
```

Create alias or add to path if you like it

### Usage

Here are some common commands you can use with this ToDo application:

#### Add a new task

```sh
td "new task"
```
or 
```sh
td new task
```
#### Enter TUI

```sh
td
```

#### For more options and usage, run:

```sh
td --help
```

### License

[LICENSE](LICENSE.md)

### Acknowledgements

- Thanks to the [Rust](https://www.rust-lang.org/) community for their amazing work on the language and ecosystem.


