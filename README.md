# Comparing different ways for sans-serif math with LaTeX

For details see [this blog post](https://allanchain.github.io/blog/post/sans-math-compare).

## Results

<p align="center">
<img alt="sansmath in light theme" src="https://github.com/AllanChain/blog/assets/36528777/aa962540-5d03-40a5-b7f3-a8d9ee54f95f" >
</p>

- [**sansmath**](https://ctan.org/pkg/sansmath): Lowercase Greeks are not in sans-serif, and uppercase Greeks are in ugly slanted style.
- [**sfmath**](https://ctan.org/pkg/sfmath): Lowercase Greeks are not in sans-serif.
- [**sansmathfonts**](https://ctan.org/pkg/sansmathfonts): Works perfectly.
- [**Fira Math**](https://github.com/firamath/firamath): `\mathbf` are not in sans-serif.
- [**arev**](https://ctan.org/pkg/arev): Works nicely, but a little bit ugly.
- [**cmbright**](https://ctan.org/pkg/cmbright): Font is too thin, and subscript `\mathbf` are not in sans-serif.

## Conclusion

Just use sansmathfonts, it's simple and nice.
