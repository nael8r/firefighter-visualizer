# firefighter-visualizer
A simple visualizer for solutions to intances of the firefighter problem on graphs

# Usage

`./view_ffp_sol.py -i  <input_file> -o <output_file>.mp4`

# Input file format

\<Number of vertices\>

\<Number of edges\>

\<Size of the set $B_{init}$\>

\<Elements of the $B_{init}$ set, space separated\>

\<Edges of the graph, onde per line, format: \<source\> \<destination\>\>

\<Vertices to be saved in the solution, space separated\>

See the file **sol1.txt** for an example.

# Dependencies:

**igraph** package for python 3: http://igraph.org/python

**ffmpeg**: https://ffmpeg.org/download.html

