# Quick start

Get from zero to a labeled dataset in a few minutes.

## 1. Create an account
Go to [trainox.ai](https://trainox.ai) and sign in. The free tier includes
1 GB of storage and up to 2,000 images, so you can try the full workflow
before paying for anything.

## 2. Create a project and a dataset
- Create a **project** for the problem you are solving (for example, "vehicles").
- Add a **dataset** inside it and upload your images.
- Define your **classes** (for example, `car`, `cat`). You can also add new
  classes later, right from the labeling screen.

## 3. Label your images
Pick the labeling mode that matches your task:

| Task | Mode |
|---|---|
| Object detection | Bounding-box labeling in the gallery labeler |
| Segmentation | Mask-first Segmentation Studio |

**Smart Select** is a SAM-based tool for segmentation. Click on an object, and
Trainox proposes a mask. Use **Add** and **Remove** points to refine it, then
assign a class.

<!-- ![Smart Select demo](../assets/smart-select.gif) -->

## 4. Speed up with auto-labeling
Run auto-label or auto-segment on a batch of images, then review the results
with keyboard shortcuts and move on to the next image automatically.

## 5. Search your dataset with text
Type a description such as "cat on top of a car" and find matching images
in your dataset.

<!-- ![Text search demo](../assets/text-search.gif) -->

## 6. Train and deploy
Train a model on your labeled data without managing any GPU infrastructure
or writing training code, then download the model artifact.

## Medical imaging
Trainox supports DICOM and NIfTI natively, so you can label medical data
without converting it first.

## Next steps
- [API reference](api.md)
- Questions or feedback: support@trainox.ai
