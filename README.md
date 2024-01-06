# dtxdescribe
LaTeX dtxdescribe package — Describe additional object types in dtx or tex source files

The doc package includes tools for describing macros and environments in LaTeX source .dtx format. The dtxdescribe package adds additional tools for describing booleans, lengths, counters, hooks, keys, packages, classes, options, files, commands, arguments, and other objects. dtxdescribe also works with the regular document classes, for those who do not wish to use the ltxdoc class and .dtx files.

Each described item is given a margin tag similar to \DescribeEnv, and is listed in the index by itself and also by type of object displayed in parentheses (length, filename, etc). Each item may be sorted further by an optional category displayed in brackets, such as [category_name].

The dtxexample environment is provided for typesetting example code and its results.

Environments are also provided for displaying verbatim or formatted source code, user-interface displays, and sidebars with titles.

Macros are provided for formatting the names of inline LaTeX objects such as packages and booleans, as well as program and file names, file types, internet objects, the names of certain programs, a number of logos, and inline dashes and slashes.

dtxdescribe works with the ltxdoc class, but also works with the standard classes as well.

The code is at CTAN: https://ctan.org/pkg/dtxdescribe
