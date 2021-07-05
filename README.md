Hi, I work on Rust stuff.

## 1.0 Crates

Here's some crates I work on that are 1.0 that you might like:
* [bytemuck](https://docs.rs/bytemuck) does data transmutation, including of owned values, references, and even slices.
* [tinyvec](https://docs.rs/tinyvec) has a vector which lives on the stack when it's small enough. This is distinct from the `arrayvec` and `smallvec` crates because it contains no unsafe code at all.
* [magnesium](https://docs.rs/magnesium) is a minimalistic iterator over an XML document. It handles enough that it can go over [gl.xml](https://github.com/KhronosGroup/OpenGL-Registry/blob/master/xml/gl.xml) and [vk.xml](https://github.com/KhronosGroup/Vulkan-Docs/blob/main/xml/vk.xml) just fine.
