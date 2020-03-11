# Unity---GPU-Animation-Dots
Unity based gpu animation with DOTS support. 

Some simple hangups:
- Low Poly Only
- Bake Times can be long!

Potential Optimizations/Improvements:
- Texture Compression (Compress data based on local changes over time)
- Texture <> Vertex Lookup (The current setup has it so that vertexes are statically placed, with extra effort you could have the vertexes look in certain places on the texture, rather then in a row. This could allow more square texture's and less wasted space)
