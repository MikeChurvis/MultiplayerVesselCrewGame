# Toolchain Candidates

## Client

AKA the player's frontend. This needs to handle inputs, render data, and send player data to wherever it needs to go.

| Tool | Pros | Cons |
| - | - | - |
| Defold | - Great tooling and support<br>- Specializes in 2D/2.5D games | - I'm rusty with Lua<br>- I've never used it before
| Phaser | - Uses JS, supports TS<br>- I can use HTML/CSS/JS for the UI<br>- Specializes in 2D games<br>- Plenty of tutorials<br>- I can use most of the web APIs that I'm already familiar with | - I've never used it before<br>- Sparse editing tools
| Godot | - GDScript is similar to Python<br>- The editor is full-featured yet lightweight<br>- Large community with good support and many tutorials | - I've never used it before
| Unity | - I've used it before<br>- Targets a wide variety of platforms | - I'm rusty with C#<br>- Unity had(has?) a habit of making your DX hell if you didn't do things "the Unity way"<br>- Has a history of poor performance on web builds, even for 2D games<br>- Unity is an extremely heavyweight editor, and my main workstation for this project is a lower-midline laptop

## Server

This needs to handle player authentication, sessions, broker connections, store and retrieve game metadata, and possibly validate game state (serverside anti-cheat?)

| Tool | Pros | Cons |
| - | - | - |
| Django | - I know it very well<br>- Uses Python<br>- Flexible use case<br>- Good admin tools out-of-the-box | - Not really specialized for this kind of work.<br>- Default project scaffolding includes a bunch of stuff I won't need (this is a trivial issue)
| Flask/FastAPI | - Uses Python<br>- Flexible use case, arguably even moreso than Django | - I've only used them once