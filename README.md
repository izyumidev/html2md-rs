> [!CAUTION]
> This project is still in development and not ready for use. If you want to contribute, feel free to open an issue or a pull request. Leave a star if you like the project.

# html2md-rs

Parses HTML and converts it to markdown.

## Usage

```rust
use html2md_rs::{parser::parse_html, to_md::to_md};

fn main() {
    let html = "<h1>Hello, World!</h1>";
    let parsed = parse_html(html);
    let md = to_md(&parsed);
    println!("{}", md);
}
```

## Supported HTML tags

Check the supported HTML tags [here](./src/structs.rs).

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
