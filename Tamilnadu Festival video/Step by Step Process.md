# 🎬 Tamil Nadu Village Festival – AI Image & Video Generation

This project demonstrates how to generate **cinematic AI images and videos** of a **Tamil Nadu village temple festival** using prompt engineering.

The workflow uses:

* **Google Nano Banana** → Image Generation
* **Google Flow (Powered by Google Neo)** → Text-to-Video Generation

The generated visuals depict a **traditional village festival scene** including:

* Giant Wheel
* Temple Chariot (Ther)
* Columbus Ride
* Mini Rollercoasters
* Children's Train Rides
* Traditional Festival Food Stalls

---

# 🧰 Tools Used

| Tool                         | Purpose                     |
| ---------------------------- | --------------------------- |
| **Google Nano Banana**       | AI Image generation         |
| **Google Flow (Google Neo)** | AI Text-to-Video generation |

---

# 🪄 Workflow Overview

The workflow followed in this project:

1. Create **cinematic prompts using the SCALE framework**
2. Generate **festival images** using **Google Nano Banana**
3. Select **Start Image** and **End Image**
4. Use **Google Flow Text-to-Video**
5. Generate short **20–30 second cinematic video**
6. Combine clips if multiple scenes are required

---

# 📐 SCALE Prompt Framework

The prompts are structured using the **SCALE framework**.

| Element | Meaning     |
| ------- | ----------- |
| **S**   | Scene       |
| **C**   | Characters  |
| **A**   | Action      |
| **L**   | Lighting    |
| **E**   | Environment |

This helps produce **stable cinematic AI outputs**.

---

# 🖼 Image Generation Prompts (Nano Banana)

## Prompt 1 — Temple Festival Scene

### SCALE Breakdown

| Element     | Description                              |
| ----------- | ---------------------------------------- |
| Scene       | Tamil Nadu village temple festival       |
| Characters  | Villagers, families, children            |
| Action      | People walking around festival           |
| Lighting    | Golden sunset                            |
| Environment | Temple chariot, giant wheel, food stalls |

### Prompt

```text
Cinematic wide scene of a vibrant Tamil Nadu village temple festival during sunset. A large decorated temple chariot (Ther) stands near the temple entrance surrounded by villagers wearing traditional clothing. A colorful giant wheel slowly turning in the background, Columbus ride swinging with bright lights, small mini rollercoaster and children's toy train ride nearby. Festival food stalls selling sweets, snacks, and sugarcane juice line the street. Colorful festival flags and lights hang across the street. Warm golden sunset light mixes with glowing festival lights creating a lively atmosphere. Ultra detailed, cinematic lighting, realistic textures, stable objects, wide angle village festival view.
```

Output Image Example

```
festival_scene_start.png
```

---

## Prompt 2 — Festival Amusement Area

```text
Colorful Tamil Nadu village festival amusement area filled with joyful activity. A bright giant wheel rotating slowly above the crowd, a Columbus ride swinging high with flashing carnival lights, mini rollercoasters with children laughing, and a small colorful toy train carrying kids around a circular track. Families walking around enjoying snacks from traditional street food stalls selling murukku, cotton candy, and bajji. The area is decorated with colorful lights, festival banners, and lanterns. Evening sky turning deep orange and purple while carnival lights glow vibrantly. Cinematic festival atmosphere, high detail, vibrant colors, realistic crowd movement, stable environment.
```

Output Image Example

```
festival_rides_scene.png
```

---

## Prompt 3 — Night Festival Temple Scene

```text
Nighttime Tamil Nadu village temple festival glowing with colorful lights and celebration. A beautifully decorated temple chariot (Ther) illuminated with traditional lamps near the temple entrance. In the background a giant wheel shining with rainbow lights rotates slowly above the festival crowd. A Columbus ride swings dramatically while a mini rollercoaster and children's toy train run nearby filled with excited kids. Food stalls selling dosa, bajji, sweet corn, and cotton candy line the festival street. Ultra realistic cinematic night lighting, vibrant colors, high detail festival environment.
```

Output Image Example

```
festival_night_scene.png
```

---

# 🎥 Video Generation Using Google Flow

Google Flow allows **Text-to-Video generation** using:

* Start Image
* End Image
* Cinematic Video Prompt

Currently Flow supports **only 2 control images**.

---

# 📽 Method 1 — Multi Clip Generation (Recommended)

Generate multiple clips and combine them.

### Clip 1

Start Image

```
festival_scene_start.png
```

End Image

```
festival_rides_scene.png
```

Scene

```
Temple festival → Amusement rides
```

---

### Clip 2

Start Image

```
festival_rides_scene.png
```

End Image

```
festival_night_scene.png
```

Scene

```
Amusement rides → Night temple festival
```

---

# 🎬 Cinematic Video Prompt (Google Flow)

Use the following prompt when generating the video.

```text
Ultra cinematic Tamil Nadu village temple festival video during evening celebration. A massive decorated temple chariot stands near the temple entrance surrounded by villagers in colorful traditional clothing. A giant wheel rotates slowly above the crowd while a Columbus ride swings with glowing lights. Children enjoy toy train rides and small rollercoasters while families walk through festival food stalls selling cotton candy, bajji, murukku and sugarcane juice. The camera slowly moves through the festival capturing vibrant lights, rides, and joyful celebration. Warm golden sunset light transitions into glowing festival lights creating a magical atmosphere. Motion remains smooth and stable with consistent objects and environment. Cinematic lighting, realistic crowd movement, vibrant colors, ultra detailed festival scene.
```

---

# ⚙ Steps to Generate Video in Google Flow

1. Open **Google Flow**
2. Select **Text to Video Creation**
3. Upload the **Start Image**
4. Upload the **End Image**
5. Paste the **Video Prompt**
6. Click **Generate**
7. Wait for AI rendering
8. Download the generated video

---

# 📹 Final Video Story Flow

The generated clips create the following cinematic sequence:

```
Temple Festival Opening
        ↓
Amusement Ride Area
        ↓
Night Temple Festival Celebration
```

This creates a **natural cinematic story progression** similar to a **festival documentary or movie scene**.

---

# 💡 Tips for Better AI Video Results

* Use **highly descriptive prompts**
* Mention **camera movement**
* Specify **lighting and atmosphere**
* Avoid prompts that cause objects to appear suddenly
* Keep **objects consistent**
* Add stability instructions like:

```
Motion remains smooth and stable with no sudden object changes.
```

---

# 🚀 Summary

Using **prompt engineering + AI generation tools**, we can create:

* Cinematic **festival images**
* Story-based **AI generated videos**
* Realistic **Tamil Nadu cultural scenes**

Tools used:

* **Google Nano Banana**
* **Google Flow (Google Neo)**

This demonstrates how **structured prompts and AI tools can create cinematic visual storytelling**.
