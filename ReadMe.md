# **Adding NetBSD KNF to clang-format**

This is the repository for the GSoC 2019 project of "[Add KNF (NetBSD style) clang-format configuration
](https://wiki.netbsd.org/projects/project/clang-format/)"

For more details about what I have done during GSoC 2019, you can refer to these articles: 
* [GSoC 2019 Report: Adding NetBSD KNF to clang-format, Part 1](http://blog.netbsd.org/tnf/entry/gsoc_2018_report_adding_netbsd)

* [GSoC 2019 Report: Adding NetBSD KNF to clang-format, Part 2](http://blog.netbsd.org/tnf/entry/gsoc_2019_report_adding_netbsd)
*  

## ** Branch  gsoc-netbsdKNF**
This is the main branch I have been working on. This is a forked repository of [llvm-mirror/clang](https://github.com/llvm-mirror/clang).

The branch contains the following changes:

* **New Style Options introduced**
    * BitFieldDeclarationsOnePerLine( Commit: [1](https://github.com/sh4nnu/clang/commit/3e99a78364972ee56f68cf22ef2e4bf19e113bad), Bug: [1](https://github.com/sh4nnu/clang/issues/1), Reviews: [1](https://reviews.llvm.org/D63062))

    * AlignConsecutiveListElements( Commit: [1](https://github.com/sh4nnu/clang/commit/4b4cd45a5f3d211008763f1c0235a22352faa81e), Bug: [1](https://github.com/sh4nnu/clang/issues/2))

    * AlignConsecutiveListElements( Commit:[1](https://github.com/sh4nnu/clang/commit/4b4cd45a5f3d211008763f1c0235a22352faa81e), Bug: [1](https://github.com/sh4nnu/clang/issues/2), Status: **Work In Progress**)

* **Modifications made to existing styles**
    * SpacesAfterTrailingComments (Commit: [1](https://github.com/sh4nnu/clang/commit/76984db63d534098f58376f6b6ca20f7969f72a4), Reviews: [1](https://reviews.llvm.org/D65648))
       * **Description:** This style option now adds spaces before block comments( /* .. */) along with line comments (//... )
    * SortIncludes and IncludeCategories (Commit: [1](https://github.com/sh4nnu/clang/commit/772551b43ce66cf443e5a025797816d43b5a3be4), Reviews:[1](https://github.com/sh4nnu/clang/commit/772551b43ce66cf443e5a025797816d43b5a3be4), Status: **Ready to Merge**)
        * **Description:** This modification helps users to define differentt prioritties for sorting and grouping ```#includes```.



