# cs16-385-assignment-2--augmented-reality-with-planr-homographies-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs16-385-assignment-2-augmented-reality-with-planr-homographies-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94231&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS16-385 Assignment 2 –Augmented Reality with Planr Homographies Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
    
<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Augmented Reality with Planr Homographies

In this assignment, you will be implementing an AR application step by step using planar homographies. Before we step into the implementation, we will walk you through the theory of planar homographies. In the programming section, you will first learn to find point correspondences between two images and use these to estimate the homography between them. Using this homography you will then warp images and finally implement your own AR application.

Instructions

<ol>
<li>Integrity and collaboration: Students are encouraged to work in groups but each student must submit their own work. If you work as a group, include the names of your collaborators in your write up. Code should NOT be shared or copied. Please DO NOT use external code unless permitted. Plagiarism is strongly prohibited and may lead to failure of this course.</li>
<li>Start early! This is a much bigger assignment than assignment 1.</li>
<li>Questions: If you have any questions, please look at Piazza first. Other students may have encountered the same problem, and it may be solved already. If not, post your question on the discussion board. Teaching staff will respond as soon as possible.</li>
<li>Write-up: Your write-up should mainly consist of three parts, your answers to theory questions, resulting images of each step, and the discussions for experiments. Please note that we DO NOT accept handwritten scans for your write-up in this assign- ment. Please type your answers to theory questions and discussions for experiments electronically.</li>
<li>Please stick to the function prototypes mentioned in the handout. This makes verifying code easier for the TAs.</li>
<li>Submission: Create a zip file, &lt;andrew-id&gt;.zip, composed of your write-up, your Matlab implementations (including helper functions), and your implementations, re- sults for extra credits (optional). Please make sure to remove the data/folder, loadVid.m, warpH.m and any other temporary files you’ve generated. Your final upload should have the files arranged in this layout:1</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• &lt;AndrewId&gt;.zip

– &lt;AndrewId&gt;/

∗ &lt;AndrewId&gt;.pdf ∗ matlab/

· MatchPics.m

· briefRotTest.m

· computeH.m

· computeH norm.m

· computeH ransac.m

· compositeH.m

· HarryPotterize auto.m

· ar.m

· yourHelperFunctions.m (optional)

∗ result/ · ar.avi

∗ ec/ (optional for extra credit) · ar ec.m

· panorama.m

· the images required for generating the results.

Please make sure you do follow the submission rules mentioned above before uploading your zip file to Canvas. Assignments that violate this submission rule will be penalized by up to 10% of the total score.

7. File paths: Please make sure that any file paths that you use are relative and not absolute. Not imread(’/name/Documents/subdirectory/hw2/data/xyz.jpg’) but imread(’../data/xyz.jpg’).

1 Homographies

Planar Homographies as a Warp

Recall that a planar homography is an warp operation (which is a mapping from pixel coordinates from one camera frame to another) that makes a fundamental assumption of the points lying on a plane in the real world. Under this particular assumption, pixel coordinates in one view of the points on the plane can be directly mapped to pixel coordinates in another camera view of the same points.

</div>
</div>
<div class="layoutArea">
<div class="column">
Q1.1 Homography

</div>
<div class="column">
(5 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Figure 1: A homography H links all points xπ lying in plane π between two camera views x and x′ in cameras C and C′ respectively such that x′ = Hx. [From Hartley and Zisserman]

Prove that there exists a homography H that satisfies equation 1 given two 3×4 camera projection matrices P1 and P2 corresponding to the two cameras and a plane Π. You do not need to produce an actual algebraic expression for H. All we are asking for is a proof of the existence of H.

x1 ≡ Hx2 (1)

The ≡ symbol stands for identical to. The points x1 and x2 are in homogenous

coordinates, which means they have an additional dimension. If x1 is a 3D vector

􏰎xi yi zi􏰏T , it represents the 2D point 􏰎xi yi 􏰏T (called inhomogenous coordinates). zi zi

This additional dimension is a mathematical convenience to represent transformations (like translation, rotation, scaling, etc) in a concise matrix form. The ≡ means that the equation is correct to a scaling factor.

Note: A degenerate case happens when the plane Π contains both cameras’ centers, in which case there are infinite choices of H satisfying equation 1. You can ignore this special case in your answer

The Direct Linear Transform

A very common problem in projective geometry is often of the form x ≡ Ay, where x and y are known vectors, and A is a matrix which contains unknowns to be solved. Given matching points in two images, our homography relationship clearly is an instance of such a problem. Note that the equality holds only up to scale (which means that the set of equations are of the form x = λHx′), which is why we cannot use an ordinary least squares solution such as what you may have used in the past to solve simultaneous equations. A standard approach to solve these kinds of problems is called the Direct Linear Transform, where we rewrite the equation as proper homogeneous equations which are then solved in the standard least squares sense. Since this process involves disentangling the structure of the H matrix, it’s a transform of the problem into a set of linear equation, thus giving it its name.

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Q1.2 Correspondences (15 points) Let x1 be a set of points in an image and x2 be the set of corresponding points in an image taken by another camera. Suppose there exists a homography H such that:

xi1 ≡Hxi2 (i∈{1…N})

where xi1 = 􏰎xi1 y1i 1􏰏T are in homogenous coordinates, xi1 ∈ x1 and H is a 3 × 3

matrix. For each point pair, this relation can be rewritten as Aih = 0

where h is a column vector reshaped from H, and Ai is a matrix with elements de- rived from the points xi1 and xi2. This can help calculate H from the given point correspondences.

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>How many degrees of freedom does h have?</li>
<li>How many point pairs are required to solve h?</li>
<li>Derive Ai.</li>
</ol>
</div>
<div class="column">
(3 points) (2 points) (5 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
4. When solving Ah = 0, in essence you’re trying to find the h that exists in the null space of A. What that means is that there would be some non-trivial solution for h such that that product Ah turns out to be 0.

What will be a trivial solution for h? Is the matrix A full rank? Why/Why not? What impact will it have on the eigen values? What impact will it have on the eigen vectors? (5 points)

Using Matrix Decompositions to calculate the homography

A homography H transforms one set of points (in homogenous coordinates) to another set of points. In this project, we will obtain the corresponding point coordinates using feature matches and will then need to calculate the homography. You have already derived that Ax = 0 in Question 1. In this section, we will look at how to solve such equations using two approaches, either of which can be used in the subsequent assignment questions.

Eigenvalue Decomposition

One way to solve Ax = 0 is to calculate the eigenvalues and eigenvectors of A. The

eigenvector corresponding to 0 is the answer for this. Consider this example:

3 6 −8 A=0 0 6

002

4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Using the Matlab function eig, we get the following eigenvalues and eigenvectors:

1.0000 −0.8944 −0.9535 V =  0 0.4472 0.2860 

0 0 0.0953 D=􏰎3 0 2􏰏

Here, the columns of V are the eigenvectors and each corresponding element in D it’s eigenvalue. We notice that there is an eigenvalue of 0. The eigenvector corresponding to this is the solution for the equation Ax = 0.

3 6 −8 −0.8944 0 Ax=0 0 60.4472=0

00200

Singular Value Decomposition

The Singular Value Decomposition (SVD) of a matrix A is expressed as:

A = UΣV T

Here, U is a matrix of column vectors called the “left singular vectors”. Similarly, V is called the “right singular vectors”. The matrix Σ is a diagonal matrix. Each diagonal element σi is called the “singular value” and these are sorted in order of magnitude. In our case, it is a 9 × 9 matrix.

<ul>
<li>If σ9 = 0, the system is exactly-determined, a homography exists and all points fit exactly.</li>
<li>If σ9 ≥ 0, the system is over-determined. A homography exists but not all points fit exactly (they fit in the least-squares error sense). This value represents the goodness of fit.</li>
<li>Usually, you will have at least four correspondences. If not, the system is under- determined. We will not deal with those here.The columns of U are eigenvectors of AAT . The columns of V are the eigenvectors of AT A. We can use this fact to solve for h in the equation Ah = 0. Using this knowledge, let us reformulate our problem of solving Ax = 0. We want to minimize the error in solution in the least-squares sense. Ideally, the product Ah should be 0. Thus the sum-squared error can be written as:f(h) = 21(Ah − 0)T (Ah − 0) = 21(Ah)T(Ah)= 12hTATAh 5</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Minimizing this error with respect to h, we get:

df=0

</div>
</div>
<div class="layoutArea">
<div class="column">
dh

=⇒ 12(ATA+(ATA)T)h=0

</div>
</div>
<div class="layoutArea">
<div class="column">
AT Ah = 0

This implies that the value of h equals the eigenvector corresponding to the zero eigen- value (or closest to zero in case of noise). Thus, we choose the smallest eigenvalue of AT A, which is σ9 in Σ and the least-squares solution to Ah = 0 is the the corresponding eigen- vector (in column 9 of the matrix V).

Theory Questions

Q1.3 Homography under rotation (5 points)

Prove that there exists a homography H that satisfies x1 ≡ Hx2, given two cameras separated by a pure rotation. That is, for camera 1, x1 = K1 􏰎I 0􏰏 X and for camera 2, x2 = K2 􏰎R 0􏰏X. Note that K1 and K2 are the 3×3 intrinsic matrices of the two cameras and are different. I is 3 × 3 identity matrix, 0 is a 3 × 1 zero vector and X is a point in 3D space. R is the 3 × 3 rotation matrix of the camera.

Q1.4 Understanding homographies under rotation (5 points)

Suppose that a camera is rotating about its center C, keeping the intrinsic parameters K constant. Let H be the homography that maps the view from one camera orientation to the view at a second orientation. Let θ be the angle of rotation between the two. Show that H2 is the homography corresponding to a rotation of 2θ. Please limit your answer within a couple of lines. A lengthy proof indicates that you’re doing something too complicated (or wrong).

Q1.5 Limitations of the planar homography (5 points) Why is the planar homography not completely sufficient to map any arbitrary scene

image to another viewpoint? State your answer concisely in one or two sentences.

Q1.6 Behavior of lines under perspective projections (5 points)

We stated in class that perspective projection preserves lines (a line in 3D is projected to a line in 2D). Verify algebraically that this is the case, i.e., verify that the projection P in x = PX preserves lines.

6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
2 Computing Planar Homographies Feature Detection and Matching

Before finding the homography between an image pair, we need to find corresponding point pairs between two images. But how do we get these points? One way is to select them manually (using cpselect), which is tedious and inefficient. The CV way is to find interest points in the image pair and automatically match them. In the interest of being able to do cool stuff, we will not reimplement a feature detector or descriptor here, but use built-in MATLAB methods. The purpose of an interest point detector (e.g. Harris, SIFT, SURF, etc.) is to find particular salient points in the images around which we extract feature descriptors (e.g. MOPS, etc.). These descriptors try to summarize the content of the image around the feature points in as succint yet descriptive manner possible (there is often a trade- off between representational and computational complexity for many computer vision tasks; you can have a very high dimensional feature descriptor that would ensure that you get good matches, but computing it could be prohibitively expensive). Matching, then, is a task of trying to find a descriptor in the list of descriptors obtained after computing them on a new image that best matches the current descriptor. This could be something as simple as the Euclidean distance between the two descriptors, or something more complicated, depending on how the descriptor is composed. For the purpose of this exercise, we shall use the widely used FAST detector in concert with the BRIEF descriptor.

Figure 2: A few matched FAST feature points with the BRIEF descriptor.

Q2.1.1 FAST Detector (5 points) How is the FAST detector different from the Harris corner detector that you’ve seen in the lectures? (You will probably need to look up the FAST detector online.) Can you comment on its computational performance vis-`a-vis the Harris corner detector?

Q2.1.2 BRIEF Descriptor (5 points) How is the BRIEF descriptor different from the filterbanks you’ve seen in the lectures? Could you use any one of those filter banks as a descriptor?

7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Q2.1.3 Matching Methods (5 points) The BRIEF descriptor belongs to a category called binary descriptors. In such de- scriptors the image region corresponding to the detected feature point is represented as a binary string of 1s and 0s. A commonly used metric used for such descriptors is called the Hamming distance. Please search online to learn about Hamming distance and Nearest Neighbor, and describe how they can be used to match interest points with BRIEF descriptors. What benefits does the Hamming distance distance have over a more conventional Euclidean distance measure in our setting?

Q2.1.4 Feature Matching (10 points) Please implement a function:

[locs1, locs2] = matchPics(I1, I2)

where I1 and I2 are the images you want to match. locs1 and locs2 are N × 2 matrices containing the x and y coordinates of the matched point pairs. Use the Matlab built-in function detectFASTFeatures to compute the features, then build descriptors using the provided computeBrief function and finally compare them using the built-in method matchFeatures. Use the function showMatchedFeatures(im1, im2, locs1, locs2, ‘montage’) to visualize your matched points and include the result image in your write-up. An example is shown in Fig. 2.

We provide you with the function:

[desc, locs] = computeBrief(img, locs in)

which computes the BRIEF descriptor for img. locs in is an N × 2 matrix in which each row represents the location (x, y) of a feature point. Please note that the number of valid output feature points could be less than the number of input feature points. desc is the corresponding matrix of BRIEF descriptors for the interest points.

Q2.1.5 BRIEF and Rotations (10 points) Let’s investigate how BRIEF works with rotations. Write a script briefRotTest.m that:

• Takes the cv cover.jpg and matches it to itself rotated [Hint: use imrotate] in increments of 10 degrees.

• Stores a histogram of the count of matches for each orientation. • Plots the histogram using plot

Visualize the feature matching result at three different orientations and include them in your write-up. Explain why you think the BRIEF descriptor behaves this way. What happens when you switch to a different feature detector? [Hint: For instance, try detectSURFFeatures ]. Does the plot change significantly? Why/Why not?

</div>
</div>
<div class="layoutArea">
<div class="column">
Homography Computation Q2.2.1 Computing the Homography

</div>
<div class="column">
(15 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Write a function computeH that estimates the planar homography from a set of matched point pairs.

<pre>     function [H2to1] = computeH(x1, x2)
</pre>
x1 and x2 are N × 2 matrices containing the coordinates (x, y) of point pairs between the two images. H2to1 should be a 3 × 3 matrix for the best homography from image 2 to image 1 in the least-square sense. You can use eig or svd to get the eigenvectors (see Section 1 of this handout for details).

Homography Normalization

Normalization improves numerical stability of the solution and you should always normalize your coordinate data. Normalization has two steps:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Translate the mean of the points to the origin.

2. Scale the points so that the largest distance to the origin is This is a linear transformation and can be written as follows:

x􏰐 1 = T 1 x 1

x􏰐 2 = T 2 x 2

</div>
<div class="column">
√

</div>
<div class="column">
2.

</div>
</div>
<div class="layoutArea">
<div class="column">
where x􏰐1 and x􏰐2 are the normalized homogeneous coordinates of x1 and x2. T1 and T2 are 3 × 3 matrices.

</div>
</div>
<div class="layoutArea">
<div class="column">
The homography H from x􏰐2 to x􏰐1 computed by computeH satisfies: x􏰐 1 = H x􏰐 2

By substituting x􏰐1 and x􏰐2 with T1x1 and T2x2, we have: T1x1 = HT2x2

x =T−1HTx 1122

Q2.2.2 Homography with normalization

Implement the function computeH norm: function [H2to1] = computeH norm(x1, x2).

</div>
<div class="column">
(10 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
This function should normalize the coordinates in x1 and x2 and call computeH(x1, x2) as described above.

9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
RANSAC

The RANSAC algorithm can generally fit any model to noisy data. You will implement it for (planar) homographies between images. Remember that 4 point-pairs are required at a minimum to compute a homography.

Q2.2.3 Implement RANSAC for computing a homography (25 points) Write a function:

function [bestH2to1, inliers] = computeH ransac(locs1, locs2)

where bestH2to1 should be the homography H with most inliers found during RANSAC. H will be a homography such that if x2 is a point in locs2 and x1 is a corresponding point in locs1, then x1 ≡ Hx2. locs1 and locs2 are N × 2 matrices containing the matched points. inliers is a vector of length N with a 1 at those matches that are part of the consensus set, and 0 elsewhere. Use computeH norm to compute the homography.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 3: Text book Figure 4: HarryPotterized Text book

Automated Homography Estimation and Warping Q2.2.4 Putting it together

Write a script HarryPotterize.m that

1. Reads cv cover.jpg, cv desk.png, and hp cover.jpg.

</div>
<div class="column">
(10 points)

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Computes a homography automatically using MatchPics and computeH ransac.</li>
<li>Warps hp cover.jpg to the dimensions of the cv desk.png image using the pro- vided warpH function.</li>
<li>At this point you should notice that although the image is being warped to the correct location, it is not filling up the same space as the book. Why do you think this is happening? How would you modify hp cover.jpg to fix this issue?10</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
5. Implement the function:

function [ composite img ] = compositeH( H2to1, template, img )

to now compose this warped image with the desk image as in in Figure 4 6. Include your result in your write-up.

3 Creating your Augmented Reality application

Q3.1 Incorporating video (20 points) Now with the code you have, you’re able to create you own Augmented Reality appli- cation. What you’re going to do is HarryPoterize the video ar source.mov onto the video book.mov. More specifically, you’re going to track the computer vision text book in each frame of book.mov, and overlay each frame of ar source.mov onto the book in book.mov. Please write a script ar.m to implement this AR application and save your result video as ar.avi in the result/ directory. You may use the function loadVid.m that we provide to load the videos. Your result should be similar to the LifePrint project. You’ll be given full credits if you can put the video together correctly. See Figure 5 for an example frame of what the final video should look like.

Figure 5: Rendering video on a moving target

Note that the book and the videos we have provided have very different aspect ratios (the ratio of the image width to the image height). You must either use imresize or crop each frame to fit onto the book cover.

Cropping an image in Matlab is easy. You just need to extract the rows and columns you are interested in. For example, if you want to extract the subimage from point (40, 50) to point (100, 200), your code would look like img cropped = img(50:200,

11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
40:100). In this project, you must crop that image such that only the central region of the image is used in the final output. See Figure 6 for an example.

Figure 6: Crop out the yellow regions of each frame to match the aspect ratio of the book

Also, the video book.mov only has translation of objects. If you want to account for rotation of objects, scaling, etc, you would have to pick a better feature point representation (like ORB).

4 Extra Credit

Q4.1x: Make Your AR Real Time (15 points)

Write a script ar ec.m that implements the AR program described in Q3.1 in real time. As an output of the script, you should process the videos frame by frame and have the combined frames played in real time. You don’t need to save the result video for this question. The extra credits will be given to fast programs measured by FPS (frames per second). More specifically, we give 5 points to programs that run faster than 10 FPS, 10 points to programs running faster than 20 FPS and 15 points to programs running faster than 30 FPS.

Q4.2x: Create a Simple Panorama (10 points)

Take two pictures with your own camera, separated by a pure rotation as best as possible, and then construct a panorama with panorama.m. Be sure that objects in the images are far enough away so that there are no parallax effects. You can use Matlab’s cpselect to select matching points on each image or some automatic method. Submit the original images, the final panorama, and the script panorama.m that loads the images and assembles a panorama. We have provided two images for you to get started (data/pano left.png and data/pano right.png). Please use your own images when submitting this project. In your submission, include your original images and the panorama result image in your write-up. See Figure 8-10 below for example.

12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Figure 7: Original Image 1 (left) Figure 8: Original Image 2 (right)

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 9: Panorama

13

</div>
</div>
</div>
