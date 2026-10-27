

# A tutorial on doing analyses on Denmark Statistics or GenomeDK

<!-- TODO: Add Zenodo DOI here after publishing -->

<!-- TODO: Uncomment release badge if creating releases -->

<!-- [![GitHub
Release](https://img.shields.io/github/v/release/dp-next/server-analysis-tutorial.svg)](https://github.com/dp-next/server-analysis-tutorial/releases/latest) -->

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-teal.json?raw=true.svg)](https://github.com/copier-org/copier)
[![GitHub
License](https://img.shields.io/github/license/dp-next/server-analysis-tutorial.svg)](https://github.com/dp-next/server-analysis-tutorial/blob/main/LICENSE.md)
[![Build
website](https://github.com/dp-next/server-analysis-tutorial/actions/workflows/build-website.yml/badge.svg)](https://github.com/dp-next/server-analysis-tutorial/actions/workflows/build-website.yml)
[![Checks](https://github.com/dp-next/server-analysis-tutorial/actions/workflows/checks.yml/badge.svg)](https://github.com/dp-next/server-analysis-tutorial/actions/workflows/checks.yml)
[![pre-commit.ci
status](https://results.pre-commit.ci/badge/github/dp-next/server-analysis-tutorial/main.svg)](https://results.pre-commit.ci/latest/github/dp-next/server-analysis-tutorial/main)
[![lifecycle](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
<!-- TODO: Switch to active once it's published. -->
<!-- [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) -->

## Description

<!-- TODO: Very brief intro, motivation, and overview of workshop. -->

This repository contains the lesson, lecture, and assignment material
for the workshop, including the website source files and other
associated workshop administration and development files. For more
detail on the workshop, check out the [welcome
page](https://dp-next.github.io/server-analysis-tutorial).

> [!TIP]
>
> This workshop repository was generated from the
> [`template-workshop`](https://github.com/rostools/template-workshop)
> rostools template.

## Instructional Design

The lectures and lessons in this workshop are designed to be presented
primarily with a participatory live-coding approach. This involves an
teacher typing and running code in an editor or similar platform in
front of the class, while the class follows along using their own
computers. Exercises are interspersed in the lesson material, allowing
participants to collaboratively work on smaller coding problems for a
few minutes. All lesson materials are provided ahead of time on the
workshop website for participants to refer to during lectures.

## Lesson content

The teaching material is found mainly in these locations:

- `index.Rmd`: Contains the overview of the workshop.
- `overview/` folder: Contains the files that give an overview to the
  workshop, such as the syllabus and schedule.
- `pre-workshop/`: Contains the files needed before the workshop, like
  the pre-workshop tasks.
- `sessions/`: Contains the files used during the workshop
  (e.g. code-along material).
- `appendix/`: Contains the files used to support the workshop, such as
  code of conduct, changelog, contributing guides, and instructions for
  teachers.
- `slides/`: Contains the lecture slides that are rendered into HTML
  slides from Markdown.

The website is generated with [Quarto](https://quarto.org/), so it
follows the file and folder structure conventions from that package.

## Contributing

If you are interested in contributing to the workshop material, please
refer to the [contributing guidelines](CONTRIBUTING.md). For guidelines
on how to be a helper or teacher, check out the [For
teachers](https://guides.rostools.org/instructors) page.

Please note that the project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By contributing to or being involved in
this project, you agree to abide by its terms.

<!-- TODO: Unhide after having contributors -->

## Licensing

This project is licensed under the [CC-BY-4.0 License](LICENSE.md).

## Re-use

The workshop is largely designed to be taught in the order given, as
each session builds off of the previous ones. The easiest way to use
this material is to use it as-is, making use of the tips and
instructions found throughout this page. The only thing you might want
to make as your own would be the slides, however, they are also good
enough to use on their own too.

To help with general admin tasks of running the workshop, there is the
[samwise](https://github.com/rostools/samwise) R package.

## Changelog

For a list of changes, see our [changelog](CHANGELOG.md) page.
