# Patch Viewer

Single file, browser based side-by-side patch viewer.

Try it online: https://captureage.github.io/PatchViewer/PatchViewer.html

Just save the `PatchViewer.html` to use it offline. No any other dependencies or internet access needed.

Screenshot:

![image](https://github.com/megatops/PatchViewer/assets/13481083/7154076b-4561-45ff-a286-4323576d85d8)

## Release History

**v0.6.1-ca-0.1**

- Add support for P4 files and add lazy loading for displaying diffs (handles large diffs without running out of memory).

**v0.6.1**

- Fixed a regression bug when parsing diff with only 1 line changed.

**v0.6**

- Better support for `git format-patch` patches.

**v0.5**

- Resolved the issue when parsing `git diff` which contains `\ No newline at end of file`;
- Fix for easy selection of multiple lines (by Sajal Gautam).

**v0.4**

- Support file list and file navigator;
- Open source.

**v0.3**

- Bug fixes;
- First public release.

**v0.2**

- Support unified diff.

**v0.1**

- Initial release, support context diff.

