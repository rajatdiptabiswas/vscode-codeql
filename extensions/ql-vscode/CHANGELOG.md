# CodeQL for Visual Studio Code: Changelog

## 1.1.2 - 28 April 2020

- Implement syntax highlighting for the new `unique` aggregate.
- Implement XML syntax highlighting for `.qhelp` files.
- Add option to auto save queries before running them.
- Add new command in query history to view the query text of the
  selected query (note that this may be different from the current
  contents of the query file if the file has been edited).
- Add ability to sort CodeQL databases by name or by date added.

## 1.1.1 - 23 March 2020

- Fix quick evaluation in `.qll` files.
- Add new command in query history view to view the log file of a
  query.
- Request user acknowledgment before updating the CodeQL binaries.
- Warn when using the deprecated `codeql.cmd` launcher on Windows.

## 1.1.0 - 17 March 2020

- Add functionality for testing custom CodeQL queries by using the VS
  Code Test Explorer extension and `codeql test`. See the documentation for
  more details.
- Add a "Show log" button to all information, error, and warning
  popups that will display the CodeQL extension log.
- Display a message when a query times out.
- Show canceled queries in query history.
- Improve error messages when attempting to run non-query files.

## 1.0.6 - 28 February 2020

- Add command to restart query server.
- Enable support for future minor upgrades to the CodeQL CLI.

## 1.0.5 - 13 February 2020

- Add an icon next to any failed query runs in the query history
  view.
- Add the ability to sort alerts by alert message.

## 1.0.4 - 24 January 2020

- Disable word-based autocomplete by default.
- Add command `CodeQL: Quick Query` for easy query creation without
  having to choose a place in the filesystem to store the query file.

## 1.0.3 - 13 January 2020

- Reduce the frequency of CodeQL CLI update checks to help avoid hitting GitHub API limits of 60 requests per
hour for unauthenticated IPs.
- Fix sorting of result sets with names containing special characters.

## 1.0.2 - 13 December 2019

- Fix rendering of negative numbers in results.
- Allow customization of query history labels from settings and from
  query history view context menu.
- Show number of results in results view.
- Add commands `CodeQL: Show Next Step on Path` and `CodeQL: Show
  Previous Step on Path` for navigating the steps on the currently
  shown path result.

## 1.0.1 - 21 November 2019

- Change `codeQL.cli.executablePath` to a per-machine setting, so it can no longer be set at the user or workspace level. This helps prevent arbitrary code execution when using a VS Code workspace from an untrusted source.
- Improve the highlighting of the selected query result within the source code.
- Improve the performance of switching between result tables in the CodeQL Query Results view.
- Fix the automatic upgrading of CodeQL databases when using upgrade scripts from the workspace.
- Allow removal of items from the CodeQL Query History view.

## 1.0.0 - 14 November 2019

Initial release of CodeQL for Visual Studio Code.
