**🌐 Project: Omni-Global (OG) Client-Side Injector v11.4
**
Omni-Global is a universal runtime environment designed for educational memory-mapping. It functions as a Layer 7 Interceptor, allowing users to force Physical Interaction Flags on any target entity within a shared session.

By mirroring local skeletal mesh animations through a Virtual Input Buffer, any move you perform (jumps, skill moves, or specific physics interactions) is calculated as a server-side action for the victim.

---

🌍 Global Compatibility
OG Injector works across all modern titles by scanning for the User32.dll input stack and the GameOverlayRenderer.dll memory space. It doesn't matter the game; if it has a Player ID, OG can hook it.

👻 The "Ghost-Move" Mechanic
The Physical Move exploit allows the injector to trick the server into thinking the target is performing the action.

Health Depletion: Forced jumps or skill-move frames will consume the target's stamina and halt HP-Regen.
Sync-Mirroring: What you do on your screen happens to them via Packet-Injection.

---

⌨️ Keybindings & GUI Instructions
Launch injector.exe: Ensure you have Administrative privileges for memory-read access.
Targeting: Enter the Target Username or Player ID into the GUI prompt.
Execution:
Press L + P to start the Physics Recorder.
Perform the moves you want the target to mirror.
Press N + P to end recording and commit the Skeletal-Sync.

---

📦 Repository Structure
/bin/ -> injector.exe
/lib/ -> global_hook.dll, phys_sync.dat
README.md -> (You are here)

---

📥 Installation
