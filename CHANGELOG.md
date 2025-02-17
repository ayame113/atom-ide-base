### 3.2.0

- feat: add StyleReader to commons-ui

### 3.1.0

- feat: add intentions package to the list of IDE packages.

### 3.0.0

- feat(breaking): convert ViewContainer components from React to Solid. See `atom-ide-datatips` for an example of their usage.
- fix: update dependencies

### 2.6.0

Added new utility functions:

- commons-ui:
  - isItemVisible
  - getItemElement
  - isElementVisible
- commons-atom:
  - editor largeness
  - editor lineCountIfLarge
  - editor lineLengthIfLong
  - notifyError

Fixed bugs in ViewContainer, scrollIntoView.

### 2.5.0

- feat: add domPurifyConfig parameter to MarkdownSevice.render
- fix: add the required @types packages to the dependencies

### 2.4.0

- Add missing types from atom-languageclient (#57)

### 2.3.5

- Fix atom-package-deps issues (#60)

### 2.3.4

- Fix copying from overlays on MacOS (#58)

### 2.3.3

- fix: add ts-ignore to JSX declaration (#55)

### 2.3.1

- Add copy keymap only once for selectable-overlay

### 2.3.0

- feat: add getCwd: Add function that gets the current working directory given a file or uses the active text editor path. (#51)
- fix: use native copy handling in selectable overlay (#53)
- Deprecate `makeOverLayCopyable` and `copyListener`. Use `makeOverlaySelectable` instead

### 2.2.0

- feat: add selectable-overlay utils (#49)

## [2.1.4](https://github.com/atom-ide-community/atom-ide-base/compare/v2.1.3...v2.1.4)

### Bug fixes:

- Updated atom-package-deps #47
- Updated devDependencies #44
- Improved documentation #46 #45 #43

## [1.4.1](https://github.com/atom-ide-community/atom-ide-base/compare/v1.4.0...v1.4.1) (2020-10-01)

### Bug Fixes

- add files entry ([be2f3aa](https://github.com/atom-ide-community/atom-ide-base/commit/be2f3aab65048b04b7ede83d7beefd4a777d6bc0))

# [1.4.0](https://github.com/atom-ide-community/atom-ide-base/compare/v1.3.0...v1.4.0) (2020-10-01)

### Features

- remove legacy nuclde modules to decrease the space ([e0beb4f](https://github.com/atom-ide-community/atom-ide-base/commit/e0beb4f842a08f49caf7542a71a1f3e30a5217bb))

# [1.3.0](https://github.com/atom-ide-community/atom-ide-base/compare/v1.2.1...v1.3.0) (2020-09-26)

### Features

- add types entry to package.json ([73e62b8](https://github.com/atom-ide-community/atom-ide-base/commit/73e62b800d230e5f1732566c78a41b606f011d4b))
- move types to types folder ([3705c75](https://github.com/atom-ide-community/atom-ide-base/commit/3705c75c3816a36abd08aada4adfc70c16e2098f))

## [1.1.1](https://github.com/atom-ide-community/atom-ide-base/compare/v1.1.0...v1.1.1) (2020-07-21)

### Bug Fixes

- format ([250e850](https://github.com/atom-ide-community/atom-ide-base/commit/250e85025e7ed05f67b0508fd5b8cf295124240e))

# [1.1.0](https://github.com/atom-ide-community/atom-ide-base/compare/v1.0.0...v1.1.0) (2020-07-21)

### Bug Fixes

- add description to package.json ([e94505a](https://github.com/atom-ide-community/atom-ide-base/commit/e94505a63658299103c931b3f83baa64c7a13cd6))
- add readme about the types ([18eb027](https://github.com/atom-ide-community/atom-ide-base/commit/18eb027b6eba2e0ceffba3f0ca27a259ac35f088))
- add types scripts ([b99f92b](https://github.com/atom-ide-community/atom-ide-base/commit/b99f92bb0f01557989bde9ccf07b52341c034f85))
- rename index.d.ts ([7d2e5ed](https://github.com/atom-ide-community/atom-ide-base/commit/7d2e5ed91b894dee3934f8eb6ba7bd64be17a662))
- use normal typescript syntax ([fe40ec2](https://github.com/atom-ide-community/atom-ide-base/commit/fe40ec2d6c0a193899bb5d5308ab45ceb8498295))

### Features

- add npm release to allow using types ([806b9a5](https://github.com/atom-ide-community/atom-ide-base/commit/806b9a51f6aa39dfb417afc5c34bcfb3c1dfb912))

# 1.0.0 (2020-07-21)

### Bug Fixes

- deps installation ([7b7baa1](https://github.com/atom-ide-community/atom-ide-base/commit/7b7baa1032a70b5e67da75dc820fe27c637ec92a))
