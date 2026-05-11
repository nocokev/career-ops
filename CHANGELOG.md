# Changelog

## 1.0.0 (2026-05-11)


### Features

* adapt contacto mode by contact type (recruiter/HM/peer/interviewer) ([efaa990](https://github.com/nocokev/career-ops/commit/efaa9900c1f0794466f7b5e86e15c3940b59f63d))
* add --min-score flag to batch runner ([#249](https://github.com/nocokev/career-ops/issues/249)) ([4267231](https://github.com/nocokev/career-ops/commit/4267231c511acdc14d20a989365071f9f6c68644))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/nocokev/career-ops/issues/287)) ([c194662](https://github.com/nocokev/career-ops/commit/c19466233cfa271bc27b29ea96f028ab1d65dd9f))
* add Block G — posting legitimacy assessment ([f0b3f63](https://github.com/nocokev/career-ops/commit/f0b3f6370497d2475c66aa15a9969c72abeaa019))
* add follow-up cadence tracker mode ([524774c](https://github.com/nocokev/career-ops/commit/524774cf77f3e28da0afb1356d1f0ed1f3486b2f))
* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([e0b0808](https://github.com/nocokev/career-ops/commit/e0b0808b8ed386adf38e9e887655faead5a02f27))
* add Nix flake devshell with Playwright support ([589dd22](https://github.com/nocokev/career-ops/commit/589dd22a6ff434c2186bc29693368eef3cda670d))
* add OpenCode slash commands for career-ops ([#67](https://github.com/nocokev/career-ops/issues/67)) ([48e7027](https://github.com/nocokev/career-ops/commit/48e702745cd2e18c5b99e735b7d9535696efbd60))
* add scan.mjs — zero-token portal scanner ([1e0094e](https://github.com/nocokev/career-ops/commit/1e0094e0f16bbf2c78fb517a443dc7cd8a1cbbe4))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([96c8941](https://github.com/nocokev/career-ops/commit/96c8941836a01fbed0f1fdf668629e386919a8a1))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/nocokev/career-ops/issues/246)) ([450baab](https://github.com/nocokev/career-ops/commit/450baabe828842815ccfd62e40e919d2ea5ed2c0))
* **dashboard:** add progress analytics screen ([99f3a03](https://github.com/nocokev/career-ops/commit/99f3a0300848057b6f235d88a0bc4b0b29c52f26))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/nocokev/career-ops/issues/262)) ([46c3ca9](https://github.com/nocokev/career-ops/commit/46c3ca982762e7f90c9d742e2f02039917fd6bf7))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([19f003e](https://github.com/nocokev/career-ops/commit/19f003e0ff042d4e4752f7bd4fea22edc8b2ceda))
* expand portals.example.yml with 8 dev-tools companies + 23 search queries ([#140](https://github.com/nocokev/career-ops/issues/140)) ([1e82da6](https://github.com/nocokev/career-ops/commit/1e82da63d27593e68e4a541112ef0997f159f5ae))
* **i18n:** add Japanese README + language modes for Japan market ([1eee793](https://github.com/nocokev/career-ops/commit/1eee79330c3fe326017944b013abf49464a78696))


### Bug Fixes

* 10 bug fixes — resource leaks, command injection, Unicode, navigation ([762dc94](https://github.com/nocokev/career-ops/commit/762dc94c0be64b0d4c77bc6b512c5d753ecac1ad))
* add data/ fallback to UpdateApplicationStatus ([#55](https://github.com/nocokev/career-ops/issues/55)) ([a113c49](https://github.com/nocokev/career-ops/commit/a113c498e5bd5c3ec5fa3543c86c995ec997ed00))
* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/nocokev/career-ops/issues/248)) ([8f6291d](https://github.com/nocokev/career-ops/commit/8f6291d7709238d3f16bc27267d31a63c7d9e381))
* align portals.example.yml indentation for new companies ([e909feb](https://github.com/nocokev/career-ops/commit/e909feb21366035907413fdbff9d52cf6209fd8e))
* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/nocokev/career-ops/issues/260)) ([9ed597c](https://github.com/nocokev/career-ops/commit/9ed597c126390fbcfb5f72691a189426be262eba))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/nocokev/career-ops/issues/137)) ([1cd31af](https://github.com/nocokev/career-ops/commit/1cd31af864a501d5c2b90cb2d427ca5ca830f693))
* correct dashboard launch path in docs ([#80](https://github.com/nocokev/career-ops/issues/80)) ([b5f8456](https://github.com/nocokev/career-ops/commit/b5f8456acb9545fa1d2d5b1c07e63414bbf98f7a))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/nocokev/career-ops/issues/298)) ([ea5380f](https://github.com/nocokev/career-ops/commit/ea5380f43b6d6472201baa3738568faa08c819da))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/nocokev/career-ops/issues/261)) ([e50be14](https://github.com/nocokev/career-ops/commit/e50be14eaa81efc23c2f22bee5043e3d1345acc0))
* filter expired WebSearch links before they reach the pipeline ([#57](https://github.com/nocokev/career-ops/issues/57)) ([6f08bae](https://github.com/nocokev/career-ops/commit/6f08bae0d60cee2c833463639938ff2338f9eff8))
* improve default PDF readability ([#85](https://github.com/nocokev/career-ops/issues/85)) ([bc0e8bd](https://github.com/nocokev/career-ops/commit/bc0e8bd8562b75c0feaccff96703d701146757f3))
* liveness checks ignore nav/footer Apply text, expired signals win ([db77eff](https://github.com/nocokev/career-ops/commit/db77eff1585549913dab38ca46e8b6ddcb28e44d))
* remove npm cache (no package-lock.json) ([0d3dad4](https://github.com/nocokev/career-ops/commit/0d3dad4f5de37068f95c8e0181b15aa9ffee0630))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/nocokev/career-ops/issues/286)) ([e3a9756](https://github.com/nocokev/career-ops/commit/e3a97569f7e74931687f361e4c2d77f644b5814d))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([e0c4697](https://github.com/nocokev/career-ops/commit/e0c4697c6c601323b67c27e3eec4c92bd63c36d8))
* test-all.mjs scans only git-tracked files, avoids false positives ([894dfa3](https://github.com/nocokev/career-ops/commit/894dfa3b994b48fb7ce3907f36b4aa2182cbfbce))
* use candidate name from profile.yml in PDF filename ([ba1257d](https://github.com/nocokev/career-ops/commit/ba1257dacd9008c60ca622b3fd9dcbb9ebf4b613))
* use execFileSync to prevent shell injection in test-all.mjs ([f978c83](https://github.com/nocokev/career-ops/commit/f978c8329931a96b97159690cd2e5fe75f6e6994))
* use fileURLToPath for cross platform compatible paths in tracker scripts ([#32](https://github.com/nocokev/career-ops/issues/32)) ([#58](https://github.com/nocokev/career-ops/issues/58)) ([c193d50](https://github.com/nocokev/career-ops/commit/c193d50331bbf582b5d2b8498cdac1c76ed4b0e0))
* use hi@santifer.io in English README ([f76e799](https://github.com/nocokev/career-ops/commit/f76e79969718a5dcc65b0b00b54af78e2b0599e1))


### Performance Improvements

* compress hero banner from 5.7MB to 671KB ([b3f81d8](https://github.com/nocokev/career-ops/commit/b3f81d84e6579279ca9aada4e19c2fd63546869c))

## [1.5.0](https://github.com/santifer/career-ops/compare/v1.4.0...v1.5.0) (2026-04-14)


### Features

* add --min-score flag to batch runner ([#249](https://github.com/santifer/career-ops/issues/249)) ([cb0c7f7](https://github.com/santifer/career-ops/commit/cb0c7f7d7d3b9f3f1c3dc75ccac0a08d2737c01e))
* add {{PHONE}} placeholder to CV template ([#287](https://github.com/santifer/career-ops/issues/287)) ([e71595f](https://github.com/santifer/career-ops/commit/e71595f8ba134971ecf1cc3c3420d9caf21eed43))
* **dashboard:** add manual refresh shortcut ([#246](https://github.com/santifer/career-ops/issues/246)) ([4b5093a](https://github.com/santifer/career-ops/commit/4b5093a8ef1733c449ec0821f722f996625fcb84))


### Bug Fixes

* add stopword filtering and overlap ratio to roleMatch ([#248](https://github.com/santifer/career-ops/issues/248)) ([4da772d](https://github.com/santifer/career-ops/commit/4da772d3a4996bc9ecbe2d384d1e9d2ed75b9819))
* **dashboard:** show dates in pipeline list ([#298](https://github.com/santifer/career-ops/issues/298)) ([e5e2a6c](https://github.com/santifer/career-ops/commit/e5e2a6cffe9a5b9f3cec862df25410d02ecc9aa4))
* ensure data/ and output/ dirs exist before writing in scripts ([#261](https://github.com/santifer/career-ops/issues/261)) ([4b834f6](https://github.com/santifer/career-ops/commit/4b834f6f7f8f1b647a6bf76e43b017dcbe9cd52f))
* remove wellfound, lever and remotefront from portals.example.yml ([#286](https://github.com/santifer/career-ops/issues/286)) ([ecd013c](https://github.com/santifer/career-ops/commit/ecd013cc6f59e3a1a8ef77d34e7abc15e8075ed3))

## [1.4.0](https://github.com/santifer/career-ops/compare/v1.3.0...v1.4.0) (2026-04-13)


### Features

* add GitHub Actions CI + auto-labeler + welcome bot + /run skill ([2ddf22a](https://github.com/santifer/career-ops/commit/2ddf22a6a2731b38bcaed5786c4855c4ab9fe722))
* **dashboard:** add Catppuccin Latte light theme with auto-detection ([ff686c8](https://github.com/santifer/career-ops/commit/ff686c8af97a7bf93565fe8eeac677f998cc9ece))
* **dashboard:** add progress analytics screen ([623c837](https://github.com/santifer/career-ops/commit/623c837bf3155fd5b7413554240071d40585dd7e))
* **dashboard:** add vim motions to pipeline screen ([#262](https://github.com/santifer/career-ops/issues/262)) ([d149e54](https://github.com/santifer/career-ops/commit/d149e541402db0c88161a71c73899cd1836a1b2d))
* **dashboard:** aligned tables and markdown syntax rendering in viewer ([dbd1d3f](https://github.com/santifer/career-ops/commit/dbd1d3f7177358d0384d6e661d1b0dfc1f60bd4e))


### Bug Fixes

* **ci:** use pull_request_target for labeler on fork PRs ([#260](https://github.com/santifer/career-ops/issues/260)) ([2ecf572](https://github.com/santifer/career-ops/commit/2ecf57206c2eb6e35e2a843d6b8365f7a04c53d6))
* correct _shared.md → _profile.md reference in CUSTOMIZATION.md (closes [#137](https://github.com/santifer/career-ops/issues/137)) ([a91e264](https://github.com/santifer/career-ops/commit/a91e264b6ea047a76d8c033aa564fe01b8f9c1d9))
* replace grep -P with POSIX-compatible grep in batch-runner.sh ([637b39e](https://github.com/santifer/career-ops/commit/637b39e383d1174c8287f42e9534e9e3cdfabb19))
* test-all.mjs scans only git-tracked files, avoids false positives ([47c9f98](https://github.com/santifer/career-ops/commit/47c9f984d8ddc70974f15c99b081667b73f1bb9a))
* use execFileSync to prevent shell injection in test-all.mjs ([c99d5a6](https://github.com/santifer/career-ops/commit/c99d5a6526f923b56c3790b79b0349f402fa00e2))
