# mach-math

<p>
  <a href="https://github.com/briar-systems/mach-math/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-math/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-math?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for vector-space math, starting with 4x4 matrices and quaternions.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.math]
git = "https://github.com/briar-systems/mach-math"
ref = "branch/dev"
```

Then bind the library in a source file:

```mach
use math;
```

Modules: `math.mat4` (4x4 matrices), `math.quat` (quaternions).


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
