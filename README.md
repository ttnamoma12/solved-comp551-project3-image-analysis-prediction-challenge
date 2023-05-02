Download Link: https://assignmentchef.com/product/solved-comp551-project3-image-analysis-prediction-challenge
<br>
In this mini-project the goal is to perform an image analysis prediction challenge. The task is based upon the MNIST dataset (https://en.wikipedia.org/wiki/MNIST_database). The original MNIST contains handwritten numeric digits from 0-9 and the goal is to classify which digit is present in an image.

Here, you will be working with a Modified MNIST dataset that we have constructed. In this modified dataset, the images contain three digits, and the goal is to output the digit in the image with the highest numeric value. Each example is represented as a matrix of pixel intensity values (i.e., the images are grey-scale not color). Examples of this task are shown in Figure 1. <strong>Note that this is a supervised classification task: Every image has an associated label (i.e., the digit in the image with the highest numeric value) and your goal is to predict this label.</strong>

Figure 1: Example images from the dataset. For example, the target label for the top-left image would be 7, while the target label for the bottom-right image would be 8.

<h1>Task</h1>

You must design and validate a supervised classification model to perform the Modified MNIST prediction task. There are no restrictions on your model, except that it should be written in Python. As with the previous mini-projects, you must write a report about your approach, so you should develop a coherent validation pipeline and ideally provide justification/motivation for your design decisions. <strong>You are free to develop a single model or to use an ensemble; there are no hard restrictions.</strong>

<h1>Deliverables</h1>

You must submit two separate files to MyCourses (<strong>using the exact filenames and file types outlined below</strong>):

<ol>

 <li><strong>zip</strong>: A collection of .py, .ipynb, and other supporting code files. <strong>It must be possible for the TAs to reproduce all the results in your report and your Kaggle leaderboard submissions using your submitted code. </strong>Please submit a README detailing the packages you used and providing instructions to replicate your results.</li>

 <li><strong>pdf</strong>: Your (max 5-page) project write-up as a pdf (details below).</li>

</ol>

<h2>Project write-up</h2>

Your team must submit a project write-up that is a maximum of five pages (single-spaced, 10pt font or larger; extra pages for references/bibliographical content and appendices can be used). We highly recommend that students use LaTeX to complete their write-ups, use the bibtex feature for citations, and follow the NeurIPS style formatting (https://nips.cc/Conferences/2019/PaperInformation/StyleFiles). <strong>You are free to structure the report how you see fit</strong>; below are general guidelines and recommendations, <strong>but this is only a suggested structure and you may deviate from it as you see fit.</strong>

<strong>Abstract (100-250 words)           </strong>Summarize the project task and your most important findings.

<strong>Introduction (5+ sentences) </strong>Summarize the project task, the dataset, and your most important findings. This should be similar to the abstract but more detailed.

<strong>Related work (4+ sentences)            </strong>Summarize previous relevant literature.

<strong>Dataset and setup (3+ sentences) </strong>Very briefly describe the dataset/task and any basic data preprocessing methods. <strong>Note: </strong>You do not need to explicitly verify that the data satisfies the i.i.d. assumption (or any of the other formal assumptions for linear classification).

<strong>Proposed approach (7+ sentences </strong>) Briefly describe your model (or the different models you developed, if there was more than one), providing citations as necessary. <strong>If you use or build upon an existing model based on previously published work, it is essential that you properly cite and acknowledge this previous work. </strong>Include any decisions about training/validation split, regularization strategies, any optimization tricks, setting hyper-parameters, etc. It is not necessary to provide detailed derivations for the model(s) you use, but you should provide at least few sentences of background (and motivation) for each model.

<strong>Results (7+ sentences, possibly with figures or tables) </strong>Provide results for your approach (e.g., accuracy on the validation set, runtime). You should report your leaderboard test set accuracy in this section, but most of your results should be on your validation set (or from cross validation).

<strong>Discussion and Conclusion (3+ sentences)           </strong>Summarize the key takeaways from the project and possibly directions for future investigation.

<strong>Statement of Contributions (1-3 sentences)              </strong>State the breakdown of the workload.

<h1>Evaluation</h1>