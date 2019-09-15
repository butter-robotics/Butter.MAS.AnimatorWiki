# Modeling

The main mode we will use to model robots is edit mode. We will typically begin to modeling with a [primitive](https://docs.blender.org/manual/en/latest/modeling/meshes/primitives.html) mesh object and slowly combine them into large assembly's.

# Mesh Structure

Meshes are defined by three basic structures: vertices, edges and faces. 
- vertex: a single point or position in 3D space.
- edge: a straight line that connects two different vertices.
- face: the area (or polygon) defined between at least tree vertices.

    ![mesh structure](https://github.com/bennymeg/Butter.MAS.AnimatorWiki/raw/master/resources/modeling/mesh_structure.png "Mesh structure")

Manipulating these structures will modify the mesh shape.
You can read more about meshes structure [here](https://docs.blender.org/manual/en/latest/modeling/meshes/structure.html).

# Adding a Mesh

You can added a mesh object to you design in two main way:
- In object mode:
Under the 3D editor toolbar select add > mesh > select a mesh

    ![add mesh object mode](https://github.com/bennymeg/Butter.MAS.AnimatorWiki/raw/master/resources/modeling/add_mesh_obj.jpg "Add mesh - object mode")
- In edit mode:
Under the 3D editor toolbar select add > mesh > select a mesh

    ![add mesh edit mode](https://github.com/bennymeg/Butter.MAS.AnimatorWiki/raw/master/resources/modeling/add_mesh_edit.jpg "Add mesh - edit mode")

# Positioning a Mesh

In order to control an object position, follow the following steps:
- enter object mode
- select the manipulator from the left sidebar (i.e. move)
- select the object you wish to manipulate
- use the arrows to manipulate the object

    ![sidebar](https://github.com/bennymeg/Butter.MAS.AnimatorWiki/raw/master/resources/general/sidebar_obj.jpg "Sidebar")

# Manipulating a Mesh

In order to manipulate a mesh object you wil need to enter edit mode.
Editing a mesh is done by manipulating the mesh structure (vertices, edges and faces) position. It can be done by moving, rotating, transforming the mesh structure. You can always add more vertices and edges to your mesh to allow more degrees of freedom for manipulating the mesh. You can read more about editing meshes [here](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/index.html).