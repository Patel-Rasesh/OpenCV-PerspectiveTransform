# Portrait of the cheque
Here, the expectation is to make a "cheque scanner"; transform the picture of a cheque (bank terminology), captured from different angles and with different rotations, to a front-facing image of the cheque (akin to its scanned copy).

This covers perspective transform of an image and contour detection in OpenCV.

Time spent: **6** hours spent in total

## Steps achieved

- [X] Able to approximate contour (with 4 sides) of a cheque
- [X] Successfully warp the image of a cheque using perspective transform of an image

## Screenshots of the execution

![image](https://user-images.githubusercontent.com/91232193/169592857-0639e66e-bb63-4af6-8c62-0502f0092226.png)

## Challenges faced 
(X mark indicates that they are resolved)

- [X] Determining length and width of the resultant image of the cheque
- [ ] For the input images where cheque is held in hands, or background of the image and the color of the cheque are similar, finding contours became extremely difficult task
