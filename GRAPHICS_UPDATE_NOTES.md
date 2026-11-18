# Graphics-only update

This update improves the existing Three.js tower and enemy presentation without changing game balance or abilities.

## Visual changes
- Towers: added a machined base rim, anchor bolts, shared metallic trim, and a subtle trim pulse.
- Enemies: added procedural 3D articulated arms and legs for humanoid units, twig-arm motion for snowlings, and flapping wing meshes for runners and the dragon. Their limbs animate with movement and dash state.

## Preserved
- `js/config.js` was not changed.
- Tower/enemy types, stats, prices, damage, range, attack rate, abilities, pathing, targeting, and projectile logic were not intentionally changed.
- Existing Three.js renderer and game systems remain in place.

## Build
The web bundle was regenerated and Capacitor assets were synchronized. JavaScript syntax checks passed. An APK was not built in this environment because the Gradle wrapper distribution could not be downloaded; run the existing GitHub Actions workflow to produce the APK.
