# Clothing image workflow kit

A practical shot list and review checklist for preparing clothing images for virtual try-on. Maintained by the Collart AI team; this guide includes our own product.

## What this kit is for

Use the CSV templates to organize model photos, garment inputs, and review decisions before creating images for product listings, social posts, or ads. The templates work as a manual production checklist. They are not an API integration or an automated uploader.

- [Shot-list template](shot-list.csv): keep each outfit and intended output together.
- [Quality-review template](quality-checklist.csv): record visible defects and approval decisions.

## Prepare the inputs

1. Choose a model photo you have permission to use. Favor a clear, well-lit image with a pose that leaves the relevant clothing area visible. Keep the same model input when comparing outfit variants.
2. Photograph each garment separately. Make the silhouette, fabric, pattern, and important details easy to see. Avoid cropped sleeves, hidden hems, and distracting backgrounds.
3. Give assets stable names, such as `model-front-01.jpg`, `top-blue-01.jpg`, and `bag-tan-01.jpg`. Add those names to `shot-list.csv` before uploading.
4. Start with a simple outfit. Add accessories after checking the main garment. Changing one item at a time makes it easier to find the cause of an unexpected result.
5. Record the intended use and aspect ratio. Leave room for a product crop or ad caption when planning the composition.

## Example manual workflow in Collart

Open [Collart AI Clothes Changer](https://collart.ai/en/studio/ai-clothes-changer), select or upload a model, and add the clothing images. The current interface supports up to five clothing items or accessories and an optional prompt. It offers a single image or an image set using the same model.

Example direction:

> Create a clean product image using the supplied model and clothing references. Keep the full outfit visible against a simple background with soft, even lighting.

This is a prompt example, not a tested quality guarantee. The interface showed a generation cost of 5 credits when checked on October 28, 2026. Review the current cost in the product before generating; this guide does not promise free use.

## Review before publishing

Compare the output against the original garment, rather than judging only whether the image looks attractive. Use `quality-checklist.csv` to record a pass, a revision request, or a rejection.

| Check | What to inspect |
| --- | --- |
| Product identity | Color, print, logo, buttons, pockets, trim, and major seams |
| Shape and coverage | Sleeve length, neckline, hem, garment boundaries, and missing pieces |
| Model consistency | Face, pose, proportions, hands, and consistency across an image set |
| Contact areas | Hands near sleeves, straps near shoulders, bags, shoes, and overlapping layers |
| Output readiness | Crop, resolution, background, and unwanted marks or text |
| Rights and disclosure | Permission to use source assets and any required AI disclosure |

Generated images may alter product details. Do not publish an output that misrepresents the item being sold. Virtual try-on imagery does not establish garment measurements, physical fit, or sizing accuracy.

## Using the templates

Copy each CSV into your spreadsheet tool. Duplicate the example row for each planned image. Use local filenames or your team's asset identifiers; do not put customer names, private image URLs, or credentials in a public copy.

The example rows are illustrative planning data. They are not generated results or evidence that a particular outfit was tested. Keep the original photos and final approval records in your own asset system.

## Scope

This repository contains workflow documentation and CSV templates. It does not include model weights, generated fashion examples, customer images, or an unofficial Collart API. Questions about the product can be sent to the public contact address: marketing@collart.ai.
