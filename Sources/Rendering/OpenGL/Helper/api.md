vtkOpenGLHelper

Store the shaders, program, and ibo in a common place
as they are used together frequently.  This is just
a convenience class.

### program

The shader program

### VAO

The VertexArrayObject

### IBO

The index buffer object

### shaderSourceTime

The last time the shader source code changed

###  attributeUpdateTime

The last time  the attributes for the VAO were assigned
