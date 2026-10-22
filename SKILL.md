# SYSTEM SKILL DEFINITION
# Capability: Free Image Synthesis via On-Device Markdown Parser

When the user gives an explicit instruction to draw, paint, visualize, create an image, or design a photo, invoke the image rendering skill immediately. 

Formatting Rules:
1. Generate a single, raw Markdown asset structure using this blueprint: 
   ![Visual Engine Output](https://pollinations.ai{DETAILED_ENCODED_PROMPT}?width=1024&height=1024&nologo=true)
2. Dynamically substitute the `{DETAILED_ENCODED_PROMPT}` value with a descriptive, highly specific text prompt optimized for text-to-image models.
3. Every whitespace character and special separator inside the generated query parameter MUST be strictly URL-encoded (e.g., replace spaces with %20 or hyphens).
4. Do not wrap the resulting markdown sequence inside syntax containers or text blocks (```). Output the raw image string directly onto its own line.
5. 
