# Language Migration Tool for Sitecore 9.0

## Table of Contents
 - [Introduction](#introduction)
 - [Difference with original source code](#difference-with-original-source-code)

## Introduction
[Back to the contents](#table-of-contents)

It's updated Language Migration Tool to work with Sitecore 9.0 and .Net Framework 4.6.2. The original source code [here](https://github.com/Verndale-Corp/Sitecore-Language-Migration-Tool)

## Difference with original source code
[Back to the contents](#table-of-contents)

The list of the difference with original:

1. .Net Framework version was updated to 4.6.2
2. Sitecore references were updated to work with SItecore 9.0
3. Output assembly name and solution/project names were changed from ``Verndale.SharedSource`` to ``WeAreYou.LanguageMigrationTool``. But the namespace in source code(as it exist in aspx file) still the same (starts with ``Verndale``)
4. NuGet metadata file is included in ``nuget`` folder of the root of the repository
5. Apache license was included in the repository 