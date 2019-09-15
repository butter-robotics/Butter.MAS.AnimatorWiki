# Importing

If you modeled your robot in a different CAD software, you can import you design to blender and continue from there.
In this section we will describe how to export you design from _Fusion 360_ and _Solidworks_ and import it into Blender.

There are two file types you should consider, OBJ and STL. Generally, STL file contains only an approximated mesh of you object, hence the file type will be smaller then OBJ. On the other hand, OBj file contains in addition the original object mesh and it texture, hence, it will be easier to modify it if you wish.  

You should always favour OBJ Mesh files when possible.

# Fusion 360

## Exporting OBJ Assembly

On your _Design_ workspace
- Navigate to Create > _Create Base Feature_
- Navigate to Modify > Mesh > _BRep to Mesh_
- Select the object you wish to export
- Press _OK_
- Right click on the Mesh body that you just created in the Model Browser (left panel)
- Select _Save As OBJ_
- Choose the file name and destination
- Press _Save_

## Exporting STL Assembly

- Right click on any component, component group, or body in the Model Browser (left panel)
- Select _Save As STL_
- Choose the file name and destination
- Press _Save_

# Solidworks

## Exporting OBJ Assembly

_This feature is currently not supported in Solidworks_

## Exporting STL Assembly

- Navigate to File > Save As
- Select STL (*.stl) for _Save as_ type
- Press _Save_

# Blender

## Importing OBJ Assembly

- Navigate to File > Import > Wavefront
- Select your OBJ file
- Press _Import OBJ_

## Importing STL Assembly

- Navigate to File > Import > Stl
- Select your STL file
- Press _Import STL_
