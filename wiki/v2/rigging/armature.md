# Armature

Armature is a collection of bones with a relation between them. These bones can be moved around and anything that they are attached to or associated with will move and deform in a similar way. You can think of an armature as of a real world skeleton. In butter, we will typically use the armature to define the robots degrees of freedom (most definitely it's motors).

## Creating a new Armature

- In object mode:
Under the 3D editor toolbar select `Add > Armature`

Blender will create a new armature and add a single bone to it. In order to edit an armature will will have to be in _Edit mode_, while you will be in it, the armature will always be in it's rest position.

## Bones

Bones are the base elements of armatures. There are to types of bones:

- Deforming Bones: Bones that will act a motors in your rig, their movement will influents the robot movement.
- Control Bones: Bones that will act as a controls, which will influent how other bones or objects react when they are transformed.

Bones are structured from three parts: root, body, and tip. the root and the tip defines the bone size and acts an it joints that can be connected to other bones. When selecting a bone, pay attention to the position you select it, select the joints when you want to manipulate them, and the body when you want to control the whole bone.

### Adding a Bone

There are three main ways to insert a new bone to an armature (in edit mode):
- Add:  Add a new bone to your armature.
Under the 3D editor toolbar select `Add > Single Bone`
- Extrude:  Extrude a new bone from a given bone.
Select a bone, then under the 3D editor toolbar select `Armature > Extrude` or right click a bone and then select _Extrude_
- Duplicate:  Duplicate a given bone.
Select a bone, then under the 3D editor toolbar select `Armature > Duplicate` or right click a bone and then select _Duplicate_

Note: when you extrude or duplicate a bone, the new bone will be parented to the bone you manipulated. We will explain what parenting mean in the next subsection.
You can read more about all the methods [here](https://docs.blender.org/manual/en/latest/animation/armatures/bones/editing/bones.html#add-menu).

### Parenting a Bone

Parenting is essentially the process of creating relationships between bones. for every bone on your rig you will have to decide two things: if it has to be parented to another bone, and if so, if it should be connected to it.

In order to parent one bone to another:
1. In _3D View_, select the bone and then its future parent (the order matters). 
2. Under the 3D editor toolbar select `Armature > Parent > Make Parent`. 
3. In the small _Make Parent_ menu that pops up, choose Connected if you want the child to be connected to its parent, else click on Keep Offset.

In order to disconnect parented bones:
1. In _3D View_, select both of the bone. 
2. Under the 3D editor toolbar select `Armature > Parent > Clear Parent`.

You can read more about parenting [here](https://docs.blender.org/manual/en/latest/animation/armatures/bones/editing/parenting.html).