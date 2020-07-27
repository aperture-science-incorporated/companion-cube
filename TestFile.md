# Repolinter Report

*This report was generated automatically by the Repolinter Action bot. If you see an issue please report it to ...*

Repolinter is a tool used by New Relic to maintain consistency across our repositories. Each rule below represents a policy that New Relic implements in the Open Source initiative. For more information about this issue and/or Repolinter, please go to ...


- [Summary](#summary)
- [Fail](#fail)
  - [❌ `some-rule-that-failed`](#-some-rule-that-failed)
  - [❌ `some-rule-that-failed-with-file-specifics`](#-some-rule-that-failed-with-file-specifics)
- [Warning](#warning)
  - [⚠️ `some-rule-that-just-annoys-developers`](#️-some-rule-that-just-annoys-developers)
- [Pass](#pass)
  - [✅ `readme-exists`](#-readme-exists)
  - [✅ `another-rule-that-failed-with-file-specifics`](#-another-rule-that-failed-with-file-specifics)

## Summary

This Repolinter run was triggered by a GitHub push. It generated the following results:
|✅ Pass| ❌ Fail | ⚠️ Warn | Total|
|---|---|---|---|
| 20 | 1 | 2 | 23 |


## Fail

### ❌ `some-rule-that-failed`
A file matching the following patterns was not found: `LICENSE*`, `COPYING*`. We require that all repositories have the MIT license unless direction is received otherwise. For more information please visit www.example.com/morepolicyinfo.

ℹ️ **Suggested Fix**: Create file with with contents from www.example.com (`LICENSE`).

### ❌ `some-rule-that-failed-with-file-specifics`

All files in the repository must contain an Apache license header. For more information please visit www.example.com/morepolicyinfo. Below is a list of files that failed:
* `tests/axioms/packagers_tests.js`: The first five lines of this file do not contain the apache license header.
  * ℹ️ **Suggested Fix**: Add apache license header to file.
* `tests/axioms/other_tests.js`: The first five lines of this file do not contain the apache license header.
  * ℹ️ **Suggested Fix**: Add apache license header to file.

## Warning

<details>
<summary>Click to see passed rules</summary>

### ⚠️ `some-rule-that-just-annoys-developers`

The default branch on this repository is named `master`. We suggest you switch away from master/slave terminology as detailed in the New Relic Open Source handbook. More information can be found here: www.example.com/morepolicyinfo

</details>

## Pass
<details>
  <summary>Click to see passed rules</summary>

### ✅ `readme-exists`

A file matching the pattern `README*` was found (`README.md`). We require all projects to have some form of front facing documentation.

### ✅ `another-rule-that-failed-with-file-specifics`

All files in the repository must contain an Apache license header. For more information please visit www.example.com/morepolicyinfo. Below is a list of files that failed:
* `tests/axioms/packagers_tests.js`: The first five lines of this file do not contain the apache license header.
* `tests/axioms/other_tests.js`: The first five lines of this file do not contain the apache license header.

</details>
