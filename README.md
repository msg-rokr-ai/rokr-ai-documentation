<h1 align="center">
  <br>
  ROKR AI Technical Research
  <br>
</h1>

### Prerequisites

- Have `Node.js` installed (>= v20.11.0)

### Setup

- Install `npm i docsify-cli -g`

- To preview the site locally, run `docsify serve docs`

### Guidelines

- When adding your files, create a separate .md file in the documents section and make sure to reference it in the \_sidebar.md file, under the appropriate topic (or create one if it no topic matches the subject of the research).

e.g.

```_sidebar.md

* [Home](/)

- <topic-name>

    - [<your-research-document-name>](documents/<your-research-document>.md)

- Help
  ...
```

- When adding headings of type 1 (#) and 2 (##), the content will be showed on the sidebar unless you include, on the same line, the following command: `<!-- {docsify-ignore} -->`

### Quick References

[Docsify Documentation](https://docsify.js.org/#/)

[Additional Docsify Plugins](https://docsify.js.org/#/awesome?id=plugins)
