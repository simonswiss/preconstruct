# preconstruct

## 0.0.74
### Patch Changes

- [f79b195](https://github.com/preconstruct/preconstruct/commit/f79b195) - Change import path generated in TypeScript declarations

## 0.0.73
### Patch Changes

- [2e01590](https://github.com/preconstruct/preconstruct/commit/2e01590) [#60](https://github.com/preconstruct/preconstruct/pulls/60) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Stop adding a postinstall script with preconstruct dev in preconstruct init. This was causing problems with single package repos so it's being removing for now.

## 0.0.72
### Patch Changes

- [cd0979f](https://github.com/preconstruct/preconstruct/commit/cd0979f) - Change TS declaration filename

## 0.0.71
### Patch Changes

- [ac2eb8a](https://github.com/preconstruct/preconstruct/commit/ac2eb8a) [#59](https://github.com/preconstruct/preconstruct/pulls/59) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add typescript declaration generation

## 0.0.70
### Patch Changes

- [423a8b6](https://github.com/preconstruct/preconstruct/commit/423a8b6) [#56](https://github.com/preconstruct/preconstruct/pulls/56) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add checks that imported modules in a package are inside of the package's directory
- [8b6e051](https://github.com/preconstruct/preconstruct/commit/8b6e051) [#58](https://github.com/preconstruct/preconstruct/pulls/58) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Fix entrypoints package.json creation
- [4a9de88](https://github.com/preconstruct/preconstruct/commit/4a9de88) [#57](https://github.com/preconstruct/preconstruct/pulls/57) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add .d.ts file so that TS types can be found when built

## 0.0.69
### Patch Changes

- [802fec0](https://github.com/preconstruct/preconstruct/commit/802fec0) [#54](https://github.com/preconstruct/preconstruct/pulls/54) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Replace flow file that re-exports source contents with a symlink in dev command. This fixes the problem where if you added or removed the default export of an entrypoint source file, you would have to run `preconstruct dev` again.
- [b351218](https://github.com/preconstruct/preconstruct/commit/b351218) [#55](https://github.com/preconstruct/preconstruct/pulls/55) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Add support for TypeScript resolving types with dev command

## 0.0.68
### Patch Changes

- [9022265](https://github.com/preconstruct/preconstruct/commit/9022265) - Set fields in a better order

## 0.0.67
### Patch Changes

- [b22d4e1](https://github.com/preconstruct/preconstruct/commit/b22d4e1) - Fix init command prompting incorrectly for UMD builds
- [0a9b9d7](https://github.com/preconstruct/preconstruct/commit/0a9b9d7) - Remove aliases export, this is now replaced with the dev command

## 0.0.66

### Patch Changes

- [698fe38](https://github.com/preconstruct/preconstruct/commit/698fe38) [#53](https://github.com/preconstruct/preconstruct/pulls/53) Thanks [@mitchellhamilton](https://github.com/mitchellhamilton)! - Move require hook into a package
