# Computer--Vision-Lectures
This is a series of jupyter notebooks that tries to cover computer vision from its origins to the present day

<h2>Lecture 1 (How vision works)</h2>

<ul style="font-weight: 100;">
    <li><b>How vision works</b>
    <ul>
        <li>How does eyes work</li>
        <li>How do we process light?</li>
        <li>How the brain sees 3D</li>
        <ul>
            <li>One eye</li>
            <li>Two eyes</li>
            <li>Brain</li>
        </ul>
        <li>So what are we looking at?</li>
        <ul>
            <li>where does light come from?</li>
            <li>so what makes visible light special, then?</li>
        </ul>
        <li>How do we perceive colors?</li>
        <li>CIE 1931 and Color Matching (William Wright and John Guild Experiment)</li>
        <ul>
            <li>Experiment</li>
            <li>Restrictions on viewing conditions</li>
        <li>Practical example</li>
        <li>From CIE-RGB to CIE-XYZ</li>
        <ul>
            <li>sRGB</li>
            <li>Linear sRGB</li>
            <li>CIELAB</li>
        </ul>
    </ul>
</ul>
      
<h2>Lecture 2 (How the cameras work)</h2>
 
 <ul style="font-weight: 100;">
    <li><b>How the cameras work</b>
        <ul>
            <li>Camera operation</li>
            <ul>
                <li>Pinhole camera</li>
                <li>Bayer Pattern</li>
            </ul>
            <li>Reading Images on the Computer</li>
            <li>Pixel Grid</li>
            <li>Pixel read types</li>
            <ul>
                <li>HWC (Height, Width, Channel)</li>
                <li>CHW (Channel, Height, Width)</li>
            </ul>
        </ul>
    </li>
    <li><b>Getting started with OpenCV</b>
        <ul>
            <li>Read an Image</li>
            <li>Show an Image</li>
            <li>Save an Image</li>
            <li>Read from the camera (video)</li>
            <li>Read from a video</li>
            <li>Draw in a frame</li>
            <ul>
                <li>Draw a line</li>
                <li>Draw an arrow</li>
                <li>Draw a rectangle</li>
                <li>Draw a circle</li>
                <li>Draw a Polygon</li>
                <li>Draw text</li>
            </ul>
            <li>Print day and time on video</li>
            <li>Event Handlers in OpenCV</li>
        </ul>
    </li>
    <li><b>Representation of information in tensors</b></li>
    <li><b>Object Detection and Object Tracking Using HSV</b></li>
</ul>
      
 <h2>Lecture 3 (Image interpolation and scaling)</h2>
      
 <ul style="font-weight: 100;">
    <li><b>Image interpolation and scaling</b>
        <ul>
            <li>Image size scaling</li>
            <ul>
                <li>Nearest neighbor</li>
                <li>Triangle interpolation</li>
                <li>Bilinear interpolation</li>
                <li>Bicubic Interpolation</li>
                <li>Summary and some others</li>
            </ul>
            <li>Image size reduction</li>
            <ul>
                <li>Box filter</li>
                <li>Gaussean filter</li>
                <li>Filters for Images on OpenCV (summary and some others)</li>
                <li>Image De-noising - Non-Local Means Denoising</li>
            </ul>
            <li>Low-pass/High-pass Filters</li>
            <ul>
                <li>Simple Image Thresholding (With Global Value)</li>
                <li>Adaptive Thresholding (With Dynamic Value)</li>
                <li>Otsu's Binarization</li>
            </ul>
            <li>Histograms</li>
            <ul>
                <li>One-dimensional</li>
                <li>Multidimensional</li>
            </ul>
            <li>Morphological Transformations</li>
            <ul>
                <li>Dilation</li>
                <li>Erosion</li>
                <li>Opening</li>
                <li>Closing</li>
                <li>Gradiant</li>
                <li>Tophat</li>
                <li>blackhat</li>
                <li>Structuring Elements</li>
                <li>Thinning</li>
                <li>Thickening</li>
                <li>Skeletonization (Medial Axis Transform)</li>
            </ul>
            <li>Bitwise Operations</li>
            <ul>
                <li>AND</li>
                <li>OR</li>
                <li>XOR</li>
                <li>NOT - square</li>
            </ul>
            <li>Find Edges</li>
            <ul>
                <li>Properties of convolutions</li>
                <ul>
                    <li>Commutative property</li>
                    <li>Associative property</li>
                    <li>Distribution property over addition</li>
                    <li>Scalable property</li>
                </ul>
                <li>Sobel filters</li>
                <ul>
                    <li>Sobel X</li>
                    <li>Sobel Y</li>
                    <li>Sobel XY</li>
                    <li>Sobel Combined</li>
                </ul>
                <li>Laplacian</li>
                <li>Gaussian difference (DoG)</li>
                <li>Sharpen</li>
                <ul>Sharpen
                    <li>Identity Kernel </li>
                    <li>Sharpen Kernel</li>
                </ul>
                <li>Canny Edge Detector</li>
            </ul>
        </ul>
    </li>
</ul>
