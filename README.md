# Expanded UE VR Template

Developed using UE 4.26

This is a fork of https://github.com/inugames/basic-vr that further expands and adds Oculus/SteamVR Home interactions and features

Original Unreal Forum thread: https://forums.unrealengine.com/development-discussion/vr-ar-development/1701223-vr-interaction-project-open-source

There is oculus-quest-config branch that can be used to generate apk to try out on quest (no performance test were done yet).

# All currently implemented features:

  - :heavy_check_mark: Locomotion with collisions (dynamic heigth) - locomotion using thumbstic (left controller)
  
  TODO: record gif

  - :heavy_check_mark: Teleportation - locomotion using teleportation (right controller)
  
![teleport](./gif/teleport.gif)

  - :heavy_check_mark: Turn in place - rotate character in place (right controller)
  
![rotation](./gif/rotation.gif)

  - :heavy_check_mark: Physics Hands - hands cannot pass through walls and interact with physic based objects
  
![physic_hands](./gif/physic_hands.gif)

  - :heavy_check_mark: IK Hands - IK on finger when interacting or picking up physics objects
  
![ik](./gif/ik.gif)

  - :heavy_check_mark: Physics pickup - picked up objects with calculated weigth that impacts hands, retains all collisions and interactions with physic based objects
  
![physics_objects](./gif/physics_objects.gif)

  - :heavy_check_mark: Attachable one hand objects - object that is attached to hand, retains all collisions and interactions with physic based objects with action
  
![attachable_object](./gif/attachable_object.gif)

![gun](./gif/gun.gif)

Planned features for future implementation:
  - :x: HMD collisions (RecRoom inspired)
  - :x: Two handed object pickup with action
  - :x: Hand gestures
  - :construction: Interactable objects (doors, drawers, buttons and levers)

:heavy_check_mark: finished
:x: not yet started
:construction: work in proggress


### Development

Want to contribute? Great!

You can take a task from planned features that isn't tagged started (or you don't see any branch with that task) and start working.


### Contributors

 - @inugames
 - @JJcherrycode

License
----

MIT

