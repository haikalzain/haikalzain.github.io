# Some notes on WebAssembly

I've been playing around with WebAssembly, and trying to what it is and why I should care. There's a ton of projects popping up around the ecosystem, such as binaryen, emscripten, wazero.

WebAssembly has shipped (link https://webassembly.org/) and companies are actually using it (figma, pdfasm)

WebAssembly promises to be faster and safer than javascript. 



## ASCII vs binary formats

Programming languages such as javascript are written in plaintext. That's great for programmers to code in but when you send it over the wire, you're actually wasting a lot of space.

Each character is a byte, which can represent 256 characters. In a format like javascript, we are only using &lt60 of these (a-z, A-Z, 0-10, a few special chars), so we are actually wasting 3 times the space.




// ascii table

If you look at the ascii table, each character

Conceptually a 