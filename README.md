# RTS Helpdesk: Client Quickstart Guide

Client quickstart guide for RTS's current helpdesk application.

## Running Locally

`bundle exec jeyll server`

## Markdown Style Guide

The following rules should be followed when creating new markdown documents.

- Include the trailing `/` in all links
- Ensure all examples of issues are not specific to a single system because users from any system will be using this guide (e.g. "Unable to import data" instead of "Unable to import an NROL report")
- Avoid referring to deploying to production because some clients (e.g. NR will SSoWPS) handle the deployment to production so we don't want to have tickets left open while we wait for them to carry out the deployment that could be weeks/months.

## Notes

Just some general notes.

- **Open markdown links in a new tab**

  ```HTML
  [link name](url_link){:target="_blank"}
  ```
