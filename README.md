# NBA STREET FIGHTER — Prototype 0.1

A playable 3D mobile fighting-game vertical slice with a Three.js court, procedural placeholder fighters, touch joystick, attack/block/dodge/special controls, CPU opponent, health bars, round timer, and restart flow.

## Important limitations
- Characters are procedural placeholder models, not final realistic assets or official NBA likenesses.
- Online multiplayer, accounts, story, Crew Wars, tournament progression, career saves, store, and monetization are not implemented yet.
- Three.js is loaded from jsDelivr CDN, so first load requires internet. The external engine may not be available offline.
- Uses original fictional court branding; not an official NBA product.

## Run on iPhone
1. Upload all files to a static host such as GitHub Pages, Netlify, or Cloudflare Pages.
2. Open the HTTPS URL in Safari and rotate to landscape.
3. Tap **ENTER THE BLACKTOP**.
4. Safari Share → Add to Home Screen to install the PWA.

## Controls
Touch joystick = move; ATTACK = basic attack; hold BLOCK to block; DODGE = sidestep; SPECIAL = stronger move with cooldown. For keyboard testing: arrow keys, J/Space attack, K special, L block, I dodge.

## Next milestone
Replace placeholder models with optimized, properly licensed rigged GLB models and animation, then tune combat feel and CPU behavior before adding the other modes and online architecture.
