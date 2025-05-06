# comp202-assignment-6-graph-implementation-and-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [COMP202 Assignment 6-Graph implementation and algorithms Solved](https://www.ankitcodinghub.com/product/comp202-assignment-6-graph-implementation-and-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96028&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP202 Assignment 6-Graph implementation and algorithms Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Description

This assignment requires you to implement:

• A given graph ADT

• Graph search algorithms

• Graph traversal on an implicit graph (an image)

The files provided to you have comments that will help you with implementation. In addition, keep the slides handy as they include the pseudo-codes for the algorithms. The file descriptions are below. Bold ones are the ones you need to modify and they are placed under the code folder, with the rest under given. The homework consists of three parts:

Graph Implementation

This part of the homework requires you to implement a given graph ADT for four different types of graphs. There is no explicit Edge class or an explicit Vertex class. This is done to give you total freedom. If you need extra classes such as these, feel free to put them as nested classes but do not provide extra files.

<ul>
<li>iGraph.java: The interface that defines the graph ADT. Make sure you pay attention to all the comments!</li>
<li>BaseGraph.java: The abstract base class for the graphs that you should implement. You can put the common functions here or ignore this file all together.</li>
<li>UndirectedUnweightedGraph.java: Implement an undirected-unweighted graph in this file.</li>
<li>DirectedUnweightedGraph.java: Implement a directed-unweighted graph in this file.</li>
<li>UndirectedWeightedGraph.java: Implement an undirected-weighted graph in this file.</li>
<li>DirectedWeightedGraph.java: Implement an directed-weighted graph in this file.</li>
<li>GraphTesting.java: The file that includes the autograder implementation this part. Can be run by itself.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Graph Algorithms

This part of the homework requires you to implement depth first search (DFS), breadth first search (BFS), Dijkstra’s single-source all-destinations shortest path (or actually smallest cost) algorithm and cycle finding algorithms (for both directed and undirected graphs).

<ul>
<li>GraphAlgorithms.java: Implement the algorithms. You can (and probably should) add more methods and fields.</li>
<li>AlgTesting.java: The file that includes the autograder implementation this part. Can be run by itself.
Implicit Graphs: Image Segmentation

This part of the homework requires you to work on an implicit graph formed by the pixels of an image. Think of an image as a 2D array of floating point numbers (doubles in this case). These individual floating point numbers are called pixels. Pixels are indexed by their rows and columns. Pixels values range from 0.0 to 1.0. See Fig. 1

Figure 1: A grayscale image is very similar to a 2D array.

The task is to segment a given image by applying graph algorithms. The goal of image segmentation is to cluster pixels into image regions. In our segmentation approach, we want to group together pixels that have similar values. We can pose this as a problem of finding connected components in a graph where each pixel is a vertex and pixel value similarity decides whether there is an edge between neighboring vertices Each pixel has 4 possible neighbors as shown in Fig.2:

Figure 2: The pixel in the middle(red color) has 4 possible neighbors labeled 0, 1, 2, 3. Look at the images under the images/input and images/reference folders to get an idea.

<ul>
<li>ImageSegmenter.java: The file where you need to implement the segmentation approach. There is a dummyIteration method to help you get around the image.</li>
<li>Image.java: This files defines a wrapper for an image class. You need to go over it to be able to handle this part of the assignment.</li>
<li>GradeImagePart.java: The file that includes the autograder implementation this part. Can be run by itself.</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
