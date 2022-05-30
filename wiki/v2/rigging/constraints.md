# Constraints

Constraints are a way to control an object’s properties (e.g. its location, rotation, scale).
There are two main types of constrains:
* Static constrains - plain constant values (A.K.A "limit" constrains).
* Dynamic constrains - dynamic values that are retrieved from another object, called “target” (A.K.A "copy" constrains).

Constraints can be applied to Objects and Bones, and they work in combination with each other to form a Constraint Stack.

## Adding a Constraint

There are two main ways to add a new constraint to a bone / object (in edit mode):
- Menu:  Under the 3D editor toolbar select `Object > Constraint > Add constraint (with Targets)`.
- Tab:  In the Properties Editor select `Object constraint tab > Add Object Constraint` or `Bone constraint tab > Add Bone Constraint`.

## Removing a Constraint

There are two main ways to add a remove constraint to a bone / object (in edit mode):
- Menu:  Under the 3D editor toolbar select `Object > Constraint > Clear Object Constraints`.
- Tab:  In the Properties Editor click on the "X" button in the relevant constraint [header](https://docs.blender.org/manual/en/latest/animation/constraints/interface/header.html
).

You can read more about constraints [here](https://docs.blender.org/manual/en/latest/animation/constraints/index.html).