---
name: realistic-id-photo
description: Generate photorealistic, unretouched Chinese ID-style portrait prompts with a strong anti-airbrush, anti-AI-look bias. Use when the user wants a lifelike ID photo / document headshot that looks like a real phone photograph — no beautify, no soft-skin, no studio look, no digital perfection. The user supplies only the subject description inside { }.
compatibility: Portable to any agent that can read local files — no external API calls, proprietary runtime, or required tools.
---

# Realistic ID Photo Prompt

## Usage

The template has exactly one free-form slot, `{ }`. The user writes the subject in the braces; everything else is fixed and must be emitted verbatim.

1. Take the user's subject description and paste it into the `{ }` slot.
2. Keep every fixed line unchanged (preserve the order, wording, and structure).
3. Output the full prompt, then the separate negative prompt, in English.

## Prompt Template

{ }，white background ID photo, natural and relaxed expression, not a posed shot, not a portrait/fine-art photo session, not an influencer selfie. Face not completely symmetrical, nose bridge slightly not straight, nostrils slightly different in size, fine lines at the corners of the mouth, chin slightly receded, face not a standard oval shape.

Real skin, not airbrushed, slight redness around the nostrils, fine visible pores on the cheeks, minor acne marks in places, faint fine lines and mild dark circles under the eyes, oily sheen on the T-zone, slight reflection on the forehead, small blemishes on the chin, uneven skin tone, fine vellus hair on the cheeks, real surface texture with natural unevenness, not a smooth plastic surface.

Lighting not sophisticated, no added lighting, no soft focus.

Phone-photo quality, slight compression artifacts, slight noise, slight blur, slight hand shake, slight motion blur, slight chromatic aberration at the lens edges, colors not very saturated, white balance slightly warm, low contrast, ordinary everyday photo, real camera photo, not retouched, no beauty filter, not commercial photography, not a high-end studio shoot.

Negative prompt: AI face, AI-generated look, cartoon, anime, illustration, painting, 3D render, CG, plastic skin, rubber face, ceramic skin, glass eyes, vacant gaze, over-airbrushed, flawless skin, smooth skin, perfect facial features, uniform features, influencer face, beauty filter, liquify/retouch traces, over-sharpened, ultra-sharp eyes, overexposed highlights, pitch-black shadows, fake pores, fake texture, retouched portrait photos, magazine cover, perfect symmetry, artistic beautification, oil painting, 2D/anime, deformed facial features, deformed fingers, over-clean, over-smooth, commercial lighting, high-end studio lighting, soft focus, creamy skin, cold pale skin, perfect face shape, elaborate makeup
