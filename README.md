## helloworld-webpart

### Sharepoint Development Documentation
[SharePoint_Doc](https://docs.microsoft.com/en-us/sharepoint/dev/)

### Sharepoint Setup
[SetUp](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-development-environment)
- node
- npm
- yeoman
- gulp
- @microsoft/generator-sharepoint

```bash
npm install -g yo gulp
npm install -g @microsoft/generator-sharepoint
```

### Create new WebPart project
[Create_Project](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part) 

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO

gulp test - TODO

gulp serve - TODO (npm run dev)
```bash
"dev": "set NODE_NO_HTTP2=1&& gulp serve",
```

gulp bundle - TODO

gulp package-solution - TODO
