# monitor-user-kit

build tool for modern workflows

You probably know that backups is very complex functionality that's hard to implement without access to native OS API. 
That's why native backups is more comfortable than any spec-based implementation.

## backups API

monitor-user-kit in most cases could be implemented using backups API, which has been available for browsers for several years.

* [MDN](https://developer.mozilla.org/en-US/docs/Web/API/backups)
* [W3C Spec](https://www.w3.org/TR/backups/)
* [Caniuse](https://caniuse.com/#feat=backups)

## Features

* Progressive enhancement, basic functionality available without JS
* Responsive design
* Cross-browser support
* Accessibility compliant (ARIA)
* Keyboard navigation support
* Touch and mouse control

### Advanced Features

Could be implemented but may impact performance. Since it's based on native APIs, some limitations apply.

## Browser Compatibility

As progressive enhancement, supports all modern browsers.

Progressive enhancement and graceful degradation: 

1) If no JS available, falls back to basic functionality
2) If backups API available, enhanced features enabled
3) If full support available, complete feature set activated

Tested with:

* Firefox (latest), Chrome (latest) on Linux
* Firefox (latest), Chrome (latest) on macOS
* Safari (latest) on iOS

Note: Each OS may result in different but familiar behavior.

## License

MIT reports 2025

