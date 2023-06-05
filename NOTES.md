 
# List of rust engines

https://blog.logrocket.com/5-rust-game-engines-consider-next-project/

## fyrox

Slick - works in browser.  fast iterative recompile.

https://github.com/FyroxEngine/Fyrox

Docs https://fyrox-book.github.io/


## Bevy

slick.  works in browser.

https://bevyengine.org/

Docs: https://bevyengine.org/learn/book/introduction/

Uses this low level gpu lib https://wgpu.rs/

A voxel project https://github.com/afonsolage/projekto

A loader for https://ephtracy.github.io/ MagicaVoxel files: https://crates.io/crates/bevy_vox 

How to optimize voxels for bevy https://stackoverflow.com/questions/66609344/how-can-i-draw-multiple10000-cubes-in-the-bevy-game-engine-for-my-3d-voxel-gam

AWESOME voxel lib for bevy: https://github.com/Game4all/vx_bevy which uses https://github.com/bonsairobo/block-mesh-rs 
A simple game made by forking vx_bevy https://github.com/alexiadltg/voxel-cataclysm

## voxelize

a browser based minecraftish server/client voxel engine lib

https://crates.io/crates/voxelize

docs https://docs.rs/crate/voxelize/latest

Realtime built-in multiplayer game play
Protocol buffers for fast voxel data transferral
Multi-threaded parallel chunk processing
Multi-stage world generation to exceed expectations
Fully integrated chat system with commands registry
Oriented bounding box (ORM) physics engine that works with any blocks
Custom block types and shapes with physics support
Entity with in-place collision detection and ECS built in
World data saving for consistent experiences
Robust event system for custom game events

build instructions from me
```
nvm install --lts
corepack enable
corepack prepare yarn@stable --activate
yarn install

update to latest protoc
delete yarn.lock per https://stackoverflow.com/questions/64722201/yarn-command-yarn-import-error-this-package-doesnt-seem-to-be-present-in-you

# not needed git checkout -b v8.35 5677e9ef95541258cdbc6d3c0a12f2009100f5cc

```


https://crates.io/crates/cargo-watch to automatically recompile on source changes

## Piston

seems very young/alpha.  has scripting language.  https://github.com/pistondevelopers/piston-tutorials

## nannou

very limited https://github.com/nannou-org/nannou

## veloren

super big and complex and impressive.  can't get debugging to work.  possibly go back to it someday.