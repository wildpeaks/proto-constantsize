# ConstantSize

VRML PROTO (based on `Script`) that emits a scale that makes an object appear
to have the same size regardless or its position (e.g. something far
should be much bigger than something near to appear the size from your point of view).

	EXTERNPROTO ConstantSize [
		exposedField  SFVec3f  translation
		exposedField  SFVec3f  scaleFactor
		eventOut      SFVec3f  scale
	] "proto.ConstantSize.wrl#ConstantSize"


-------------------------------------------------------------------------------

## Property `translation`

3D position of the object.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFVec3f`
 - Default Value: `0 0 0`


-------------------------------------------------------------------------------

## Property `scaleFactor`

Factor added to the resulting scale.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFVec3f`
 - Default Value: `1 1 1`


-------------------------------------------------------------------------------

## Event `scale`

Resulting scale to route to the Transform that contains the object.

Definition:
 - Field Type: `eventOut`
 - Data Type: `SFVec3f`


-------------------------------------------------------------------------------
