# QuixelBridgeBlender

Updates to the Quixel Bridge Blender plugin script to support Blender versions 4.1+

Blender updated internal naming of some texture key properties which broke the import script for Bridge, this is a hack to get it working again.

Overwrite your existing file (or make a backup first). To get it working, I had to put it in Blender startup C:\Users\<username>\AppData\Roaming\Blender Foundation\Blender\4.x\scripts\startup\MSPlugin but YMMV.

https://blender.stackexchange.com/questions/314746/keyerror-bpy-prop-collectionkey-key-specular-not-found link to here for pointing me in a direction.
