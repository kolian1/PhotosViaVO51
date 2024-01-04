# PhotosViaVO51

# Desired feature list
VO51 based photos management app

## Desired features
1. Adding photos from:    
    1.   Local storage
    2.   Remote/cloud storage
3. Remove photos
    1.   From application
    2.   Application and Local storage
    3.   Application and Remote/cloud storage
5. Photos time
    1. Extract time information, using EXIF data
    2. Sort by time, ascending, descending
    3. Presetn photos on timeline
7. Photos location
    1. Extract location information, using EXIF data
    2. Tag photos with city, country using GPS location and map
    3. Present photos on top of map
1. Search objects in photo
    1.  Animals, cars, humans, hunam faces, buiding,
    2.  Tag photos with detceted items classes
1. Perform **obejct similairy** search to group
    1.   Humans based on human similairy
    2.   Human faces based on face similairy
    3.   Support contact import for face tagging
    4.   Objects based on object similairy
1. Perform **image similairy** to identify search
    2. Duplicates
    3. Near duplicates
9. Search **photos** based on combination of
    1. Date
    2. Location
    3. Free Text query- CLIP embeddings
    4. Multimodal search- text and visual search applied to photos
1. Search **objects** based on combination of
    1. Date
    2. Location
    3. Free Text query- CLIP embeddings applied to croppings
    4. Multimodal search- text and visual search applied to crops
1. Perform OCR search- is redudant due to CLIP?
2. Image enhancement using GenAI
