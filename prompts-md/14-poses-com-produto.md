# Poses com Produto

**Categoria:** Imagem realista - analise e recomposicao

**O que faz:** Cria poses com produto mantendo campos travados e consistencia visual para geracao de imagem.

**TXT para copiar:** [14-poses-com-produto.txt](../prompts-txt/14-poses-com-produto.txt)

## Prompt

```text
{
"task": "universal_product_preservation_and_repose",
"input": {
"reference_image": true,
"note": "The reference image already contains the target product. Your job is to keep that product identical and
only change the pose/composition."
},
"core_rules": {
"priority": "product_fidelity_over_everything",
"do_not": ["redesign","stylize","beautify","optimize fit","change proportions","change materials","change color
tone","invent missing details"],
"object_rule": "Treat the product as an immutable object. The subject adapts to the product, never the opposite."
},
"step_1_auto_classification": {
"task": "Identify what the product is in the image.",
"output_fields": ["product_category","product_subtype","worn_or_held","key_visibility_zones"],
"examples": ["dress, glasses, jacket, bag, shoes, watch, jewelry, headphones"]
},
"step_2_product_lock": {
"task": "Extract a strict product lock description from the image to preserve identity.",
"lock_fields":
["silhouette_or_shape","dimensions_and_proportions","materials_and_texture","color_and_finish","construction_de
"constraint": "If any detail is uncertain, mark it as uncertain. Do not guess."
},
"step_3_generate_repose_prompt": {
"task": "Create a final image-generation prompt that keeps the product locked and changes only pose.",
"pose_policy": {
"goal": "professional model pose, fashion lookbook style",
"safe_pose_defaults": ["standing","weight shift to one leg","subtle hip elevation","relaxed shoulders","arms relaxe
or lightly bent"],
"limits": {
"max_torso_rotation_degrees": 10,
"allowed_deformation": "only natural gravity-driven behavior",
"avoid": ["sitting","walking","jumping","arms above shoulders","extreme twists"]
}
},
"camera_policy": {
"framing": "full body or three-quarter depending on product",
"lens": "no distortion, realistic perspective",
"focus": "product clarity and structure"
},
"output_requirements": {
"deliverable": "Return ONLY the final prompt text to generate the new image.",
"format": "FULL JSON prompt block, no commentary."
}
}
}
```
