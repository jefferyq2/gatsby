# Changelog: `gatsby-adapter-netlify`

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

### [1.1.5](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.5/packages/gatsby-adapter-netlify) (2024-05-17)

#### Features

- allow dsg/ssr renders without access to datastore if it's not required [#38974](https://github.com/gatsbyjs/gatsby/issues/38974) [#38979](https://github.com/gatsbyjs/gatsby/issues/38979) ([326c89a](https://github.com/gatsbyjs/gatsby/commit/326c89aaa30edcd3d6e46e797a4b7bcec171b6f2))

### [1.1.4](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.4/packages/gatsby-adapter-netlify) (2024-04-10)

#### Bug Fixes

- handler generation on windows [#38900](https://github.com/gatsbyjs/gatsby/issues/38900) [#38929](https://github.com/gatsbyjs/gatsby/issues/38929) ([edaf016](https://github.com/gatsbyjs/gatsby/commit/edaf016906b593f0e028fa4a4e0b4ecc41cf1cc6))

### [1.1.3](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.3/packages/gatsby-adapter-netlify) (2024-01-25)

#### Bug Fixes

- add missing fs method rewrites to handle fetchRemoteFile in dsg/ssr engine [#38822](https://github.com/gatsbyjs/gatsby/issues/38822) [#38823](https://github.com/gatsbyjs/gatsby/issues/38823) ([c50e8f2](https://github.com/gatsbyjs/gatsby/commit/c50e8f2cd93898d9a483440ebd6eeeb492e73087))

### [1.1.2](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.2/packages/gatsby-adapter-netlify) (2024-01-23)

**Note:** Version bump only for package gatsby-adapter-netlify

### [1.1.1](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.1/packages/gatsby-adapter-netlify) (2023-12-19)

#### Bug Fixes

- update remote url docs [#38768](https://github.com/gatsbyjs/gatsby/issues/38768) [#38770](https://github.com/gatsbyjs/gatsby/issues/38770) ([5d6bb65](https://github.com/gatsbyjs/gatsby/commit/5d6bb65f1b1c93eaf5d9e01dfc9c8b37c9b09fea))

## [1.1.0](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.1.0/packages/gatsby-adapter-netlify) (2023-12-18)

[🧾 Release notes](https://www.gatsbyjs.com/docs/reference/release-notes/v5.13)

#### Features

- image and file cdn url generator adapter implementation [#38685](https://github.com/gatsbyjs/gatsby/issues/38685) [#38715](https://github.com/gatsbyjs/gatsby/issues/38715) [#discussion_r1414135797](https://github.com/gatsbyjs/gatsby/issues/discussion_r1414135797) [#38735](https://github.com/gatsbyjs/gatsby/issues/38735) [#38719](https://github.com/gatsbyjs/gatsby/issues/38719) ([4a780fb](https://github.com/gatsbyjs/gatsby/commit/4a780fbac717b1df337f156e2ac4b2da6478106b))
- support pathPrefix and trailingSlash options fix [#38666](https://github.com/gatsbyjs/gatsby/issues/38666) ([63e57cf](https://github.com/gatsbyjs/gatsby/commit/63e57cf3dd96083d219c09741a751206bb715a53))

#### Bug Fixes

- adapter use headerRoutes [#38652](https://github.com/gatsbyjs/gatsby/issues/38652) ([22c2412](https://github.com/gatsbyjs/gatsby/commit/22c24122f321d60011aec7daec86a1ccf89e994d))
- respect 'force' and 'conditions' properties on redirects [#38657](https://github.com/gatsbyjs/gatsby/issues/38657) ([48d311e](https://github.com/gatsbyjs/gatsby/commit/48d311e71f7ab6865b0615f6f291764b4b04a874))
- handle cases with large cached \_redirects and/or \_headers files [#38559](https://github.com/gatsbyjs/gatsby/issues/38559) ([db41d13](https://github.com/gatsbyjs/gatsby/commit/db41d1356c527cf4028142050978accd4abb1e9a))

#### Chores

- update dependency rimraf to ^5.0.5 [#38596](https://github.com/gatsbyjs/gatsby/issues/38596) ([37f2288](https://github.com/gatsbyjs/gatsby/commit/37f2288ee701d30d4d62ccb2f1d4487e7eb522b4))
- added logging for cache handling [#38654](https://github.com/gatsbyjs/gatsby/issues/38654) ([f642940](https://github.com/gatsbyjs/gatsby/commit/f642940579fb2c96c22868b2b40f0983feaef087))

### [1.0.4](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.0.4/packages/gatsby-adapter-netlify) (2023-11-21)

#### Features

- support pathPrefix and trailingSlash options fix [#38666](https://github.com/gatsbyjs/gatsby/issues/38666) fix [#38701](https://github.com/gatsbyjs/gatsby/issues/38701) ([1090558](https://github.com/gatsbyjs/gatsby/commit/1090558010c5e73de49d5987ab38d30165581c51))

### [1.0.3](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.0.3/packages/gatsby-adapter-netlify) (2023-11-03)

#### Bug Fixes

- adapter use headerRoutes [#38652](https://github.com/gatsbyjs/gatsby/issues/38652) [#38674](https://github.com/gatsbyjs/gatsby/issues/38674) ([8ae5702](https://github.com/gatsbyjs/gatsby/commit/8ae5702433e8ab68b2742ef92f9816fbc84dcfd0))

### [1.0.2](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.0.2/packages/gatsby-adapter-netlify) (2023-10-26)

#### Bug Fixes

- respect 'force' and 'conditions' properties on redirects [#38657](https://github.com/gatsbyjs/gatsby/issues/38657) [#38664](https://github.com/gatsbyjs/gatsby/issues/38664) ([c43080f](https://github.com/gatsbyjs/gatsby/commit/c43080f49fe54022be141855db4e56d98398338c))

#### Chores

- added logging for cache handling [#38654](https://github.com/gatsbyjs/gatsby/issues/38654) [#38660](https://github.com/gatsbyjs/gatsby/issues/38660) ([4a76878](https://github.com/gatsbyjs/gatsby/commit/4a768788c91298317ff40388c288564efc52b763))

### [1.0.1](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.0.1/packages/gatsby-adapter-netlify) (2023-09-22)

#### Bug Fixes

- handle cases with large cached \_redirects and/or \_headers files [#38559](https://github.com/gatsbyjs/gatsby/issues/38559) [#38564](https://github.com/gatsbyjs/gatsby/issues/38564) ([56ddcce](https://github.com/gatsbyjs/gatsby/commit/56ddccecb8df4b04af956df9c83b7058d8008b26))

## [1.0.0](https://github.com/gatsbyjs/gatsby/commits/gatsby-adapter-netlify@1.0.0/packages/gatsby-adapter-netlify) (2023-08-24)

[🧾 Release notes](https://www.gatsbyjs.com/docs/reference/release-notes/v5.12)

**Note:** Version bump only for package gatsby-adapter-netlify

<a name="before-release-process"></a>
