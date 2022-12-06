```
❯ npm run build

> next-fail-output-standalone-build-app-dir@0.1.0 build
> next build

warn  - You have enabled experimental feature (appDir) in next.config.js.
warn  - Experimental features are not covered by semver, and may cause unexpected or broken application behavior. Use at your own risk.
info  - Thank you for testing `appDir` please leave your feedback at https://nextjs.link/app-feedback

info  - Creating an optimized production build
info  - Compiled successfully
info  - Linting and checking validity of types
warn  - Failed to copy traced files for /Users/ludusrusso/develop/github.com/ludusrusso/next-fail-output-standalone-build-app-dir/.next/server/app/test/page.js [Error: ENOENT: no such file or directory, open '/Users/ludusrusso/develop/github.com/ludusrusso/next-fail-output-standalone-build-app-dir/.next/server/app/test/page.js.nft.json'] {
  errno: -2,
  code: 'ENOENT',
  syscall: 'open',
  path: '/Users/ludusrusso/develop/github.com/ludusrusso/next-fail-output-standalone-build-app-dir/.next/server/app/test/page.js.nft.json'
}
info  - Collecting page data
info  - Generating static pages (4/4)
info  - Finalizing page optimization

Route (app)                                Size     First Load JS
┌ ○ /                                      0 B                0 B
└ ○ /test                                  0 B                0 B
+ First Load JS shared by all              65.9 kB
  ├ chunks/17-f297d0969951135e.js          64.1 kB
  ├ chunks/main-app-af873159cf3615af.js    200 B
  └ chunks/webpack-8074fabf81ca3fbd.js     1.61 kB

Route (pages)                              Size     First Load JS
─ ○ /404                                   179 B          80.7 kB
+ First Load JS shared by all              80.5 kB
  ├ chunks/main-d3ce11cbe6c7b908.js        78.7 kB
  ├ chunks/pages/_app-5841ab2cb3aa228d.js  192 B
  └ chunks/webpack-8074fabf81ca3fbd.js     1.61 kB

○  (Static)  automatically rendered as static HTML (uses no initial props)
```
