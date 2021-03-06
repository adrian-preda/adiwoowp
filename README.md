# adiwoowp

wordpress woocommerce theme

Thank you for choosing adiwoowp! Whether you’re a small business owner or a developer creating websites for clients, we’re hoping the theme will help you reach your goals. You must be excited about starting your new project, so let's just get on with it.

### Version
1.0

### Tech

adiwoowp uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [Marked] - a super fast port of Markdown to JavaScript
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [keymaster.js] - awesome keyboard handler lib by [@thomasfuchs]
* [jQuery] - duh

And of course adiwoowp itself is open source with a [public repository][adiwoowp]
 on GitHub.

### Installation

You need Gulp installed globally:

```sh
$ npm i -g gulp
```

```sh
$ git clone [git-repo-url] adiwoowp
$ cd adiwoowp
$ npm i -d
$ mkdir -p downloads/files/{md,html,pdf}
$ gulp build --prod
$ NODE_ENV=production node app
```

### Plugins

adiwoowp is currently extended with the following plugins

* Dropbox
* Github
* Google Drive
* OneDrive
* Subsidy

### Development

Want to contribute? Great!

adiwoowp uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma start
```

### Todos

 - Write Tests
 - Rethink Github Save
 - Add Code Comments
 - Add Night Mode