# GrabCut Segmentation on Humerus Xray images

### Process:
1. Get contours
2. fit rectangle on the contours
3. apply grabCut to segment

### Sample outputs:
Had issues with some images where mask is seen as bacground and not foreground <br>

<table align="center">
  <tr>
    <td align="center">Original</td>
    <td align="center">Output</td>
  </tr>
  <tr>
    <td><img src="https://github.com/ronocara/grabCut_segmentation/blob/f97c5285d8aa87ac8314083111d0ceb8760bd16a/sample%20images/image5.png" width="200"></td>
    <td><img src="https://github.com/ronocara/grabCut_segmentation/blob/f97c5285d8aa87ac8314083111d0ceb8760bd16a/grabCut_outputs/image5.png" width="200"></td>
  </tr>
    <tr>
    <td><img src="https://github.com/ronocara/grabCut_segmentation/blob/2d5e8ad5250b211b703867df9b39707a05d8eb78/sample%20images/MURA-v1.1-train-XR_HUMERUS-patient02804-study1_positive-image2.png" width="200"></td>
    <td><img src="https://github.com/ronocara/grabCut_segmentation/blob/2d5e8ad5250b211b703867df9b39707a05d8eb78/grabCut_outputs/MURA-v1.1-train-XR_HUMERUS-patient02804-study1_positive-image2.png" width="200"></td>
  </tr>
</table>



