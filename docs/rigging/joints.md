# Joints

In Blender we will model robot joints using bones. Typically a joint mean a motor, or an object that have the ability to move.

## Coordinate System

When creating a new joint, it is mandatory to set its coordinate system to XYZ Euler.
Typically, motors can only rotate in single axis, hence there in no risk of having a gimbal lock when using euler coordinate system. Therefor, we choose to use euler coordinate system over the robust but complicated quaternion coordinate system.

## Adding a Joint

Adding a joint is as simple as adding a bone to your rig with the following exceptions:

1. A joint most use XYZ Euler coordinate system.
2. A Joint most have only single free axis, meaning, you most lock all the axis except the axis that the motor spin on. 

## Special Joints

Here we will describe how to create different types of joints using bones. You can always use what ever technics the suited you best.

### Regular Motor

### Geared Motor

### Lead Screw

### Linear Rail

### Wire Driven

#### Rigid Wire

#### Flexible Wire