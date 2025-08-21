---
mode: "agent"
tools: ['codebase', 'extensions', 'fetch', 'findTestFiles', 'githubRepo', 'problems', 'search', 'searchResults', 'testFailure', 'usages']
description: "Generate routes summary"
---

Please provide me with a summary of where the HTTP
routes are defined in this code base. Please print them out in a format
similar to how rake routes would display them with the following collumns:

VERB | URI | FILE | LINE NUMBERS

Example:

GET | / | app.js | 10-20

