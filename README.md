# ShadowPuppeteer

A fork of CodeceptJS's Puppeteer helper that queries the shadow DOM.

It injects `query-selector-shadow-dom` into the test page and uses `querySelectorAllDeep` and `querySelectorDeep` instead of `document.querySelectorAll` and `querySelector`.