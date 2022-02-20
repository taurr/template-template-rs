# template-template-rs

A [cargo-generate] template for a new [Rust] template!


## Tips'n'tricks

If the template is used on a regular basis, [cargo-generate] allows to setup favorite templates and default variables.

To do this, open or create the file `$CARGO_HOME/cargo-generate.toml`, insert this:
```toml
[favorites.template]
git = "taurr/template-template-rs"
```

After this, the template can be expanded using a simple:

```shell
cargo generate template
```

[Rust]:https://www.rust-lang.org
[cargo-generate]:https://github.com/cargo-generate/cargo-generate
