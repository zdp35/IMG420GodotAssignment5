# IMG420GodotAssignment5

Shader Explanation

The shader gives the particles a moving, glowing look. It makes each particle shift slightly from side to side in a wave pattern that changes over time. At the same time, the color blends smoothly from one shade at the top to another at the bottom. The soft edges make each particle fade out instead of having a hard border. Together, these effects make the particles look alive and in motion, even though the shader only affects their color and texture, not their movement.

Physics Properties

The chain is built from several connected pieces that move like a rope. Each piece is joined with a spring-like connection that keeps the parts together but lets them swing and stretch a little. The settings for stiffness and damping were chosen so the chain moves naturally—tight enough to hold its shape, but soft enough to sway smoothly under gravity and when the player bumps into it.

Raycast Detection

The laser system constantly sends out an invisible line that checks for objects in front of it. A colored beam shows where the laser reaches, and it changes length if it hits something. When the player walks through the beam, it flashes red and prints an alarm message before returning to normal after a short delay. This shows how a raycast can be used to detect collisions and trigger visual feedback in real time.
