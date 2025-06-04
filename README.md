# VoxaCommunications-Backend
 
Compose files for VoxaCommunications' Central Servers. 

#### Usage
The average user will not need to host this, as this is the central service that is provided by VoxaCommunications. But if you are a developer, you may want to test. Here are the instructions on how to run this.

1. Create a `.env`, and populate it with the values found in `.env.example`
2. Clone `VoxaCommunications-Registry` and run the `build.sh` in it.
3. Make sure you have `docker` installed, and the `.env` correctly configured.
4. Run `docker compose up -d` to start the central services.

---
Support: `voxa@connor33341.dev`