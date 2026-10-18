# Changelog
## [0.1.1](https://github.com/OneByJorah/eduvex/compare/v0.1.0...v0.1.1) (2026-10-18)


### Bug Fixes

* **api:** add missing imports and fix model references in routes ([36297c8](https://github.com/OneByJorah/eduvex/commit/36297c8b111080ad93b78e4a2666a5962d27eca2))
* **api:** add missing SQLAlchemy ORM models and database initialization ([ea39787](https://github.com/OneByJorah/eduvex/commit/ea39787cd27d065acd91e19caa72f96571ae103a))
* **api:** add security headers middleware and CORS configuration ([52845e5](https://github.com/OneByJorah/eduvex/commit/52845e52731c9641dd8876037ff0b990b39f81ab))
* **audit:** add standard project files ([1e218ca](https://github.com/OneByJorah/eduvex/commit/1e218caf4858c831f966be396dd5b2325d455a51))
* **ci:** add reports/ to .gitignore and create j1.yaml ([0e9f4f2](https://github.com/OneByJorah/eduvex/commit/0e9f4f2e89a023384fb283bf90132fcd61297bbe))
* **compose:** add health checks, restrict port exposure, require credentials ([953065c](https://github.com/OneByJorah/eduvex/commit/953065c98cc9b1301f374ed2b80910c05ce91c42))
* **compose:** bind published ports to localhost only ([#12](https://github.com/OneByJorah/eduvex/issues/12)) ([bf3fb54](https://github.com/OneByJorah/eduvex/commit/bf3fb54daf415c4ce2d527aa1877386b41c247e7))
* **docker:** add non-root user and .dockerignore ([12789b0](https://github.com/OneByJorah/eduvex/commit/12789b0437235fbf5851a7ce07b3fb0050d09d48))
* **docker:** remove redundant pip install layers in Dockerfile ([641c6ef](https://github.com/OneByJorah/eduvex/commit/641c6efe8299b8e1749f41b49e3a288dc13d9bcc))
* **docs:** correct README database badge, tech stack, and architecture tree ([49b89b7](https://github.com/OneByJorah/eduvex/commit/49b89b74a10901ad15bea2c7ef95b55762f64a21))
* remove ollama pull from onboarding bootstrap script ([f4c6f49](https://github.com/OneByJorah/eduvex/commit/f4c6f49f7c16791aa5636397d9c740f005e0d70e))
* **security:** add credential warnings to compose.env.example ([15e89de](https://github.com/OneByJorah/eduvex/commit/15e89def8958e679112b4f8ba138ea5ff28f3c05))
* use quay.io/minio/minio image (Docker Hub minio/minio removed) ([#10](https://github.com/OneByJorah/eduvex/issues/10)) ([a733c71](https://github.com/OneByJorah/eduvex/commit/a733c71c1d0b0b27841877340b7f8851d8c3b601))

## [1.0.0] - 2026-07-07
### Added
- Initial release
- Dockerfile with multi-stage build
- .env.example with placeholder values
