# Goal

Use [2025 Tanks Tutorial](https://youtu.be/cb5pTd8t-VQ) to checkout Unity 6 and an entry into [competition](https://play.unity.com/en/showcases/tanks-learn-along-challenge).

# Play

- This version: https://play.unity.com/en/games/cb7be0b0-09dc-4a6c-8efa-61d806be5be1/tanks-with-turrets
- Unity's version: https://play.unity.com/en/games/3772f049-9025-4536-8ede-d93718dace14/tanks

# Differentiators

What makes my version different than what's on the [Unity Learn Tanks Course](https://learn.unity.com/course/tanks-make-a-battle-game-for-web-and-mobile)?

1. Holding fire locks the turrets pointing direction. This allows for twin-stick-like shooting mechanics.
2. Holding fire auto-queues the next bullet
3. Bullets meshes auto-scale depending on TankShooting.cs MaxDamage
4. Tank Shooting adds greater than 0 projection of the moving direction of the source tank. Allows for faster bullets while turrent is aligned with treads.
5. Uses physics. (RigidBody.AddForce() replaces RigidBody.MovePosition())
6. TODO Add 3rd player defaulting to numpad 8456 and 0 to fire.
7. Renders meshes on mobile. [Thanks Grizmu](https://discussions.unity.com/t/official-unity-learn-event-learn-along-featuring-tanks-remastered-for-unity-6-on-unity-learn/1633869/33) (TODO: re-enable shadows for only PC) 

# Unity Play Desc (max 200 chars)

Differentiators:
- Holding fire locks where turret points
- Holding fire auto-queues the next bullet
- Tanks shoot faster along their moving velocity
