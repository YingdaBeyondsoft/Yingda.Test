# CE-CSI-Test
C+E Content, Services and International team test repo for Open Publishing Service.  This test repo is private and internal to Microsoft.  Open Publishing Service repos can have public repos, which allows community contribution to documentation but this test will not allow public access...

Contact eric@microsoft.com for more information

# CE-CSI-Test
C+E Content, Services and International team test repo for Open Publishing Service.  This test repo is private and internal to Microsoft.  Open Publishing Service repos can have public repos, which allows community contribution to documentation but this test will not allow public access.

Contact olpechuk@microsoft.com for more information


======================================

This is a quick tutorial regarding Open Publishing.

Quick Start
-----------------------

Start contributing to Open Publishing docs using the following steps:

1. Clone the repo:
   ```
   https://github.com/Microsoft/openpublishing-docs.git
   ```

2. Edit the Markdown files using your favorite Markdown editor.
3. Commit and push your changes:
   ```
   git add -u
   git commit -m "update doc"
   git push
   ```

4. Wait for a moment and your changes will be automatically published to: https://ppe.msdn.microsoft.com/en-us/CSITestDocs/EM/README?branch=master

> If you don't have the permission to push to this repo, fork it to your own account and use pull request to submit your changes back.

Validation and Preview
----------------------

Before pushing your changes to remote, you can build and preview your doc in local to discover problems early:

1. To validate your changes, just run `msbuild` under the root of the repo.
2. To preview your changes:
   1. Run `msbuild /t:serve` under the root of the repo.
   2. Open `http://localhost:8080` in your browser.

