# lungs-image-segmentation
A bit of practice with image segmentation on lungs' x-ray dataset.

## Current status
I'm using the U-Net network as it was developed for biomedical image segmentation. The results are acceptable for me as it was fast prototyping. The network creates masks which cover most of the lungs' area and sometimes a bit of random part of x-ray.

## Further improvements
- figure out how to restrict mask to the continuous closed area — it may help with mask consistency
- try different model topologies
