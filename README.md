# easycache

* [Chrome Web Store](https://chromewebstore.google.com/detail/easycache/kcidaidcpfbkemhohngajephodacajbf)
* [.crx file](https://sigwait.org/~alex/demo/chrome/)

A browser extension (manifest v3) that serves an interface for web
archivers (Wayback Machine, archive.today). Supports adding custom
providers.

## Compilation

	$ npm i -g adieu
    $ sudo dnf install jq jsonnet
	$ make crx

The resulting .crx should appear in `_out` dir.

## License

MIT.
