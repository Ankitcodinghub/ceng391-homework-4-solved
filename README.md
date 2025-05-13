# ceng391-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CENG391 Homework 4 Solved](https://www.ankitcodinghub.com/product/ceng391-homework-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92749&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CENG391 Homework 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Exercise 1 Image Processing and Feature Detection

Please do the following exercises by a single Python script named as src/detect and match.py. You may use OpenCV for feature detection and descriptor computation.

<ol>
<li>Detect SIFT interest points on the six images of the Golden Gate Bridge that are in the folder data.</li>
<li>Draw the SIFT interest points on each image and store the result- ing images in the same folder with names as sift keypoints i.png, where i is the image number.</li>
<li>Calculate SIFT descriptor matches between consecutive pairs of im- ages by brute force matching, for example between goldengate-00.png and goldengate-01.png, between goldengate-01.png and goldengate-02.png, and so on.</li>
<li>Draw these tentative correspondences on a match image and save the resulting images in the same folder with names as

tentative correspondences i-j.png, where i and j are image num- bers.</li>
<li>Save the SIFT interest points, descriptors, and tentative correspon- dences as text files in the same folder with names as sift i.txt and tentative correspondences i-j.txt.
1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 2 RANSAC

Please do the following exercises by a single Python script named as src/ransac.py. You may use OpenCV for homography computation with RANSAC.

<ol>
<li>Read the keypoints and tentative correspondences for each image pair and match them by RANSAC.</li>
<li>You may use RANSAC from OpenCV, implement RANSAC yourself for 10 bonus points.</li>
<li>Save the resulting homography matrices in files within the folder data with names such as h i-j.txt, where i and j are image numbers.</li>
<li>Do not forget about normalization and the final estimation over all inliers. You may optionally perform guided matching.</li>
<li>Draw and save the resulting final inlier correspondences in files in the data folder with names as inliers i-j.png and inliers i-j.txt.</li>
</ol>
Exercise 3 Basic Stitching

Please do the following exercises by a single Python script named as src/stitch.py. You may use OpenCV function warp perspective for im- age warping.

<ol>
<li>Stitch all the images by calculating a homography matrix from each image to one of the center images goldengate-02.png or goldengate-03.png and warping the images to this coordinate sys- tem.</li>
<li>Save the resulting image in the folder data named as panorama.png.</li>
<li>To blend multiple images just overwrite or average intensities of over- lapping pixels.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
