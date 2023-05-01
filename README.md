Download Link: https://assignmentchef.com/product/solved-elec0134-the-amls-assignment
<br>
The AMLS assignment comprises individual code writing, training and testing on data, and an individual report in the form of a conference paper and (optionally) supplementary material. You are allowed to discuss ideas with peers, but your code, experiments and report must be done solely based on your own work.

<h2>Assignment summary</h2>

<ol>

 <li>The assignment leverages elements covered in:

  <ol>

   <li>The AMLS lectures,</li>

   <li>The AMLS lab sessions, and</li>

   <li>Relevant research literature associated with machine learning systems.</li>

  </ol></li>

</ol>

The assignment involves the realisation of various machine learning tasks on a provided dataset. You are expected to go through the data, analyse it and/or pre-process it as necessary.

<ol start="2">

 <li>Using your ML knowledge acquired in the lectures and the labs, design solutions for each task described in the section <em>Assignment Description</em> You should also search the relevant literature for additional information, e.g., papers on state-of-theart methods in machine learning.</li>

 <li>Implement your solution in your preferred programming language, e.g., MATLAB, Python, C/C++, Java, etc. However, please note that the weekly exercise of the module will be based on Python, so you are encouraged to use this programming language too.</li>

 <li>Write a report summarising all steps taken to solve the tasks, explaining your model and design choices. In addition, in the report, you should also describe and analyse the results obtained via your experiments and provide accuracy prediction scores on unseen data. Please refer to Report and Code Format and Marking Criteria section for more details about the report.</li>

</ol>

<h2>Goal of the assignment</h2>

<ul>

 <li>To further develop your programming skills.</li>

 <li>To further develop your skills and understanding of machine learning systems.</li>

 <li>To acquire experience in dealing with real-world data.</li>

 <li>To develop good practice in model training, validation and testing.</li>

 <li>To read state-of-the-art research papers on machine learning systems and understand the current challenges and limitations.</li>

 <li>To develop your writing skills by presenting your solutions and findings in the form of a conference paper.</li>

</ul>

<h1>Assignment Description</h1>

<h2>Datasets</h2>

We provide two datasets which are designed specifically for this assignment and contains pre-processed subsets from the following datasets:

<ol>

 <li><strong>CelebFaces Attributes Dataset (CelebA)</strong>, a celebrity image dataset (S. Yang, P. Luo, C.</li>

 <li>Loy, and X. Tang, “From facial parts responses to face detection: A Deep Learning</li>

</ol>

Approach”, in <em>IEEE International Conference on Computer Vision (ICCV)</em>, 2015)

<ol start="2">

 <li><strong>Cartoon Set</strong>, an image dataset of random cartoons/avatars (source: <u>https://google.github.io/cartoonset/</u>).</li>

</ol>

The datasets you are going to use in this assignment are:

<ol>

 <li><strong>celeba</strong>: A sub-set of CelebA dataset. This dataset contains 5000 images. It is going to be used for task A1 and A2.</li>

 <li><strong>cartoon_set</strong>: A subset of Cartoon Set. This dataset contains 10000 images. It is going to be used for task B1 and B2.</li>

</ol>

The datasets can be downloaded via following link: <u>https://drive.google.com/file/d/1wGrq9r1fECIIEnNgI8RS-_kPCf8DVv0B/view?usp=sharing</u> A separate test set will be provided one week before the deadline.

<h2>Tasks</h2>

The machine learning tasks include:

<ol>

 <li><strong>Binary tasks (celeba dataset) </strong></li>

</ol>

A1:<strong>    </strong>Gender detection: male or female.

A2:<strong>    </strong>Emotion detection: smiling or not smiling.

<ol>

 <li><strong>Multiclass tasks (cartoon_set dataset) </strong></li>

</ol>

B1:<strong>     </strong>Face shape recognition: 5 types of face shapes.

B2:<strong>    </strong>Eye color recognition: 5 types of eye colors.

You should design separate modes for each task and report training errors, validation errors, hyper-parameter tuning. You are allowed to use the same model/methodology for different tasks, but you must explain the reason behind choices. If you tried several models for one task, feel free to show them in your code and compare the results in the report.

<h1>Report and Code Format, and Marking Criteria</h1>

<h2>Report format and template</h2>

We provide both latex and MS word templates in <strong><em>AMLS_assignment_kit</em></strong>. The criteria for each part are detailed in the template. For beginners in latex, we recommend <u>overleaf.com</u>, which is a free online latex editor.

Your report should be no longer than <strong>8 pages </strong>(including the reference). You are allowed to append an additional supplementation material to your report with no longer than <strong>4 pages</strong>.

Once you finish your report, please export it into a PDF document and name it with the following format (Using your SN number):

<strong>Report_AMLS_20-21 _SN12345678.pdf </strong>

<h2>Code criteria</h2>

You should write your code in modules and organize them in the following fashion:




<ul>

 <li>Keep <strong>‘Dataset’</strong> folder empty while submitting your code. Use this folder for your programming only. If you need to pre-process the dataset, do not save the intermediate results or pre-processed dataset. Your final submission must directly read the files we provided.</li>

 <li>When assessing your code, we will copy-paste the dataset into this folder. Then, your project should look like:</li>

</ul>

o AMLS_20-21_SN12345678

<ul>

 <li>A1</li>

 <li>A2</li>

 <li>B1</li>

 <li>B2</li>

 <li>Datasets</li>

</ul>

<ul>

 <li>cartoon_set</li>

 <li>celeba</li>

 <li>cartoon_set_test</li>

 <li>celeba_test main.py</li>

 <li>README.md</li>

 <li>The ‘<strong>A1</strong>’, ‘<strong>A2</strong>’, ‘<strong>B1</strong>’ and ‘<strong>B2</strong>’ folders should contain the code files for each task.</li>

 <li>Pre-trained models (especially for deep learning models) are allowed to be saved in the folder for each task.</li>

 <li>The <strong>README</strong> file should contain:</li>

</ul>

o a brief description of the organization of your project; o the role of each file; o the packages required to run your code (e.g. numpy, scipy, etc.).

The recommend format for <strong>README</strong> file is markdown (<strong>.md</strong>). <strong>.txt</strong> is acceptable too.

<ul>

 <li>We should be able to run your project via ‘<strong>py</strong>’. An example structure of ‘<strong>main.py</strong>’ has been provided for your reference.</li>

</ul>

You are NOT going to upload your code and dataset to Moodle. Please refer to Submission session for more details.