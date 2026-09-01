# Atari Homebrew Games List

The Atari Homebrew Games List is a community-maintained registry of Atari homebrew games across multiple Atari platforms.

It collects information about released, completed, and work-in-progress homebrew games, including participants and their roles, publishers, platforms, ROM size, release status, and relevant source links.

> This is a community-maintained project under `atariage-community`. It is not an official AtariAge repository.

## Quick links

* **[Browse the Homebrew Games List](https://atariage-community.github.io/homebrew-list/index.html)**
* **[View the canonical game data](homebrews.yaml)**

## Data source

`homebrews.yaml` is the canonical source of the game data.

Information is collected from community sources such as AtariAge and ZeroPage Homebrew. Where a more complete or structured source is available, such as a spreadsheet or database, it may be used as the basis for the data.

The goal is to preserve the information provided by the original sources rather than unnecessarily normalizing or simplifying it.

## Game information

A game entry may contain:

* `title` — game/project name
* `platforms` — one or more target platforms
* `participants` — people or organizations involved in the project, with roles such as development, graphics, music, testing, packaging, box art, etc.
* `publishers` — publisher(s), where applicable
* `rom_size` — ROM size in bytes
* `status` — current project status
* `physical_release` — whether a physical release exists
* `sources` — source datasets or threads
* `urls` — relevant project, download, source, or discussion links
* `history` — known status changes over time
* `notes` — additional information

The schema is intended to remain simple and extensible. New fields should be discussed before being introduced broadly.

## Contributing

The data is maintained as a community project.

If you spot missing, incorrect, or outdated information, please open an issue or submit a pull request with the proposed changes.

When adding or correcting information, please provide a source whenever possible.

You do not need to be a GitHub expert to contribute. Suggestions and corrections can also be submitted through the project discussion or issue tracker.

## Repository structure

```text
homebrews.yaml                  # canonical game data
docs/
  index.html                    # public web interface
```

## Attribution

Many thanks to the Atari homebrew community, AtariAge, ZeroPage Homebrew, and everyone contributing information about Atari homebrew development.

This project is intended to complement existing community lists and preserve their information in a structured, machine-readable format.
