# Rust PNG writer sans dependencies

Hi! This is a PNG writer I wrote as a utility for a larger project where I preferred to minimise dependencies for simplicity's sake. It hope it serves as a good way of coming to grips with the PNG format!

This doesn't compress, and only supports RGBA. It is ideal for saving tiny pixel art images; for bigger ones maybe you should consider a proper png library.

To test, run:

    cargo run > test.png

Which should generate:

![Watermelon](https://raw.githubusercontent.com/chrishulbert/rust_png_write_sans_dependencies/main/test.png)

If you'd like to use this in your own project, feel free to simply copy it into your project rather than use cargo, as it's only about 150 LOC.
