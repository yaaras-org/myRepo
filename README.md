[![workerB](https://img.shields.io/endpoint?url=https%3A%2F%2Fworkerb.linearb.io%2Fv2%2Fbadge%2Fprivate%2FU2FsdGVkX18LJrj0RtObbkh7QxlchxkiABzOYRStkog%2Fcollaboration.svg%3FcacheSeconds%3D60)](https://workerb.linearb.io/v2/badge/collaboration-page?magicLinkId=8biy-A6)
[![workerB](https://img.shields.io/endpoint?url=https%3A%2F%2Fworkerb.linearb.io%2Fv2%2Fbadge%2Fprivate%2FU2FsdGVkX19h6r90AiFVzMU9qiCgpjduPvkGr2EW4o%2Fcollaboration.svg%3FcacheSeconds%3D60)](https://workerb.linearb.io/v2/badge/collaboration-page?magicLinkId=a_JzDgz)
[![workerB](https://img.shields.io/endpoint?url=https%3A%2F%2Fworkerb.linearb.io%2Fv2%2Fbadge%2Fprivate%2FU2FsdGVkX18QOJLLBP8tuMEEDrSniIP3MJbsRxh5MaU%2Fcollaboration.svg%3FcacheSeconds%3D60)](https://workerb.linearb.io/v2/badge/collaboration-page?magicLinkId=Q_qKzEL)
[![Mend Renovate](https://app.renovatebot.com/images/banner.svg)](https://renovatebot.com)

This PR contains the following updates:

| Package | Type | Update | Change | Age | Adoption | Passing | Confidence |
|---|---|---|---|---|---|---|---|
| [node](https://togithub.com/nodejs/node) |  | major | `16.19.0` -> `18.14.0` | [![age](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/age-slim)](https://docs.renovatebot.com/merge-confidence/) | [![adoption](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/adoption-slim)](https://docs.renovatebot.com/merge-confidence/) | [![passing](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/compatibility-slim/16.19.0)](https://docs.renovatebot.com/merge-confidence/) | [![confidence](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/confidence-slim/16.19.0)](https://docs.renovatebot.com/merge-confidence/) |
| [node](https://togithub.com/nodejs/node) | engines | major | [`^16.0.0` -> `^18.0.0`](https://renovatebot.com/diffs/npm/node/v16.19.0/v18.14.0) | [![age](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/age-slim)](https://docs.renovatebot.com/merge-confidence/) | [![adoption](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/adoption-slim)](https://docs.renovatebot.com/merge-confidence/) | [![passing](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/compatibility-slim/v16.19.0)](https://docs.renovatebot.com/merge-confidence/) | [![confidence](https://badges.renovateapi.com/packages/github-tags/node/v18.14.0/confidence-slim/v16.19.0)](https://docs.renovatebot.com/merge-confidence/) |
| [@types/node](https://togithub.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/node) ([source](https://togithub.com/DefinitelyTyped/DefinitelyTyped)) | devDependencies | major | [`16.18.12` -> `18.13.0`](https://renovatebot.com/diffs/npm/@types%2fnode/16.18.12/18.13.0) | [![age](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/age-slim)](https://docs.renovatebot.com/merge-confidence/) | [![adoption](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/adoption-slim)](https://docs.renovatebot.com/merge-confidence/) | [![passing](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/compatibility-slim/16.18.12)](https://docs.renovatebot.com/merge-confidence/) | [![confidence](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/confidence-slim/16.18.12)](https://docs.renovatebot.com/merge-confidence/) |
| [@types/node](https://togithub.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/node) ([source](https://togithub.com/DefinitelyTyped/DefinitelyTyped)) | devDependencies | major | [`17.0.7` -> `18.13.0`](https://renovatebot.com/diffs/npm/@types%2fnode/17.0.7/18.13.0) | [![age](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/age-slim)](https://docs.renovatebot.com/merge-confidence/) | [![adoption](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/adoption-slim)](https://docs.renovatebot.com/merge-confidence/) | [![passing](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/compatibility-slim/17.0.7)](https://docs.renovatebot.com/merge-confidence/) | [![confidence](https://badges.renovateapi.com/packages/npm/@types%2fnode/18.13.0/confidence-slim/17.0.7)](https://docs.renovatebot.com/merge-confidence/) |

---

### Release Notes

<details>
<summary>nodejs/node</summary>

### [`v18.14.0`](https://togithub.com/nodejs/node/releases/tag/v18.14.0): 2023-02-02, Version 18.14.0 &#x27;Hydrogen&#x27; (LTS), @&#8203;BethGriggs prepared by @&#8203;juanarbol

[Compare Source](https://togithub.com/nodejs/node/compare/v18.13.0...v18.14.0)

##### Notable changes

##### Updated npm to 9.3.1

Based on the [list of guidelines we've established on integrating `npm` and `node`](https://togithub.com/npm/cli/wiki/Integrating-with-node),
here is a grouped list of the breaking changes with the reasoning as to why they
fit within the guidelines linked above. Note that all the breaking changes were
made in [9.0.0](https://togithub.com/npm/cli/releases/tag/v9.0.0).
All subsequent minor and patch releases after `npm@9.0.0` do not contain any
breaking changes.

##### Engines

> Explanation: the node engines supported by `npm@9` make it safe to allow `npm@9` as the default in any LTS version of `14` or `16`, as well as anything later than or including `18.0.0`

-   `npm` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

##### Filesystem

> Explanation: when run as root previous versions of npm attempted to manage file ownership automatically on the user's behalf. this behavior was problematic in many cases and has been removed in favor of allowing users to manage their own filesystem permissions

-   `npm` will no longer attempt to modify ownership of files it creates.

##### Auth

> Explanation: any errors thrown from users having unsupported auth configurations will show `npm config fix` in the remediation instructions, which will allow the user to automatically have their auth config fixed.

-   The presence of auth related settings that are not scoped to a specific
    registry found in a config file is no longer supported and will throw errors.

##### Login

> Explanation: the default `auth-type` has changed and users can opt back into the old behavior with `npm config set auth-type=legacy`. `login` and `adduser` have also been seperated making each command more closely match it's name instead of being aliases for each other.

-   Legacy auth types `sso`, `saml` & `legacy` have been consolidated into `"legacy"`.
-   `auth-type` defaults to `"web"`
-   `login` and `adduser` are now separate commands that send different data to the registry.
-   `auth-type` config values `web` and `legacy` only try their respective methods,
    npm no longer tries them all and waits to see which one doesn't fail.

##### Tarball Packing

> Explanation: previously using multiple ignore/allow lists when packing was an undefined behavior, and now the order of operations is strictly defined when packing a tarball making it easier to follow and should only affect users relying on the previously undefined behavior.

-   `npm pack` now follows a strict order of operations when applying ignore rules.
    If a `files` array is present in the `package.json`, then rules in `.gitignore`
    and `.npmignore` files from the root will be ignored.

##### Display/Debug/Timing Info

> Explanation: these changes center around the display of information to the terminal including timing and debug log info. We do not anticipate these changes breaking any existing workflows.

-   Links generated from git urls will now use `HEAD` instead of `master` as the default ref.
-   `timing` has been removed as a value for `--loglevel`.
-   `--timing` will show timing information regardless of `--loglevel`, except when `--silent`.
-   When run with the `--timing` flag, `npm` now writes timing data to a file
    alongside the debug log data, respecting the `logs-dir` option and falling
    back to `<CACHE>/_logs/` dir, instead of directly inside the cache directory.
-   The timing file data is no longer newline delimited JSON, and instead each run
    will create a uniquely named `<ID>-timing.json` file, with the `<ID>` portion
    being the same as the debug log.
-   `npm` now outputs some json errors on stdout. Previously `npm` would output
    all json formatted errors on stderr, making it difficult to parse as the
    stderr stream usually has logs already written to it.

##### Config/Command Deprecations or Removals

> Explanation: `install-links` is the only config or command in the list that has an effect on package installs. We fixed a number of issues that came up during prereleases with this change. It will also only be applied to new package trees created without a package-lock.json file. Any install with an existing lock file will not be changed.

-   Deprecate boolean install flags in favor of `--install-strategy`.
-   `npm config set` will no longer accept deprecated or invalid config options.
-   `install-links` config defaults to `"true"`.
-   `node-version` config has been removed.
-   `npm-version` config has been removed.
-   `npm access` subcommands have been renamed.
-   `npm birthday` has been removed.
-   `npm set-script` has been removed.
-   `npm bin` has been removed (use `npx` or `npm exec` to execute binaries).

##### Other notable changes

-   **doc**:
    -   add parallelism note to os.cpus() (Colin Ihrig) [#&#8203;45895](https://togithub.com/nodejs/node/pull/45895)
-   **http**:
    -   join authorization headers (Marco Ippolito) [#&#8203;45982](https://togithub.com/nodejs/node/pull/45982)
    -   improved timeout defaults handling (Paolo Insogna) [#&#8203;45778](https://togithub.com/nodejs/node/pull/45778)
-   **stream**:
    -   implement finished() for ReadableStream and WritableStream (Debadree Chatterjee) [#&#8203;46205](https://togithub.com/nodejs/node/pull/46205)

##### Commits

-   \[[`1352f08778`](https://togithub.com/nodejs/node/commit/1352f08778)] - **assert**: remove `assert.snapshot` (Moshe Atlow) [#&#8203;46112](https://togithub.com/nodejs/node/pull/46112)
-   \[[`4ee3238643`](https://togithub.com/nodejs/node/commit/4ee3238643)] - **async_hooks**: refactor to use `validateObject` (Deokjin Kim) [#&#8203;46004](https://togithub.com/nodejs/node/pull/46004)
-   \[[`79e0bf9b64`](https://togithub.com/nodejs/node/commit/79e0bf9b64)] - **benchmark**: include webstreams benchmark (Rafael Gonzaga) [#&#8203;45876](https://togithub.com/nodejs/node/pull/45876)
-   \[[`ed1ac82469`](https://togithub.com/nodejs/node/commit/ed1ac82469)] - **benchmark,tools**: use os.availableParallelism() (Deokjin Kim) [#&#8203;46003](https://togithub.com/nodejs/node/pull/46003)
-   \[[`16ee02f2eb`](https://togithub.com/nodejs/node/commit/16ee02f2eb)] - **(SEMVER-MINOR)** **buffer**: add buffer.isUtf8 for utf8 validation (Yagiz Nizipli) [#&#8203;45947](https://togithub.com/nodejs/node/pull/45947)
-   \[[`3bf2371a57`](https://togithub.com/nodejs/node/commit/3bf2371a57)] - **build**: add extra semi check (Jiawen Geng) [#&#8203;46194](https://togithub.com/nodejs/node/pull/46194)
-   \[[`560ee24157`](https://togithub.com/nodejs/node/commit/560ee24157)] - **build**: fix arm64 cross-compile from powershell (Stefan Stojanovic) [#&#8203;45890](https://togithub.com/nodejs/node/pull/45890)
-   \[[`48e3ad3aca`](https://togithub.com/nodejs/node/commit/48e3ad3aca)] - **build**: add option to disable shared readonly heap (Anna Henningsen) [#&#8203;45887](https://togithub.com/nodejs/node/pull/45887)
-   \[[`52a7887b94`](https://togithub.com/nodejs/node/commit/52a7887b94)] - **(SEMVER-MINOR)** **crypto**: add CryptoKey Symbol.toStringTag (Filip Skokan) [#&#8203;46042](https://togithub.com/nodejs/node/pull/46042)
-   \[[`a558774a40`](https://togithub.com/nodejs/node/commit/a558774a40)] - **crypto**: add cipher update/final methods encoding validation (vitpavlenko) [#&#8203;45990](https://togithub.com/nodejs/node/pull/45990)
-   \[[`599d1dc841`](https://togithub.com/nodejs/node/commit/599d1dc841)] - **crypto**: ensure auth tag set for chacha20-poly1305 (Ben Noordhuis) [#&#8203;46185](https://togithub.com/nodejs/node/pull/46185)
-   \[[`24a101698c`](https://togithub.com/nodejs/node/commit/24a101698c)] - **crypto**: return correct bit length in KeyObject's asymmetricKeyDetails (Filip Skokan) [#&#8203;46106](https://togithub.com/nodejs/node/pull/46106)
-   \[[`2de50fef84`](https://togithub.com/nodejs/node/commit/2de50fef84)] - **(SEMVER-MINOR)** **crypto**: add KeyObject Symbol.toStringTag (Filip Skokan) [#&#8203;46043](https://togithub.com/nodejs/node/pull/46043)
-   \[[`782b6f6f9f`](https://togithub.com/nodejs/node/commit/782b6f6f9f)] - **crypto**: ensure exported webcrypto EC keys use uncompressed point format (Ben Noordhuis) [#&#8203;46021](https://togithub.com/nodejs/node/pull/46021)
-   \[[`7a97f3f43b`](https://togithub.com/nodejs/node/commit/7a97f3f43b)] - **crypto**: fix CryptoKey prototype WPT (Filip Skokan) [#&#8203;45857](https://togithub.com/nodejs/node/pull/45857)
-   \[[`1a8aa50aa2`](https://togithub.com/nodejs/node/commit/1a8aa50aa2)] - **crypto**: fix CryptoKey WebIDL conformance (Filip Skokan) [#&#8203;45855](https://togithub.com/nodejs/node/pull/45855)
-   \[[`c6436450ee`](https://togithub.com/nodejs/node/commit/c6436450ee)] - **crypto**: fix error when getRandomValues is called without arguments (Filip Skokan) [#&#8203;45854](https://togithub.com/nodejs/node/pull/45854)
-   \[[`4cdf0002c5`](https://togithub.com/nodejs/node/commit/4cdf0002c5)] - **debugger**: refactor console in lib/internal/debugger/inspect.js (Debadree Chatterjee) [#&#8203;45847](https://togithub.com/nodejs/node/pull/45847)
-   \[[`b7fe8c70fa`](https://togithub.com/nodejs/node/commit/b7fe8c70fa)] - **deps**: update simdutf to 3.1.0 (Node.js GitHub Bot) [#&#8203;46257](https://togithub.com/nodejs/node/pull/46257)
-   \[[`eaeb870cd7`](https://togithub.com/nodejs/node/commit/eaeb870cd7)] - **deps**: upgrade npm to 9.3.1 (npm team) [#&#8203;46242](https://togithub.com/nodejs/node/pull/46242)
-   \[[`7c03a3d676`](https://togithub.com/nodejs/node/commit/7c03a3d676)] - **deps**: upgrade npm to 9.3.0 (npm team) [#&#8203;46193](https://togithub.com/nodejs/node/pull/46193)
-   \[[`340d76accb`](https://togithub.com/nodejs/node/commit/340d76accb)] - **deps**: cherrypick simdutf patch (Jiawen Geng) [#&#8203;46194](https://togithub.com/nodejs/node/pull/46194)
-   \[[`cce2af4306`](https://togithub.com/nodejs/node/commit/cce2af4306)] - **deps**: bump googletest to 2023.01.13 (Jiawen Geng) [#&#8203;46198](https://togithub.com/nodejs/node/pull/46198)
-   \[[`d251a66bed`](https://togithub.com/nodejs/node/commit/d251a66bed)] - **deps**: add /deps/\*\*/.github/ to .gitignore (Luigi Pinca) [#&#8203;46091](https://togithub.com/nodejs/node/pull/46091)
-   \[[`874054f469`](https://togithub.com/nodejs/node/commit/874054f469)] - **deps**: add simdutf version to metadata (Mike Roth) [#&#8203;46145](https://togithub.com/nodejs/node/pull/46145)
-   \[[`2497702b82`](https://togithub.com/nodejs/node/commit/2497702b82)] - **deps**: update simdutf to 2.1.0 (Node.js GitHub Bot) [#&#8203;46128](https://togithub.com/nodejs/node/pull/46128)
-   \[[`c8492b7f4c`](https://togithub.com/nodejs/node/commit/c8492b7f4c)] - **deps**: update corepack to 0.15.3 (Node.js GitHub Bot) [#&#8203;46037](https://togithub.com/nodejs/node/pull/46037)
-   \[[`d148f357fd`](https://togithub.com/nodejs/node/commit/d148f357fd)] - **deps**: update simdutf to 2.0.9 (Node.js GitHub Bot) [#&#8203;45975](https://togithub.com/nodejs/node/pull/45975)
-   \[[`422a98199c`](https://togithub.com/nodejs/node/commit/422a98199c)] - **deps**: update to uvwasi 0.0.14 (Colin Ihrig) [#&#8203;45970](https://togithub.com/nodejs/node/pull/45970)
-   \[[`7812752db0`](https://togithub.com/nodejs/node/commit/7812752db0)] - **deps**: fix updater github workflow job (Yagiz Nizipli) [#&#8203;45972](https://togithub.com/nodejs/node/pull/45972)
-   \[[`4063cdcef6`](https://togithub.com/nodejs/node/commit/4063cdcef6)] - ***Revert*** "**deps**: disable avx512 for simutf on benchmark ci" (Yagiz Nizipli) [#&#8203;45948](https://togithub.com/nodejs/node/pull/45948)
-   \[[`64d3e3f3ba`](https://togithub.com/nodejs/node/commit/64d3e3f3ba)] - **deps**: disable avx512 for simutf on benchmark ci (Yagiz Nizipli) [#&#8203;45803](https://togithub.com/nodejs/node/pull/45803)
-   \[[`c9845fc334`](https://togithub.com/nodejs/node/commit/c9845fc334)] - **deps**: add simdutf dependency (Yagiz Nizipli) [#&#8203;45803](https://togithub.com/nodejs/node/pull/45803)
-   \[[`6963c96547`](https://togithub.com/nodejs/node/commit/6963c96547)] - **deps**: update timezone to 2022g (Node.js GitHub Bot) [#&#8203;45731](https://togithub.com/nodejs/node/pull/45731)
-   \[[`874f6c340b`](https://togithub.com/nodejs/node/commit/874f6c340b)] - **deps**: update undici to 5.14.0 (Node.js GitHub Bot) [#&#8203;45812](https://togithub.com/nodejs/node/pull/45812)
-   \[[`7599b913d5`](https://togithub.com/nodejs/node/commit/7599b913d5)] - **deps**: upgrade npm to 9.2.0 (npm team) [#&#8203;45780](https://togithub.com/nodejs/node/pull/45780)
-   \[[`4844935ff3`](https://togithub.com/nodejs/node/commit/4844935ff3)] - **deps**: upgrade npm to 9.1.3 (npm team) [#&#8203;45693](https://togithub.com/nodejs/node/pull/45693)
-   \[[`8dce62c7fe`](https://togithub.com/nodejs/node/commit/8dce62c7fe)] - **deps**: V8: cherry-pick [`5fe919f`](https://togithub.com/nodejs/node/commit/5fe919f78321) (Richard Lau) [#&#8203;45587](https://togithub.com/nodejs/node/pull/45587)
-   \[[`8de642517e`](https://togithub.com/nodejs/node/commit/8de642517e)] - **dgram**: sync the old handle state to new handle (theanarkh) [#&#8203;46041](https://togithub.com/nodejs/node/pull/46041)
-   \[[`de2b7a9640`](https://togithub.com/nodejs/node/commit/de2b7a9640)] - **doc**: fix mismatched arguments of `NodeEventTarget` (Deokjin Kim) [#&#8203;45678](https://togithub.com/nodejs/node/pull/45678)
-   \[[`6317502d10`](https://togithub.com/nodejs/node/commit/6317502d10)] - **doc**: update events API example to have runnable code (Deokjin Kim) [#&#8203;45760](https://togithub.com/nodejs/node/pull/45760)
-   \[[`a9db45eee1`](https://togithub.com/nodejs/node/commit/a9db45eee1)] - **doc**: add note to tls docs about secureContext availability (Tim Gerk) [#&#8203;46224](https://togithub.com/nodejs/node/pull/46224)
-   \[[`5294371063`](https://togithub.com/nodejs/node/commit/5294371063)] - **doc**: add text around collaborative expectations (Michael Dawson) [#&#8203;46121](https://togithub.com/nodejs/node/pull/46121)
-   \[[`be85d5a6eb`](https://togithub.com/nodejs/node/commit/be85d5a6eb)] - **doc**: update to match changed `--dns-result-order` default (Mordy Tikotzky) [#&#8203;46148](https://togithub.com/nodejs/node/pull/46148)
-   \[[`4f2d9ea6da`](https://togithub.com/nodejs/node/commit/4f2d9ea6da)] - **doc**: add Node-API media link (Kevin Eady) [#&#8203;46189](https://togithub.com/nodejs/node/pull/46189)
-   \[[`9bfd40466f`](https://togithub.com/nodejs/node/commit/9bfd40466f)] - **doc**: update http.setMaxIdleHTTPParsers arguments (Debadree Chatterjee) [#&#8203;46168](https://togithub.com/nodejs/node/pull/46168)
-   \[[`d7a8c076e1`](https://togithub.com/nodejs/node/commit/d7a8c076e1)] - **doc**: use "file system" instead of "filesystem" (Rich Trott) [#&#8203;46178](https://togithub.com/nodejs/node/pull/46178)
-   \[[`e54483cd2b`](https://togithub.com/nodejs/node/commit/e54483cd2b)] - **doc**: https update default request timeout (Marco Ippolito) [#&#8203;46184](https://togithub.com/nodejs/node/pull/46184)
-   \[[`335110b0fb`](https://togithub.com/nodejs/node/commit/335110b0fb)] - **doc**: make options of readableStream.pipeTo as optional (Deokjin Kim) [#&#8203;46180](https://togithub.com/nodejs/node/pull/46180)
-   \[[`ec34cad712`](https://togithub.com/nodejs/node/commit/ec34cad712)] - **doc**: add PerformanceObserver.supportedEntryTypes to doc (theanarkh) [#&#8203;45962](https://togithub.com/nodejs/node/pull/45962)
-   \[[`d0f905bd6f`](https://togithub.com/nodejs/node/commit/d0f905bd6f)] - **doc**: duplex and readable from uncaught execption warning (Marco Ippolito) [#&#8203;46135](https://togithub.com/nodejs/node/pull/46135)
-   \[[`512feaafa4`](https://togithub.com/nodejs/node/commit/512feaafa4)] - **doc**: remove outdated sections from `maintaining-v8` (Antoine du Hamel) [#&#8203;46137](https://togithub.com/nodejs/node/pull/46137)
-   \[[`849a3e2ce7`](https://togithub.com/nodejs/node/commit/849a3e2ce7)] - **doc**: fix (EC)DHE remark in TLS docs (Tobias Nießen) [#&#8203;46114](https://togithub.com/nodejs/node/pull/46114)
-   \[[`a3c9c1b4e6`](https://togithub.com/nodejs/node/commit/a3c9c1b4e6)] - **doc**: fix ERR_TLS_RENEGOTIATION_DISABLED text (Tobias Nießen) [#&#8203;46122](https://togithub.com/nodejs/node/pull/46122)
-   \[[`1834e94ebb`](https://togithub.com/nodejs/node/commit/1834e94ebb)] - **doc**: fix spelling in SECURITY.md (Vaishno Chaitanya) [#&#8203;46124](https://togithub.com/nodejs/node/pull/46124)
-   \[[`3968698af5`](https://togithub.com/nodejs/node/commit/3968698af5)] - **doc**: abort controller emits error in child process (Debadree Chatterjee) [#&#8203;46072](https://togithub.com/nodejs/node/pull/46072)
-   \[[`1ec14c2c61`](https://togithub.com/nodejs/node/commit/1ec14c2c61)] - **doc**: fix `event.cancelBubble` documentation (Deokjin Kim) [#&#8203;45986](https://togithub.com/nodejs/node/pull/45986)
-   \[[`5539977f80`](https://togithub.com/nodejs/node/commit/5539977f80)] - **doc**: add personal pronouns option (Filip Skokan) [#&#8203;46118](https://togithub.com/nodejs/node/pull/46118)
-   \[[`1fabef3a81`](https://togithub.com/nodejs/node/commit/1fabef3a81)] - **doc**: mention how to run ncu-ci citgm (Rafael Gonzaga) [#&#8203;46090](https://togithub.com/nodejs/node/pull/46090)
-   \[[`84dc65ab87`](https://togithub.com/nodejs/node/commit/84dc65ab87)] - **doc**: include updating release optional step (Rafael Gonzaga) [#&#8203;46089](https://togithub.com/nodejs/node/pull/46089)
-   \[[`76c7ea1e74`](https://togithub.com/nodejs/node/commit/76c7ea1e74)] - **doc**: describe argument of `Symbol.for` (Deokjin Kim) [#&#8203;46019](https://togithub.com/nodejs/node/pull/46019)
-   \[[`2307a74990`](https://togithub.com/nodejs/node/commit/2307a74990)] - **doc**: update isUtf8 description (Yagiz Nizipli) [#&#8203;45973](https://togithub.com/nodejs/node/pull/45973)
-   \[[`fa5b65ea24`](https://togithub.com/nodejs/node/commit/fa5b65ea24)] - **doc**: use console.error for error case in timers and tls (Deokjin Kim) [#&#8203;46002](https://togithub.com/nodejs/node/pull/46002)
-   \[[`29d509c100`](https://togithub.com/nodejs/node/commit/29d509c100)] - **doc**: fix wrong output of example in `url.protocol` (Deokjin Kim) [#&#8203;45954](https://togithub.com/nodejs/node/pull/45954)
-   \[[`61dbca2690`](https://togithub.com/nodejs/node/commit/61dbca2690)] - **doc**: use `os.availableParallelism()` in async_context and cluster (Deokjin Kim) [#&#8203;45979](https://togithub.com/nodejs/node/pull/45979)
-   \[[`86b2c8cea2`](https://togithub.com/nodejs/node/commit/86b2c8cea2)] - **doc**: make EventEmitterAsyncResource's `options` as optional (Deokjin Kim) [#&#8203;45985](https://togithub.com/nodejs/node/pull/45985)
-   \[[`335acf7748`](https://togithub.com/nodejs/node/commit/335acf7748)] - **doc**: replace single executable champion in strategic initiatives doc (Darshan Sen) [#&#8203;45956](https://togithub.com/nodejs/node/pull/45956)
-   \[[`aab35a9388`](https://togithub.com/nodejs/node/commit/aab35a9388)] - **doc**: update error message of example in repl (Deokjin Kim) [#&#8203;45920](https://togithub.com/nodejs/node/pull/45920)
-   \[[`53a94a95ff`](https://togithub.com/nodejs/node/commit/53a94a95ff)] - **doc**: fix typos in packages.md (Eric Mutta) [#&#8203;45957](https://togithub.com/nodejs/node/pull/45957)
-   \[[`83875f46cf`](https://togithub.com/nodejs/node/commit/83875f46cf)] - **doc**: remove port from example in `url.hostname` (Deokjin Kim) [#&#8203;45927](https://togithub.com/nodejs/node/pull/45927)
-   \[[`162d3a94e3`](https://togithub.com/nodejs/node/commit/162d3a94e3)] - **doc**: show output of example in http (Deokjin Kim) [#&#8203;45915](https://togithub.com/nodejs/node/pull/45915)
-   \[[`53684e4506`](https://togithub.com/nodejs/node/commit/53684e4506)] - **(SEMVER-MINOR)** **doc**: add parallelism note to os.cpus() (Colin Ihrig) [#&#8203;45895](https://togithub.com/nodejs/node/pull/45895)
-   \[[`546e083d36`](https://togithub.com/nodejs/node/commit/546e083d36)] - **doc**: fix wrong output of example in `url.password` (Deokjin Kim) [#&#8203;45928](https://togithub.com/nodejs/node/pull/45928)
-   \[[`14c95ecd23`](https://togithub.com/nodejs/node/commit/14c95ecd23)] - **doc**: fix some history entries in `deprecations.md` (Antoine du Hamel) [#&#8203;45891](https://togithub.com/nodejs/node/pull/45891)
-   \[[`d94dba973b`](https://togithub.com/nodejs/node/commit/d94dba973b)] - **doc**: add tip for NODE_MODULE (theanarkh) [#&#8203;45797](https://togithub.com/nodejs/node/pull/45797)
-   \[[`662f574c5b`](https://togithub.com/nodejs/node/commit/662f574c5b)] - **doc**: reduce likelihood of mismerges during release (Richard Lau) [#&#8203;45864](https://togithub.com/nodejs/node/pull/45864)
-   \[[`48ea28aa30`](https://togithub.com/nodejs/node/commit/48ea28aa30)] - **doc**: add backticks to webcrypto rsaOaepParams (Filip Skokan) [#&#8203;45883](https://togithub.com/nodejs/node/pull/45883)
-   \[[`726b285163`](https://togithub.com/nodejs/node/commit/726b285163)] - **doc**: remove release cleanup step (Michaël Zasso) [#&#8203;45858](https://togithub.com/nodejs/node/pull/45858)
-   \[[`5eb93f1de9`](https://togithub.com/nodejs/node/commit/5eb93f1de9)] - **doc**: add stream/promises pipeline and finished to doc (Marco Ippolito) [#&#8203;45832](https://togithub.com/nodejs/node/pull/45832)
-   \[[`f874d0ba74`](https://togithub.com/nodejs/node/commit/f874d0ba74)] - **doc**: remove Juan Jose keys (Rafael Gonzaga) [#&#8203;45827](https://togithub.com/nodejs/node/pull/45827)
-   \[[`67efe2a55e`](https://togithub.com/nodejs/node/commit/67efe2a55e)] - **doc**: fix wrong output of example in util (Deokjin Kim) [#&#8203;45825](https://togithub.com/nodejs/node/pull/45825)
-   \[[`b709af31e0`](https://togithub.com/nodejs/node/commit/b709af31e0)] - **doc**: sort http.createServer() options alphabetically (Luigi Pinca) [#&#8203;45680](https://togithub.com/nodejs/node/pull/45680)
-   \[[`ebe292113a`](https://togithub.com/nodejs/node/commit/ebe292113a)] - **doc,crypto**: fix WebCryptoAPI import keyData and export return (Filip Skokan) [#&#8203;46076](https://togithub.com/nodejs/node/pull/46076)
-   \[[`204757719c`](https://togithub.com/nodejs/node/commit/204757719c)] - **errors**: refactor to use a method that formats a list string (Daeyeon Jeong) [#&#8203;45793](https://togithub.com/nodejs/node/pull/45793)
-   \[[`463bb9602e`](https://togithub.com/nodejs/node/commit/463bb9602e)] - **esm**: mark `importAssertions` as required (Antoine du Hamel) [#&#8203;46164](https://togithub.com/nodejs/node/pull/46164)
-   \[[`0bdf2db079`](https://togithub.com/nodejs/node/commit/0bdf2db079)] - **esm**: rewrite loader hooks test (Geoffrey Booth) [#&#8203;46016](https://togithub.com/nodejs/node/pull/46016)
-   \[[`297773c6d1`](https://togithub.com/nodejs/node/commit/297773c6d1)] - **events**: change status of `event.returnvalue` to legacy (Deokjin Kim) [#&#8203;46175](https://togithub.com/nodejs/node/pull/46175)
-   \[[`d088d6e5c3`](https://togithub.com/nodejs/node/commit/d088d6e5c3)] - **events**: change status of `event.cancelBubble` to legacy (Deokjin Kim) [#&#8203;46146](https://togithub.com/nodejs/node/pull/46146)
-   \[[`36be0c4ee2`](https://togithub.com/nodejs/node/commit/36be0c4ee2)] - **events**: change status of `event.srcElement` to legacy (Deokjin Kim) [#&#8203;46085](https://togithub.com/nodejs/node/pull/46085)
-   \[[`b239f0684a`](https://togithub.com/nodejs/node/commit/b239f0684a)] - **events**: fix violation of symbol naming convention (Deokjin Kim) [#&#8203;45978](https://togithub.com/nodejs/node/pull/45978)
-   \[[`aec340b312`](https://togithub.com/nodejs/node/commit/aec340b312)] - **fs**: refactor to use `validateInteger` (Deokjin Kim) [#&#8203;46008](https://togithub.com/nodejs/node/pull/46008)
-   \[[`e620de6444`](https://togithub.com/nodejs/node/commit/e620de6444)] - **http**: refactor to use `validateHeaderName` (Deokjin Kim) [#&#8203;46143](https://togithub.com/nodejs/node/pull/46143)
-   \[[`3e70b7d863`](https://togithub.com/nodejs/node/commit/3e70b7d863)] - **http**: writeHead if statusmessage is undefined dont override headers (Marco Ippolito) [#&#8203;46173](https://togithub.com/nodejs/node/pull/46173)
-   \[[`3d1dd96c4f`](https://togithub.com/nodejs/node/commit/3d1dd96c4f)] - **http**: refactor to use min of validateNumber for maxTotalSockets (Deokjin Kim) [#&#8203;46115](https://togithub.com/nodejs/node/pull/46115)
-   \[[`4df1fcc9db`](https://togithub.com/nodejs/node/commit/4df1fcc9db)] - **(SEMVER-MINOR)** **http**: join authorization headers (Marco Ippolito) [#&#8203;45982](https://togithub.com/nodejs/node/pull/45982)
-   \[[`8c06e2f645`](https://togithub.com/nodejs/node/commit/8c06e2f645)] - **http**: replace `var` with `const` on code of comment (Deokjin Kim) [#&#8203;45951](https://togithub.com/nodejs/node/pull/45951)
-   \[[`3c0c5e0567`](https://togithub.com/nodejs/node/commit/3c0c5e0567)] - **(SEMVER-MINOR)** **http**: improved timeout defaults handling (Paolo Insogna) [#&#8203;45778](https://togithub.com/nodejs/node/pull/45778)
-   \[[`edcd4fc576`](https://togithub.com/nodejs/node/commit/edcd4fc576)] - **lib**: use kEmptyObject and update JSDoc in webstreams (Deokjin Kim) [#&#8203;46183](https://togithub.com/nodejs/node/pull/46183)
-   \[[`d6fc855b8a`](https://togithub.com/nodejs/node/commit/d6fc855b8a)] - **lib**: refactor to use validate function (Deokjin Kim) [#&#8203;46101](https://togithub.com/nodejs/node/pull/46101)
-   \[[`bc17f37b98`](https://togithub.com/nodejs/node/commit/bc17f37b98)] - **lib**: reuse invalid state errors on webstreams (Rafael Gonzaga) [#&#8203;46086](https://togithub.com/nodejs/node/pull/46086)
-   \[[`86554bf27c`](https://togithub.com/nodejs/node/commit/86554bf27c)] - **lib**: fix incorrect use of console intrinsic (Colin Ihrig) [#&#8203;46044](https://togithub.com/nodejs/node/pull/46044)
-   \[[`7fc7b19124`](https://togithub.com/nodejs/node/commit/7fc7b19124)] - **lib**: update JSDoc of `getOwnPropertyValueOrDefault` (Deokjin Kim) [#&#8203;46010](https://togithub.com/nodejs/node/pull/46010)
-   \[[`c1cc1f9e12`](https://togithub.com/nodejs/node/commit/c1cc1f9e12)] - **lib**: use `kEmptyObject` as default value for options (Deokjin Kim) [#&#8203;46011](https://togithub.com/nodejs/node/pull/46011)
-   \[[`db617222da`](https://togithub.com/nodejs/node/commit/db617222da)] - **meta**: update AUTHORS (Node.js GitHub Bot) [#&#8203;46215](https://togithub.com/nodejs/node/pull/46215)
-   \[[`10afecd0d8`](https://togithub.com/nodejs/node/commit/10afecd0d8)] - **meta**: update AUTHORS (Node.js GitHub Bot) [#&#8203;46130](https://togithub.com/nodejs/node/pull/46130)
-   \[[`d8ce990ce6`](https://togithub.com/nodejs/node/commit/d8ce990ce6)] - **meta**: update comment in `CODEOWNERS` to better reflect current policy (Antoine du Hamel) [#&#8203;45944](https://togithub.com/nodejs/node/pull/45944)
-   \[[`e3f0194168`](https://togithub.com/nodejs/node/commit/e3f0194168)] - **meta**: update AUTHORS (Node.js GitHub Bot) [#&#8203;46040](https://togithub.com/nodejs/node/pull/46040)
-   \[[`d31c478929`](https://togithub.com/nodejs/node/commit/d31c478929)] - **meta**: update AUTHORS (Node.js GitHub Bot) [#&#8203;45968](https://togithub.com/nodejs/node/pull/45968)
-   \[[`10a276a3e0`](https://togithub.com/nodejs/node/commit/10a276a3e0)] - **meta**: add `nodejs/loaders` to CODEOWNERS (Geoffrey Booth) [#&#8203;45940](https://togithub.com/nodejs/node/pull/45940)
-   \[[`56247d7c87`](https://togithub.com/nodejs/node/commit/56247d7c87)] - **meta**: add `nodejs/test_runner` to CODEOWNERS (Antoine du Hamel) [#&#8203;45935](https://togithub.com/nodejs/node/pull/45935)
-   \[[`3bef8bc743`](https://togithub.com/nodejs/node/commit/3bef8bc743)] - **meta**: update AUTHORS (Node.js GitHub Bot) [#&#8203;45899](https://togithub.com/nodejs/node/pull/45899)
-   \[[`baf30ee935`](https://togithub.com/nodejs/node/commit/baf30ee935)] - **module**: fix unintended mutation (Antoine du Hamel) [#&#8203;46108](https://togithub.com/nodejs/node/pull/46108)
-   \[[`3ad584c357`](https://togithub.com/nodejs/node/commit/3ad584c357)] - **net**: handle socket.write(cb) edge case (Santiago Gimeno) [#&#8203;45922](https://togithub.com/nodejs/node/pull/45922)
-   \[[`2ab35cf0cc`](https://togithub.com/nodejs/node/commit/2ab35cf0cc)] - **node-api**: disambiguate napi_add_finalizer (Chengzhong Wu) [#&#8203;45401](https://togithub.com/nodejs/node/pull/45401)
-   \[[`6e9676e986`](https://togithub.com/nodejs/node/commit/6e9676e986)] - **node-api**: generalize finalizer second pass callback (Chengzhong Wu) [#&#8203;44141](https://togithub.com/nodejs/node/pull/44141)
-   \[[`b2faceff0a`](https://togithub.com/nodejs/node/commit/b2faceff0a)] - **(SEMVER-MINOR)** **os**: add availableParallelism() (Colin Ihrig) [#&#8203;45895](https://togithub.com/nodejs/node/pull/45895)
-   \[[`8fac4c5684`](https://togithub.com/nodejs/node/commit/8fac4c5684)] - **perf_hooks**: fix checking range of `options.figures` in createHistogram (Deokjin Kim) [#&#8203;45999](https://togithub.com/nodejs/node/pull/45999)
-   \[[`ea73702847`](https://togithub.com/nodejs/node/commit/ea73702847)] - **process,worker**: ensure code after exit() effectless (ywave620) [#&#8203;45620](https://togithub.com/nodejs/node/pull/45620)
-   \[[`784ed594ea`](https://togithub.com/nodejs/node/commit/784ed594ea)] - **repl**: improve robustness wrt to prototype pollution (Antoine du Hamel) [#&#8203;45604](https://togithub.com/nodejs/node/pull/45604)
-   \[[`fcfde3412e`](https://togithub.com/nodejs/node/commit/fcfde3412e)] - **src**: rename internal module declaration as internal bindings (Chengzhong Wu) [#&#8203;45551](https://togithub.com/nodejs/node/pull/45551)
-   \[[`646cadccd0`](https://togithub.com/nodejs/node/commit/646cadccd0)] - **src**: fix endianness of simdutf (Yagiz Nizipli) [#&#8203;46257](https://togithub.com/nodejs/node/pull/46257)
-   \[[`94605b1665`](https://togithub.com/nodejs/node/commit/94605b1665)] - **src**: replace unreachable code with static_assert (Tobias Nießen) [#&#8203;46209](https://togithub.com/nodejs/node/pull/46209)
-   \[[`3ce39bbcb7`](https://togithub.com/nodejs/node/commit/3ce39bbcb7)] - **src**: hide kMaxDigestMultiplier outside HKDF impl (Tobias Nießen) [#&#8203;46206](https://togithub.com/nodejs/node/pull/46206)
-   \[[`9648b06e09`](https://togithub.com/nodejs/node/commit/9648b06e09)] - **src**: distinguish env stopping flags (Chengzhong Wu) [#&#8203;45907](https://togithub.com/nodejs/node/pull/45907)
-   \[[`53ecd20bbd`](https://togithub.com/nodejs/node/commit/53ecd20bbd)] - **src**: remove return after abort (Shelley Vohr) [#&#8203;46172](https://togithub.com/nodejs/node/pull/46172)
-   \[[`c4c8931b9d`](https://togithub.com/nodejs/node/commit/c4c8931b9d)] - **src**: remove unnecessary semicolons (Shelley Vohr) [#&#8203;46171](https://togithub.com/nodejs/node/pull/46171)
-   \[[`fab72b1677`](https://togithub.com/nodejs/node/commit/fab72b1677)] - **src**: use simdutf for converting externalized builtins to UTF-16 (Anna Henningsen) [#&#8203;46119](https://togithub.com/nodejs/node/pull/46119)
-   \[[`67729961e7`](https://togithub.com/nodejs/node/commit/67729961e7)] - **src**: use constant strings for memory info names (Chengzhong Wu) [#&#8203;46087](https://togithub.com/nodejs/node/pull/46087)
-   \[[`0ac4e5dd34`](https://togithub.com/nodejs/node/commit/0ac4e5dd34)] - **src**: fix typo in node_snapshotable.cc (Vadim) [#&#8203;46103](https://togithub.com/nodejs/node/pull/46103)
-   \[[`b454a7665d`](https://togithub.com/nodejs/node/commit/b454a7665d)] - **src**: keep PipeWrap::Open function consistent with TCPWrap (theanarkh) [#&#8203;46064](https://togithub.com/nodejs/node/pull/46064)
-   \[[`41f5a29cca`](https://togithub.com/nodejs/node/commit/41f5a29cca)] - **src**: speed up process.getActiveResourcesInfo() (Darshan Sen) [#&#8203;46014](https://togithub.com/nodejs/node/pull/46014)
-   \[[`02a61dd6bd`](https://togithub.com/nodejs/node/commit/02a61dd6bd)] - **src**: fix typo in `node_file.cc` (Vadim) [#&#8203;45998](https://togithub.com/nodejs/node/pull/45998)
-   \[[`99c033ed98`](https://togithub.com/nodejs/node/commit/99c033ed98)] - **src**: fix crash on OnStreamRead on Windows (Santiago Gimeno) [#&#8203;45878](https://togithub.com/nodejs/node/pull/45878)
-   \[[`27d6a8b2b1`](https://togithub.com/nodejs/node/commit/27d6a8b2b1)] - **src**: fix creating `Isolate`s from addons (Anna Henningsen) [#&#8203;45885](https://togithub.com/nodejs/node/pull/45885)
-   \[[`9ca31cdba3`](https://togithub.com/nodejs/node/commit/9ca31cdba3)] - **src**: use string_view for FastStringKey implementation (Anna Henningsen) [#&#8203;45914](https://togithub.com/nodejs/node/pull/45914)
-   \[[`e4fc3abfd5`](https://togithub.com/nodejs/node/commit/e4fc3abfd5)] - **src**: fix UB in overflow checks (Ben Noordhuis) [#&#8203;45882](https://togithub.com/nodejs/node/pull/45882)
-   \[[`574afac26a`](https://togithub.com/nodejs/node/commit/574afac26a)] - **src**: check size of args before using for exec_path (A. Wilcox) [#&#8203;45902](https://togithub.com/nodejs/node/pull/45902)
-   \[[`f0692468cd`](https://togithub.com/nodejs/node/commit/f0692468cd)] - **src**: fix tls certificate root store data race (Ben Noordhuis) [#&#8203;45767](https://togithub.com/nodejs/node/pull/45767)
-   \[[`a749ceda2e`](https://togithub.com/nodejs/node/commit/a749ceda2e)] - **src**: add undici and acorn to `process.versions` (Debadree Chatterjee) [#&#8203;45621](https://togithub.com/nodejs/node/pull/45621)
-   \[[`08a6a61575`](https://togithub.com/nodejs/node/commit/08a6a61575)] - **src,lib**: the handle keeps loop alive in cluster rr mode (theanarkh) [#&#8203;46161](https://togithub.com/nodejs/node/pull/46161)
-   \[[`a87963de6b`](https://togithub.com/nodejs/node/commit/a87963de6b)] - **stream**: fix pipeline calling end on destination more than once (Debadree Chatterjee) [#&#8203;46226](https://togithub.com/nodejs/node/pull/46226)
-   \[[`cde59606cd`](https://togithub.com/nodejs/node/commit/cde59606cd)] - **(SEMVER-MINOR)** **stream**: implement finished() for ReadableStream and WritableStream (Debadree Chatterjee) [#&#8203;46205](https://togithub.com/nodejs/node/pull/46205)
-   \[[`441d9de33e`](https://togithub.com/nodejs/node/commit/441d9de33e)] - **stream**: refactor to use `validateFunction` (Deokjin Kim) [#&#8203;46007](https://togithub.com/nodejs/node/pull/46007)
-   \[[`325fc08d48`](https://togithub.com/nodejs/node/commit/325fc08d48)] - **stream**: fix typo in JSDoc (Deokjin Kim) [#&#8203;45991](https://togithub.com/nodejs/node/pull/45991)
-   \[[`536322fa1c`](https://togithub.com/nodejs/node/commit/536322fa1c)] - **test**: update postject to 1.0.0-alpha.4 (Node.js GitHub Bot) [#&#8203;46212](https://togithub.com/nodejs/node/pull/46212)
-   \[[`a3056f4125`](https://togithub.com/nodejs/node/commit/a3056f4125)] - **test**: refactor to avoid mutation of global by a loader (Michaël Zasso) [#&#8203;46220](https://togithub.com/nodejs/node/pull/46220)
-   \[[`1790569518`](https://togithub.com/nodejs/node/commit/1790569518)] - **test**: improve test coverage for WHATWG `TextDecoder` (Juan José) [#&#8203;45241](https://togithub.com/nodejs/node/pull/45241)
-   \[[`896027c006`](https://togithub.com/nodejs/node/commit/896027c006)] - **test**: add fix so that test exits if port 42 is unprivileged (Suyash Nayan) [#&#8203;45904](https://togithub.com/nodejs/node/pull/45904)
-   \[[`257224da0e`](https://togithub.com/nodejs/node/commit/257224da0e)] - **test**: use `os.availableParallelism()` (Deokjin Kim) [#&#8203;46003](https://togithub.com/nodejs/node/pull/46003)
-   \[[`7e1462dd02`](https://togithub.com/nodejs/node/commit/7e1462dd02)] - **test**: update Web Events WPT (Deokjin Kim) [#&#8203;46051](https://togithub.com/nodejs/node/pull/46051)
-   \[[`40d52fbc5f`](https://togithub.com/nodejs/node/commit/40d52fbc5f)] - **test**: add test to once() in event lib (Jonathan Diaz) [#&#8203;46126](https://togithub.com/nodejs/node/pull/46126)
-   \[[`f3518f3337`](https://togithub.com/nodejs/node/commit/f3518f3337)] - **test**: use `process.hrtime.bigint` instead of `process.hrtime` (Deokjin Kim) [#&#8203;45877](https://togithub.com/nodejs/node/pull/45877)
-   \[[`4d6dd10464`](https://togithub.com/nodejs/node/commit/4d6dd10464)] - **test**: print failed JS/parallel tests (Geoffrey Booth) [#&#8203;45960](https://togithub.com/nodejs/node/pull/45960)
-   \[[`7cb6fef6d6`](https://togithub.com/nodejs/node/commit/7cb6fef6d6)] - **test**: fix test broken under --node-builtin-modules-path (Geoffrey Booth) [#&#8203;45894](https://togithub.com/nodejs/node/pull/45894)
-   \[[`55e4140c34`](https://togithub.com/nodejs/node/commit/55e4140c34)] - **test**: fix mock.method to support class instances (Erick Wendel) [#&#8203;45608](https://togithub.com/nodejs/node/pull/45608)
-   \[[`286acaa6fe`](https://togithub.com/nodejs/node/commit/286acaa6fe)] - **test**: update encoding wpt to latest (Yagiz Nizipli) [#&#8203;45850](https://togithub.com/nodejs/node/pull/45850)
-   \[[`22c1e918ce`](https://togithub.com/nodejs/node/commit/22c1e918ce)] - **test**: update url wpt to latest (Yagiz Nizipli) [#&#8203;45852](https://togithub.com/nodejs/node/pull/45852)
-   \[[`5fa6a70bbd`](https://togithub.com/nodejs/node/commit/5fa6a70bbd)] - **test**: add CryptoKey transferring tests (Filip Skokan) [#&#8203;45811](https://togithub.com/nodejs/node/pull/45811)
-   \[[`4aaec07266`](https://togithub.com/nodejs/node/commit/4aaec07266)] - **test**: add postject to fixtures (Darshan Sen) [#&#8203;45298](https://togithub.com/nodejs/node/pull/45298)
-   \[[`da78f9cbb8`](https://togithub.com/nodejs/node/commit/da78f9cbb8)] - **test,crypto**: update WebCryptoAPI WPT (Filip Skokan) [#&#8203;45860](https://togithub.com/nodejs/node/pull/45860)
-   \[[`3269423032`](https://togithub.com/nodejs/node/commit/3269423032)] - **test,esm**: validate more edge cases for dynamic imports (Antoine du Hamel) [#&#8203;46059](https://togithub.com/nodejs/node/pull/46059)
-   \[[`cade2fccf4`](https://togithub.com/nodejs/node/commit/cade2fccf4)] - **test_runner**: run t.after() if test body throws (Colin Ihrig) [#&#8203;45870](https://togithub.com/nodejs/node/pull/45870)
-   \[[`87a0e86604`](https://togithub.com/nodejs/node/commit/87a0e86604)] - **test_runner**: parse yaml (Moshe Atlow) [#&#8203;45815](https://togithub.com/nodejs/node/pull/45815)
-   \[[`757a022443`](https://togithub.com/nodejs/node/commit/757a022443)] - **tls**: don't treat fatal TLS alerts as EOF (David Benjamin) [#&#8203;44563](https://togithub.com/nodejs/node/pull/44563)
-   \[[`c6457cbf8d`](https://togithub.com/nodejs/node/commit/c6457cbf8d)] - **tls**: fix re-entrancy issue with TLS close_notify (David Benjamin) [#&#8203;44563](https://togithub.com/nodejs/node/pull/44563)
-   \[[`fcca2d5ea6`](https://togithub.com/nodejs/node/commit/fcca2d5ea6)] - **tools**: update lint-md-dependencies (Node.js GitHub Bot) [#&#8203;46214](https://togithub.com/nodejs/node/pull/46214)
-   \[[`09adb86c19`](https://togithub.com/nodejs/node/commit/09adb86c19)] - **tools**: fix macro name in update-undici (Almeida) [#&#8203;46217](https://togithub.com/nodejs/node/pull/46217)
-   \[[`1b0cc79785`](https://togithub.com/nodejs/node/commit/1b0cc79785)] - **tools**: add automation for updating postject dependency (Darshan Sen) [#&#8203;46157](https://togithub.com/nodejs/node/pull/46157)
-   \[[`38df662119`](https://togithub.com/nodejs/node/commit/38df662119)] - **tools**: update create-or-update-pull-request-action (Michaël Zasso) [#&#8203;46169](https://togithub.com/nodejs/node/pull/46169)
-   \[[`3f4c0c0de1`](https://togithub.com/nodejs/node/commit/3f4c0c0de1)] - **tools**: update eslint to 8.31.0 (Node.js GitHub Bot) [#&#8203;46131](https://togithub.com/nodejs/node/pull/46131)
-   \[[`f3dc4329e6`](https://togithub.com/nodejs/node/commit/f3dc4329e6)] - **tools**: update lint-md-dependencies to rollup@3.9.1 (Node.js GitHub Bot) [#&#8203;46129](https://togithub.com/nodejs/node/pull/46129)
-   \[[`fafbd1ca72`](https://togithub.com/nodejs/node/commit/fafbd1ca72)] - **tools**: move update-eslint.sh to dep_updaters/ (Luigi Pinca) [#&#8203;46088](https://togithub.com/nodejs/node/pull/46088)
-   \[[`609df01fa9`](https://togithub.com/nodejs/node/commit/609df01fa9)] - **tools**: make update-eslint.sh work with npm@9 (Luigi Pinca) [#&#8203;46088](https://togithub.com/nodejs/node/pull/46088)
-   \[[`31b8cf1a4d`](https://togithub.com/nodejs/node/commit/31b8cf1a4d)] - **tools**: fix lint rule recommendation (Colin Ihrig) [#&#8203;46044](https://togithub.com/nodejs/node/pull/46044)
-   \[[`0a80cbdcb1`](https://togithub.com/nodejs/node/commit/0a80cbdcb1)] - **tools**: update lint-md-dependencies to rollup@3.9.0 (Node.js GitHub Bot) [#&#8203;46039](https://togithub.com/nodejs/node/pull/46039)
-   \[[`18503fa7ba`](https://togithub.com/nodejs/node/commit/18503fa7ba)] - **tools**: update doc to unist-util-select@4.0.2 (Node.js GitHub Bot) [#&#8203;46038](https://togithub.com/nodejs/node/pull/46038)
-   \[[`b48e82ec1d`](https://togithub.com/nodejs/node/commit/b48e82ec1d)] - **tools**: add release host var to promotion script (Ruy Adorno) [#&#8203;45913](https://togithub.com/nodejs/node/pull/45913)
-   \[[`3b93b0c1f5`](https://togithub.com/nodejs/node/commit/3b93b0c1f5)] - **tools**: add url to `AUTHORS` update automation (Antoine du Hamel) [#&#8203;45971](https://togithub.com/nodejs/node/pull/45971)
-   \[[`623b0eba81`](https://togithub.com/nodejs/node/commit/623b0eba81)] - **tools**: update lint-md-dependencies to rollup@3.8.1 (Node.js GitHub Bot) [#&#8203;45967](https://togithub.com/nodejs/node/pull/45967)
-   \[[`b0e88377fe`](https://togithub.com/nodejs/node/commit/b0e88377fe)] - **tools**: update GitHub workflow action (Mohammed Keyvanzadeh) [#&#8203;45937](https://togithub.com/nodejs/node/pull/45937)
-   \[[`974442e69d`](https://togithub.com/nodejs/node/commit/974442e69d)] - **tools**: update lint-md dependencies (Node.js GitHub Bot) [#&#8203;45813](https://togithub.com/nodejs/node/pull/45813)
-   \[[`5aaa8c3bbf`](https://togithub.com/nodejs/node/commit/5aaa8c3bbf)] - **tools**: enforce use of trailing commas in `tools/` (Antoine du Hamel) [#&#8203;45889](https://togithub.com/nodejs/node/pull/45889)
-   \[[`1e32520f72`](https://togithub.com/nodejs/node/commit/1e32520f72)] - **tools**: add `ArrayPrototypeConcat` to the list of primordials to avoid (Antoine du Hamel) [#&#8203;44445](https://togithub.com/nodejs/node/pull/44445)
-   \[[`e0cda56204`](https://togithub.com/nodejs/node/commit/e0cda56204)] - **tools**: fix incorrect version history order (Fabien Michel) [#&#8203;45728](https://togithub.com/nodejs/node/pull/45728)
-   \[[`7438ff175a`](https://togithub.com/nodejs/node/commit/7438ff175a)] - **tools**: update eslint to 8.29.0 (Node.js GitHub Bot) [#&#8203;45733](https://togithub.com/nodejs/node/pull/45733)
-   \[[`1e11247b91`](https://togithub.com/nodejs/node/commit/1e11247b91)] - ***Revert*** "**tools**: update V8 gypfiles for RISC-V" (Lu Yahan) [#&#8203;46156](https://togithub.com/nodejs/node/pull/46156)
-   \[[`0defe4effa`](https://togithub.com/nodejs/node/commit/0defe4effa)] - **trace_events**: refactor to use `validateStringArray` (Deokjin Kim) [#&#8203;46012](https://togithub.com/nodejs/node/pull/46012)
-   \[[`f1dcbe7652`](https://togithub.com/nodejs/node/commit/f1dcbe7652)] - **util**: add fast path for text-decoder fatal flag (Yagiz Nizipli) [#&#8203;45803](https://togithub.com/nodejs/node/pull/45803)
-   \[[`277d9da876`](https://togithub.com/nodejs/node/commit/277d9da876)] - **vm**: refactor to use validate function (Deokjin Kim) [#&#8203;46176](https://togithub.com/nodejs/node/pull/46176)
-   \[[`96f1b2e731`](https://togithub.com/nodejs/node/commit/96f1b2e731)] - **vm**: refactor to use `validateStringArray` (Deokjin Kim) [#&#8203;46020](https://togithub.com/nodejs/node/pull/46020)

### [`v18.13.0`](https://togithub.com/nodejs/node/releases/tag/v18.13.0): 2023-01-05, Version 18.13.0 &#x27;Hydrogen&#x27; (LTS), @&#8203;danielleadams

[Compare Source](https://togithub.com/nodejs/node/compare/v18.12.1...v18.13.0)

##### Notable changes

##### Add support for externally shared js builtins

By default Node.js is built so that all dependencies are bundled into the Node.js binary itself. Some Node.js distributions prefer to manage dependencies externally. There are existing build options that allow dependencies with native code to be externalized. This commit adds additional options so that dependencies with JavaScript code (including WASM) can also be externalized. This addition does not affect binaries shipped by the Node.js project but will allow other distributions to externalize additional dependencies when needed.

Contributed by Michael Dawson in [#&#8203;44376](https://togithub.com/nodejs/node/pull/44376)

##### Introduce `File`

The File class is part of the [FileAPI](https://w3c.github.io/FileAPI/). It can be used anywhere a Blob can, for example in `URL.createObjectURL` and `FormData`. It contains two properties that Blobs do not have: `lastModified`, the last time the file was modified in ms, and `name`, the name of the file.

Contributed by Khafra in [#&#8203;45139](https://togithub.com/nodejs/node/pull/45139)

##### Support function mocking on Node.js test runner

The `node:test` module supports mocking during testing via a top-level `mock`
object.

```js
test('spies on an object method', (t) => {
  const number = {
    value: 5,
    add(a) {
      return this.value + a;
    },
  };
  t.mock.method(number, 'add');

  assert.strictEqual(number.add(3), 8);
  assert.strictEqual(number.add.mock.calls.length, 1);
});
```

Contributed by Colin Ihrig in [#&#8203;45326](https://togithub.com/nodejs/node/pull/45326)

##### Other notable changes

-   **build**:
    -   disable v8 snapshot compression by default (Joyee Cheung) [#&#8203;45716](https://togithub.com/nodejs/node/pull/45716)
-   **crypto**:
    -   update root certificates (Luigi Pinca) [#&#8203;45490](https://togithub.com/nodejs/node/pull/45490)
-   **deps**:
    -   update ICU to 72.1 (Michaël Zasso) [#&#8203;45068](https://togithub.com/nodejs/node/pull/45068)
-   **doc**:
    -   add doc-only deprecation for headers/trailers setters (Rich Trott) [#&#8203;45697](https://togithub.com/nodejs/node/pull/45697)
    -   add Rafael to the tsc (Michael Dawson) [#&#8203;45691](https://togithub.com/nodejs/node/pull/45691)
    -   deprecate use of invalid ports in `url.parse` (Antoine du Hamel) [#&#8203;45576](https://togithub.com/nodejs/node/pull/45576)
    -   add lukekarrys to collaborators (Luke Karrys) [#&#8203;45180](https://togithub.com/nodejs/node/pull/45180)
    -   add anonrig to collaborators (Yagiz Nizipli) [#&#8203;45002](https://togithub.com/nodejs/node/pull/45002)
    -   deprecate url.parse() (Rich Trott) [#&#8203;44919](https://togithub.com/nodejs/node/pull/44919)
-   **lib**:
    -   drop fetch experimental warning (Matteo Collina) [#&#8203;45287](https://togithub.com/nodejs/node/pull/45287)
-   **net**:
    -   (SEMVER-MINOR) add autoSelectFamily and autoSelectFamilyAttemptTimeout options (Paolo Insogna) [#&#8203;44731](https://togithub.com/nodejs/node/pull/44731)
-   **src**:
    -   (SEMVER-MINOR) add uvwasi version (Jithil P Ponnan) [#&#8203;45639](https://togithub.com/nodejs/node/pull/45639)
    -   (SEMVER-MINOR) add initial shadow realm support (Chengzhong Wu) [#&#8203;42869](https://togithub.com/nodejs/node/pull/42869)
-   **test_runner**:
    -   (SEMVER-MINOR) add t.after() hook (Colin Ihrig) [#&#8203;45792](https://togithub.com/nodejs/node/pull/45792)
    -   (SEMVER-MINOR) don't use a symbol for runHook() (Colin Ihrig) [#&#8203;45792](https://togithub.com/nodejs/node/pull/45792)
-   **tls**:
    -   (SEMVER-MINOR) add "ca" property to certificate object (Ben Noordhuis) [#&#8203;44935](https://togithub.com/nodejs/node/pull/44935)
    -   remove trustcor root ca certificates (Ben Noordhuis) [#&#8203;45776](https://togithub.com/nodejs/node/pull/45776)
-   **tools**:
    -   update certdata.txt (Luigi Pinca) [#&#8203;45490](https://togithub.com/nodejs/node/pull/45490)
-   **util**:
    -   add fast path for utf8 encoding (Yagiz Nizipli) [#&#8203;45412](https://togithub.com/nodejs/node/pull/45412)
    -   improve textdecoder decode performance (Yagiz Nizipli) [#&#8203;45294](https://togithub.com/nodejs/node/pull/45294)
    -   (SEMVER-MINOR) add MIME utilities ([#&#8203;21128](https://togithub.com/nodejs/node/issues/21128)) (Bradley Farias) [#&#8203;21128](https://togithub.com/nodejs/node/pull/21128)

##### Commits

-   \[[`40123a6bb0`](https://togithub.com/nodejs/node/commit/40123a6bb0)] - **(SEMVER-MINOR)** **async_hooks**: add hook to stop propagation (Gerhard Stöbich) [#&#8203;45386](https://togithub.com/nodejs/node/pull/45386)
-   \[[`9925d20ed8`](https://togithub.com/nodejs/node/commit/9925d20ed8)] - **benchmark**: add variety of inputs to text-encoder (Yagiz Nizipli) [#&#8203;45787](https://togithub.com/nodejs/node/pull/45787)
-   \[[`5e167bd658`](https://togithub.com/nodejs/node/commit/5e167bd658)] - **benchmark**: make benchmarks runnable in older versions of Node.js (Joyee Cheung) [#&#8203;45746](https://togithub.com/nodejs/node/pull/45746)
-   \[[`a1421623ac`](https://togithub.com/nodejs/node/commit/a1421623ac)] - **benchmark**: add v8 serialize benchmark (Yagiz Nizipli) [#&#8203;45476](https://togithub.com/nodejs/node/pull/45476)
-   \[[`fcf61884cc`](https://togithub.com/nodejs/node/commit/fcf61884cc)] - **benchmark**: add text-encoder benchmark (Yagiz Nizipli) [#&#8203;45450](https://togithub.com/nodejs/node/pull/45450)
-   \[[`762d285c98`](https://togithub.com/nodejs/node/commit/762d285c98)] - **benchmark**: add parameters to text-decoder benchmark (Yagiz Nizipli) [#&#8203;45363](https://togithub.com/nodejs/node/pull/45363)
-   \[[`ab891ecbff`](https://togithub.com/nodejs/node/commit/ab891ecbff)] - **benchmark**: fix text-decoder benchmark (Yagiz Nizipli) [#&#8203;45363](https://togithub.com/nodejs/node/pull/45363)
-   \[[`1ed312a737`](https://togithub.com/nodejs/node/commit/1ed312a737)] - **benchmark**: add blob benchmark (Yagiz Nizipli) [#&#8203;44990](https://togithub.com/nodejs/node/pull/44990)
-   \[[`2ee3d81277`](https://togithub.com/nodejs/node/commit/2ee3d81277)] - **bootstrap**: merge main thread and worker thread initializations (Joyee Cheung) [#&#8203;44869](https://togithub.com/nodejs/node/pull/44869)
-   \[[`e638ea4f48`](https://togithub.com/nodejs/node/commit/e638ea4f48)] - **bootstrap**: check more metadata when loading the snapshot (Joyee Cheung) [#&#8203;44132](https://togithub.com/nodejs/node/pull/44132)
-   \[[`bfcf4f0046`](https://togithub.com/nodejs/node/commit/bfcf4f0046)] - **buffer**: make decodeUTF8 params loose (Yagiz Nizipli) [#&#8203;45610](https://togithub.com/nodejs/node/pull/45610)
-   \[[`3a7f3d5993`](https://togithub.com/nodejs/node/commit/3a7f3d5993)] - **(SEMVER-MINOR)** **buffer**: introduce File (Khafra) [#&#8203;45139](https://togithub.com/nodejs/node/pull/45139)
-   \[[`345b847aa6`](https://togithub.com/nodejs/node/commit/345b847aa6)] - **buffer**: fix validation of options in `Blob` constructor (Antoine du Hamel) [#&#8203;45156](https://togithub.com/nodejs/node/pull/45156)
-   \[[`1ddc438444`](https://togithub.com/nodejs/node/commit/1ddc438444)] - **build**: disable v8 snapshot compression by default (Joyee Cheung) [#&#8203;45716](https://togithub.com/nodejs/node/pull/45716)
-   \[[`bd1a2fbd91`](https://togithub.com/nodejs/node/commit/bd1a2fbd91)] - **build**: add python 3.11 support for android (Mohammed Keyvanzadeh) [#&#8203;45765](https://togithub.com/nodejs/node/pull/45765)
-   \[[`2b0ace302d`](https://togithub.com/nodejs/node/commit/2b0ace302d)] - **build**: rework gyp files for zlib (Richard Lau) [#&#8203;45589](https://togithub.com/nodejs/node/pull/45589)
-   \[[`5ab7a30a06`](https://togithub.com/nodejs/node/commit/5ab7a30a06)] - **build**: avoid redefined macro (Michaël Zasso) [#&#8203;45544](https://togithub.com/nodejs/node/pull/45544)
-   \[[`f58b32c22e`](https://togithub.com/nodejs/node/commit/f58b32c22e)] - **build**: fix env.h for cpp20 (Jiawen Geng) [#&#8203;45516](https://togithub.com/nodejs/node/pull/45516)
-   \[[`1de1f679ec`](https://togithub.com/nodejs/node/commit/1de1f679ec)] - ***Revert*** "**build**: remove precompiled header and debug information for host builds" (Stefan Stojanovic) [#&#8203;45432](https://togithub.com/nodejs/node/pull/45432)
-   \[[`89d1eb58b0`](https://togithub.com/nodejs/node/commit/89d1eb58b0)] - **build**: add --v8-disable-object-print flag (MURAKAMI Masahiko) [#&#8203;45458](https://togithub.com/nodejs/node/pull/45458)
-   \[[`f2a4def232`](https://togithub.com/nodejs/node/commit/f2a4def232)] - **build**: make scripts in gyp run with right python (Jiawen Geng) [#&#8203;45435](https://togithub.com/nodejs/node/pull/45435)
-   \[[`473a879c91`](https://togithub.com/nodejs/node/commit/473a879c91)] - **build**: workaround for node-core-utils (Jiawen Geng) [#&#8203;45199](https://togithub.com/nodejs/node/pull/45199)
-   \[[`abcc034c61`](https://togithub.com/nodejs/node/commit/abcc034c61)] - **build**: fix icu-small build with ICU 72.1 (Steven R. Loomis) [#&#8203;45195](https://togithub.com/nodejs/node/pull/45195)
-   \[[`8a99221a21`](https://togithub.com/nodejs/node/commit/8a99221a21)] - **build**: remove unused language files (Ben Noordhuis) [#&#8203;45138](https://togithub.com/nodejs/node/pull/45138)
-   \[[`3fb44f9413`](https://togithub.com/nodejs/node/commit/3fb44f9413)] - **build**: add GitHub token to auto-start-ci workflow (Richard Lau) [#&#8203;45185](https://togithub.com/nodejs/node/pull/45185)
-   \[[`2aac993bb2`](https://togithub.com/nodejs/node/commit/2aac993bb2)] - **build**: add version info to timezone update PR (Darshan Sen) [#&#8203;45021](https://togithub.com/nodejs/node/pull/45021)
-   \[[`0db19b3c60`](https://togithub.com/nodejs/node/commit/0db19b3c60)] - **build**: support Python 3.11 (Luigi Pinca) [#&#8203;45191](https://togithub.com/nodejs/node/pull/45191)
-   \[[`fb008a2e9b`](https://togithub.com/nodejs/node/commit/fb008a2e9b)] - **build,deps,src**: fix Intel VTune profiling support (Shi Lei) [#&#8203;45248](https://togithub.com/nodejs/node/pull/45248)
-   \[[`61bc27a5b4`](https://togithub.com/nodejs/node/commit/61bc27a5b4)] - **build,win**: pass --debug-nghttp2 to configure (Santiago Gimeno) [#&#8203;45209](https://togithub.com/nodejs/node/pull/45209)
-   \[[`7b68c06988`](https://togithub.com/nodejs/node/commit/7b68c06988)] - **child_process**: validate arguments for null bytes (Darshan Sen) [#&#8203;44782](https://togithub.com/nodejs/node/pull/44782)
-   \[[`bac6b7d900`](https://togithub.com/nodejs/node/commit/bac6b7d900)] - **crypto**: simplify lazy loading of internal modules (Antoine du Hamel) [#&#8203;45809](https://togithub.com/nodejs/node/pull/45809)
-   \[[`2fbf95662c`](https://togithub.com/nodejs/node/commit/2fbf95662c)] - **crypto**: fix CipherBase Update int32 overflow (Marco Ippolito) [#&#8203;45769](https://togithub.com/nodejs/node/pull/45769)
-   \[[`0100fd445b`](https://togithub.com/nodejs/node/commit/0100fd445b)] - **crypto**: refactor ArrayBuffer to bigint conversion utils (Antoine du Hamel) [#&#8203;45567](https://togithub.com/nodejs/node/pull/45567)
-   \[[`fa0a2d8e5d`](https://togithub.com/nodejs/node/commit/fa0a2d8e5d)] - **crypto**: refactor verify acceptable key usage functions (Filip Skokan) [#&#8203;45569](https://togithub.com/nodejs/node/pull/45569)
-   \[[`ef64b86d0d`](https://togithub.com/n

</details>

---

### Configuration

📅 **Schedule**: Branch creation - At any time (no schedule defined), Automerge - At any time (no schedule defined).

🚦 **Automerge**: Disabled by config. Please merge this manually once you are satisfied.

♻ **Rebasing**: Whenever PR becomes conflicted, or you tick the rebase/retry checkbox.

🔕 **Ignore**: Close this PR and you won't be reminded about these updates again.

---

 - [ ] <!-- rebase-check -->If you want to rebase/retry this PR, check this box

---

This PR has been generated by [Mend Renovate](https://www.mend.io/free-developer-tools/renovate/). View repository job log [here](https://app.renovatebot.com/dashboard#github/NetPurpose/front).
<!--renovate-debug:eyJjcmVhdGVkSW5WZXIiOiIzNC4xMzguMyIsInVwZGF0ZWRJblZlciI6IjM0LjEzOC4zIn0=-->
