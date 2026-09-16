# Maverix Generative Grid v07

v07 iterates directly on v06 using the latest annotated reference.

## Main change

Horizontal scaling is now row-based.

Each horizontal row gets one coherent animated X scale from noise. The row then repeats cells across the full width using that scaled cell width.

This allows:
- some rows to compress dramatically, down to 3–8% of normal width
- other rows to stay normal or wider
- different horizontal rhythms per row
- misaligned vertical divisions between rows, like the reference
- no gaps between cells
- no gaps between rows
- all four triangles to fill 100% of each cell

Optional Y scaling is also row-based and cumulative, so it cannot create gaps.

The original v06 center drift and alternating 0° / 90° / 180° / 270° cell rotation remain.

Files:
- index-06.html: preserved v06
- index-07.html: current version
