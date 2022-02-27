# hax_11ty - HAXcms micro-site
This is a HAXcms generated and managed micro-site. It can run on it's own but it was generated by a HAXcms system somewhere.

## Developer mode
HAXcms primary audience is people doing things entirely through the UI. It is however creating everything in a way that's very developer friendly though. This means you can peal this off from the original place it came from and run this as a stand alone repo by:

- leveraging the included package.json
- removing the symlinks to dist / node_modules / build
- copying the dist directory from the project root into your local setup: https://github.com/elmsln/haxcms/tree/master/dist

Using this approach you'll have to manage dependencies on your own but you'll be able to utilize custom themes / elements that you can to show up. If you do add any new elements or themes you'll need to ship this repo with the `polymer build` command executed in order to bundle / compile everything together for usage.

### special note
The CDN mirrors for HAXcms may or may not include the elements you wish to extend your project with so those options for rapid distributed publishing may not be availble.

# HAXcms
HAX CMS seeks to be the smallest possible back-end CMS to make HAX work and be able to build websites with it. Leveraging JSON Outline Schema, HAX is able to author multiple pages, which it then writes onto the file system.

## License
[Apache 2.0](LICENSE.md)
