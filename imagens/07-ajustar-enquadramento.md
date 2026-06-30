# Ajustar enquadramento

**Categoria:** Imagens

**O que faz:** Altera proximidade da câmera e enquadramento mantendo identidade, estilo e consistência visual.

**TXT para copiar:** [abrir TXT](txt/07-ajustar-enquadramento.txt)

## Prompt

```text
{
"task": "camera_angle_and_distance_adjustment_only",
"analysis": {
"original_camera_angle": "eye-level, straight-on toward the seated subject on the bench",
"original_camera_distance": "medium distance, framing from approximately upper thighs to head",
"original_framing_description": "medium seated portrait with torso, arms, and part of the legs visible, subject
centered against a natural background"
},
"requested_adjustment": {
"new_camera_angle": "maintain the same eye-level, straight-on angle with no tilt or lateral shift",
"new_camera_distance": "significantly closer to the subject",
"zoom_change_description": "camera moved forward to create a tight upper-body framing, capturing only
from the upper chest to the top of the head, with the face becoming the dominant element in the frame while
preserving natural proportions"
},
"locks": {
"identity_locked": true,
"pose_locked": true,
"expression_locked": true,
"clothing_locked": true,
"environment_locked": true,
"lighting_locked": true,
"style_locked": true
},
"constraints": {
"must_keep": ["all visual elements identical except camera angle and distance","no proportional
distortion","natural photographic perspective"],
"must_avoid": ["cropping instead of true camera movement","changing subject size unnaturally","introducing
new visual elements"]
}
}
```
