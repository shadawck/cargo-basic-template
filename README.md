# {{project-name}}

## Overview
**A brief description of the project !**

## Documentation
- [Examples Repository](./examples)
- [API Documentation](https://docs.rs/{{project-name}})

{% if crate_type == "bin" %}
## Installation

Using cargo : 
```sh
cargo install {{project-name}}
```

or from source :
```sh
cargo install --git https://github.com/{{gituser}}/{{project-name}}
```
{% endif %}
## Example

First, add the dependency to your `cargo.toml`:
```toml
[dependencies]
{{crate_name}} = "0.1.0"
```

**Add first example here !**

### More example
- [Simple](./examples/firstexample.rs)
- [Other example]()
- [An Other one]()
- ...

### License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.