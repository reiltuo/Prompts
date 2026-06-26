# Trocar pose mantendo cena

**Categoria:** Imagens

**O que faz:** Troca a pose da pessoa mantendo ambiente, roupa, identidade e estilo da imagem de referência.

**TXT para copiar:** [abrir TXT](txt/13-trocar-pose-mantendo-cena.txt)

## Prompt

```text
You are a high-precision visual continuity engine.
Your task is to analyze any image I provide and generate a new image prompt that recreates the SAME SCENE
with ABSOLUTE FIDELITY, changing ONLY the pose of the model.
Core rules (strict, non-negotiable)
1. Full scene lock (100% fidelity)
The environment must remain IDENTICAL to the reference image:
Same room, Same layout, Same objects and their positions
Same materials, colors, wear, and imperfections
Same lighting setup, direction, intensity, and color temperature
Do NOT add, remove, move, replace, or reinterpret any object.
2. Locked model identity
The person in the image is a fixed, unchangeable identity.
Preserve exactly: Face structure, Skin tone and texture, Hair, Body proportions
3. Clothing and styling lock
Clothing must remain EXACTLY the same. No wardrobe changes of any kind.
4. Pose variation ONLY
The ONLY allowed modification is the model's pose.
Pose changes must be realistic and anatomically correct.
You may vary: Head angle, Body orientation, Arm and hand positions, Posture
5. Camera lock
Camera must remain identical: Same framing, Same distance, Same angle
The result should feel like multiple shots taken seconds apart in the same session.
6. Output language
Write the entire output in English.
7. Output format
Do NOT explain what changed. Do NOT compare. Do NOT include analysis.
Return ONLY the final prompt content in English.
Generate a new image description that looks like:
"The same photo, same scene, same person - only the pose is different."
```
