# CustomSkinLoader (Celso's Skin API Fork)

This is a fork of the original CustomSkinLoader project with modifications to support **Celso's Skin API**.

---

## ✨ What’s Different

This fork modifies the default skin loading behavior to integrate with a custom skin API:

- 🔗 Connects to **Celso's Skin API**
- 🎨 Allows custom skins outside Mojang services
- ⚙️ Maintains compatibility with existing CustomSkinLoader features
- 🧩 Works with Fabric, Forge, and Vanilla setups

---

## 🚀 Features

- Load skins from a custom API endpoint
- Support for capes and extra textures (depending on API)
- Compatible with multiple Minecraft versions

---

## 🛠️ Installation

1. Download the latest build from **Releases**
2. Place the `.jar` file into your Minecraft `mods` folder
3. Launch Minecraft

---

## ⚙️ Configuration

Config files are generated on first run:

```
.minecraft/CustomSkinLoader/
```

Example configuration:

```json
{
  "loadlist": [
    {
      "type": "CustomSkinAPI",
      "root": "https://your-skin-api.example.com/"
    }
  ]
}
```

Replace the URL with your actual API endpoint.

---

## Build

```bash
./gradlew build
```

Output:

```
build/libs/
```

---

## 📦 Requirements

- Java 8 or higher  
- Gradle (wrapper included)

---

## 📁 Project Structure

- `Common/` → Shared logic  
- `Fabric/` → Fabric implementation  
- `Forge/` → Forge versions  
- `Vanilla/` → Mixin-based version  
- `buildSrc/` → Build logic  

---

## ⚠️ Notes

- This is a modified fork, not the original project  
- Behavior may differ from upstream  
- Report issues related to this fork here  

---

## 🙌 Credits

- Original project: CustomSkinLoader contributors  
- Modifications: Celso  

---

## 📄 License

Same as the original project unless stated otherwise.
