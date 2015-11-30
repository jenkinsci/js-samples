# Step 05 - "Namespaced" CSS
In this plugin (`step-05-namespaced-css`), we modify <a href="../../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a>
a little so as to [use the default "namespaced" CSS for Twitter Bootstrap](https://github.com/jenkinsci/js-libs/tree/master/bootstrap#css-namespacing).

<p>
<ol>
    <li><a href="#how-to-run">How to run</a><br/>
    <li><a href="HOW-IT-WORKS.md">How it works</a><br/>
</ol>    
</p>

## How to run
The easiest way to run this Jenkins plugin is to [use the standard Maven HPI plugin for Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/Plugin+tutorial#Plugintutorial-DebuggingaPlugin).

```sh
$ mvn hpi:run
```

Again, nothing visual changes from <a href="../../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a> to this plugin.
The only difference is in <a href="HOW-IT-WORKS.md">how it works</a>, specifically in how the default namespaced CSS is auto-loaded and used.

## How it works

<a href="HOW-IT-WORKS.md"><img src="../img/how-it-works.png" /></a>

<hr/>
<p align="center">
<b><a href="../../../tree/master/step-04-externalize-libs">&lt;&lt; PREV (step-04-externalize-libs) &lt;&lt;</a></b>
</p>

[Node.js]: https://nodejs.org
[Gulp]: https://github.com/gulpjs/gulp
[jenkins-js-builder]: https://github.com/jenkinsci/js-builder
[jenkins-js-modules]: https://github.com/jenkinsci/js-modules
[jenkins-js-libs]: https://github.com/jenkinsci/js-libs
[CommonJS]: http://www.commonjs.org/
[jquery-detached]: https://github.com/tfennelly/jquery-detached
[bootstrap-detached]: https://github.com/tfennelly/bootstrap-detached
[Browserify]: http://browserify.org/
[bundle]: https://github.com/jenkinsci/js-modules/blob/master/FAQs.md#what-is-the-difference-between-a-module-and-a-bundle
