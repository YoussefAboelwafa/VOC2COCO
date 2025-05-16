# VOC2COCO
Convert PASCAL-VOC annotations in XML to COCO annotations in JSON
![0_SDIluFvFN8d6Nj_K](https://github.com/user-attachments/assets/a3b4b998-7e26-451d-bdf9-493187471fc9)

## Example usage:
```
python voc2coco.py \
  --ann_dir /path/PASCAL-VOC/Annotations \
  --ann_ids /path/PASCAL-VOC/ImageSets/Main/val.txt \
  --labels /path/labels.txt \
  --output /path/pascal_val_ann.json
```
