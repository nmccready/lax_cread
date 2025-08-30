# lax_cread

Website is built with hugo and is automatically deployed with [GitHub Actions](.github/workflows/hugo.yaml).


## Upgrading Hugo

To upgrade Hugo, change the version in the workflow file [.github/workflows/hugo.yaml](.github/workflows/hugo.yaml). Along with
whatever updates to the actions. Also newer versions of Hugo may require updates to the theme and folder structuring.

## Developing locally
To run the site locally, you need to have [Hugo](https://gohugo.io/getting-started/installing/) installed. 

Then you can run:

```bash
hugo server
```
This will start a local server at `http://localhost:1313` where you can see the site.
You can stop the server with `Ctrl+C`.
The site will automatically reload when you make changes to the files.
You can also build the site locally with:

```bash
hugo
```
This will generate the static files in the `public` directory.
You can then serve the files in the `public` directory with any static file server.
For example, you can use Python's built-in HTTP server:


