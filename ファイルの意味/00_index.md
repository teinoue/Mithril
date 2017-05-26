# Mithrilのファイルの意味

mithril.js-next/  
	├ api/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-mount.js  
	│ │  ├ test-redraw.js  
	│ │  └ test-router.js  
	│ ├ mount.js  
	│ ├ redraw.js  
	│ └ router.js  
	│  
	├ [bundler/](ModuleBundler.md)  
	│ ├ bin/  
	│ │ ├ bundle  
	│ │ └ bundle.cmd  
	│ ├ tests/  
	│ │ └ test-bundler.js  
	│ ├ bundle.js  
	│ ├ cli.js  
	│ └ minify.js  
	├ docs/  
	│ ├ generate.js  
	│ └ lint.js  
	├ examples/  
	│ ├ animation/  
	│ │ ├ flowers.jpg  
	│ │ └ mosaic.html  
	│ ├ dbmonster/  
	│ │  ├ angular/  
	│ │  │  ├ app.js  
	│ │  │  └ index.html  
	│ │  ├ mithril/  
	│ │  │  ├ app.js  
	│ │  │  └ index.html  
	│ │  ├ react/  
	│ │  │  ├ app.js  
	│ │  │  └ index.html  
	│ │  ├ vue/  
	│ │  │  ├ app.js  
	│ │  │  └ index.html  
	│ │  ├ ENV.js  
	│ │  ├ memory-stats.js  
	│ │  ├ monitor.js  
	│ │  └ styles.css  
	│ ├ editor/  
	│ │  └ index.html  
	│ ├ svg/  
	│ │  ├ clock.html  
	│ │  ├ ring.html  
	│ │  └ tiger.html  
	│ ├ threaditjs/  
	│ │  ├ app.js  
	│ │  ├ colors.css  
	│ │  └ index.html  
	│ └ todomvc/  
	│    ├ app.css  
	│    ├ base.css  
	│    ├ index.html  
	│    └ todomvc.js  
	├ module/  
	│ ├ module.js  
	│ └ README.md  
	├ ospec/  
	│ ├ bin/  
	│ │ ├ ospec  
	│ │ └ ospec.cmd  
	│ └ tests/  
	│    ├ ospec  
	│   └ ospec.cmd  
	├ performance/  
	│ ├ index.html  
	│ └ test-perf.js  
	├ promise/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  └ test-promise.js  
	│ └ promise.js  
	├ querystring/  
	│ ├  tests/  
	│ │  ├ index.html  
	│ │  ├ test-buildQueryString.js  
	│ │  └ test-parseQueryString.js  
	│ ├ build.js  
	│ └ parse.js  
	├ render/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-attributes.js  
	│ │  ├ test-component.js  
	│ │  ├ test-buildQueryString.js  
	│ │  ├ test-createElement.js  
	│ │  ├ test-createFragment.js  
	│ │  ├ test-createHTML.js  
	│ │  ├ test-createNodes.js  
	│ │  ├ test-createText.js  
	│ │  ├ test-event.js  
	│ │  ├ test-fragment.js  
	│ │  ├ test-hyperscript.js  
	│ │  ├ test-input.js  
	│ │  ├ test-normalize.js  
	│ │  ├ test-normalizeChildren.js  
	│ │  ├ test-onbeforeremove.js  
	│ │  ├ test-onbeforeupdate.js  
	│ │  ├ test-oncreate.js  
	│ │  ├ test-oninit.js  
	│ │  ├ test-onremove.js  
	│ │  ├ test-onupdate.js  
	│ │  ├ test-render.js  
	│ │  ├ test-textContent.js  
	│ │  ├ test-trust.js  
	│ │  ├ test-updateElement.js  
	│ │  ├ test-updateFragment.js  
	│ │  ├ test-updateHTML.js  
	│ │  ├ test-updateNodes.js  
	│ │  └ test-updateText.js  
	│ └ promise.js  
	├ request/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-jsonp.js  
	│ │  └ test-request.js  
	│ └  request.js
	├ router/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-defineRoutes.js  
	│ │  ├ test-getPath.js  
	│ │  └ test-setPath.js  
	│ └ router.js  
	├ stream/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-scan.js  
	│ │  ├ test-scanMerge.js  
	│ │  └ test-stream.js  
	│ ├ package.json  
	│ └ stream.js  
	├ tests/  
	│ ├ index.html  
	│ └ test-api.js  
	├ test-utils/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  ├ test-browserMock.js  
	│ │  ├ test-callAsync.js  
	│ │  ├ test-components.js  
	│ │  ├ test-domMock.js  
	│ │  ├ test-parseURL.js  
	│ │  ├ test-pushStateMock.js  
	│ │  └ test-xhrMock.js  
	│ ├ browserMock.js  
	│ ├ callAsync.js  
	│ ├ components.js  
	│ ├ domMock.js  
	│ ├ parseURL.js  
	│ ├ pushStateMock.js  
	│ ├ README.md  
	│ └ xhrMock.js  
	├ util/  
	│ ├ tests/  
	│ │  ├ index.html  
	│ │  └ test-withAttr.js  
	│ └ withAttr.js  
	├ [.deploy.enc](deploy_enc.md)  
	├ [.editorconfig](editorconfig.md)  
	├ [.eslintignore](eslintignore.md)  
	├ [.eslintrc.js](eslintrc_js.md)  
	├ [.gitattributes](gitattributes.md)  
	├ [.gitignore](gitignore.md)  
	├ [.npmignore]()  
	├ [.travis.yml]()  
	├ [browser.js]()  
	├ [hyperscript.js]()  
	├ [index.js]()  
	├ [LICENSE]()  
	├ [mithril.js]()  
	├ [mithril.min.js]()  
	├ [mount.js]()  
	├ [package.json]()  
	├ [README.md]()  
	├ [redraw.js]()  
	├ [render.js]()  
	├ [request.js]()  
	├ [route.js]()  
	└ [stream.js]()  
