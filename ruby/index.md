# Index for Ruby

## Here you will found all the documented library with examples

## Functions :

### Drawing primitives

[.draw_line(x1, y1, c1, x2, y2, c2, z = 0, mode = :default) ](ruby/_.md) void
####Draws a line from one point to another—inconsistently.
[.draw_quad(x1, y1, c1, x2, y2, c2, x3, y3, c3, x4, y4, c4, z = 0, mode = :default) ](ruby/_.md) void
####Draws a quad (actually two triangles).
[.draw_rect(x, y, width, height, c, z = 0, mode = :default) ](ruby/_.md) void
####Draws a rectangle (actually a quad, or two triangles).
[.draw_triangle(x1, y1, c1, x2, y2, c2, x3, y3, c3, z = 0, mode = :default) ](ruby/_.md) void
####Draws a triangle.

### Manipulating the current drawing context

[.clip_to(x, y, w, h) { ... }](/ruby/clip_to.md) ⇒ void
#### Masks the drawing area inside the block.

[.flush](/ruby/flush.md) ⇒ void
#### Flushes all drawing operations to OpenGL so that Z-ordering can start anew.

[.gl(z = nil) { ... }](/ruby/gl.md) ⇒ void
#### Runs the block in a clean OpenGL environment.

[.record(width, height) { ... }](/ruby/record.md) ⇒ Gosu::Image
#### Records all drawing operations inside the block as a reusable “image”.

[.rotate(angle, around_x = 0, around_y = 0) { ... }](/ruby/rotate.md) ⇒ void
#### Rotates all drawing operations inside the block.

[.scale(scale_x, scale_y, around_x, around_y) { ... }](/ruby/scale.md) ⇒ void
#### Scales all drawing operations inside the block.

[.transform(m0, m1, m2, m3, m4, m5, m6, m7, m8, m9, m10, m11, m12, m13, m14, m15) { ... }](/ruby/transform.md) ⇒ void
#### Applies a free-form matrix transformation to everything drawn in the block.

[.translate(x, y) { ... }](/ruby/scale.md) ⇒ void
#### Offsets all drawing operations inside the block.
