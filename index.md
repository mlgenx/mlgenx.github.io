---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# <h3 class="blackpar_title">(Models, Training and Inference)</h3>
layout: home
---
<div style="display: flex; align-items: center; justify-content: center; background: url('images/header.jpg') no-repeat; background-size: cover; user-select: none; height: 600px; padding: 0;">
    <h1 class="blackpar_title" style="text-align: center; font-weight: bold; line-height: 1.2; text-shadow: 0px 0px 5px black; color:#CCCCFF">Machine Learning for Genomics Explorations (MLGenX)</h1>
</div>


<!--starts inverted2 colors-->
<div class="inverted2">

<br>
<p>
The main objective of this workshop is to bridge the gap between machine learning (ML) and functional genomics (Gen), focusing on target identification---a pivotal aspect of drug discovery. Our goal is to explore this challenging aspect of modern drug development, where we aim to identify biological targets that play a critical role in modulating diseases. We will delve into the intersection of ML and genomics-related topics, with a specific focus on areas where the availability of data has expanded due to emerging technologies (e.g., large-scale genomic screens, single cell, and spatial omics platforms). From a biological perspective, our discussions will encompass sequence design, molecular perturbations, single cell, and spatial omics, shedding light on key biological questions in target identification. On the ML front, we aim to address topics such as interpretability, foundation models for genomics/biology, generalizability, and causal discovery, emphasizing the significance of ML in advancing target identification.</p>
<br>
</div>

<!--starts inverted colors-->
<div class="inverted">
<br>
<h2 class="blackpar_title" id="overview">Overview</h2>
<p>
The critical bottleneck in drug discovery is still our limited understanding of the biological mechanisms underlying diseases. Consequently, often we do not know why patients develop specific diseases, and many drug candidates fail in clinical trials.  Recent advancements in new genomics platforms and the development of diverse omics datasets have ignited a growing interest in the study of this field. In addition, machine learning plays a pivotal role in improving success rates in language processing, image analysis, and molecular design. The boundaries between these two domains are becoming increasingly blurred, particularly with the emergence of modern foundation models that stand at the intersection of data-driven approaches, self-supervised techniques, and genomic explorations. This workshop aims to elucidate the intricate relationship between genomics, target identification, and fundamental machine learning methods. By strengthening the connection between machine learning and target identification via genomics, new possibilities for interdisciplinary research in these areas will emerge. 
</p>
<p>
The goal of this workshop is to bring together communities at the intersection of machine learning and genomics to discuss areas of interaction and explore possibilities for future areas of research.
During this workshop, participants will gain valuable insights into the synergies between ML and genomics-related research, and help refine the next generation of applied and theoretical ML methods for target identification. We look forward to your participation in this exciting discourse on the future of (foundational) genomics and AI.
</p>

<br>
<!-- Call for Papers -->
<h2 class="blackpar_title" id="call_for_papers">Call for Papers</h2>

<p>
We consider a broad range of subject areas including but not limited to the following topics:
</p>

<!--
<ul>
    <li>
	<u><b>Biological sequence design</b></u>: Prediction and optimization of biological sequences, incorporating constraints and prior knowledge
    </li>
	<ul>
	    <li>
	        Effectively miniaturize DNA/RNA/Protein sequences while preserving their key properties
	    </li>
	    <li>
	        Multi-omics-based sequence design
	    </li>
	    <li>
		Modeling long-range sequence interactions
	    </li>
	    <li>
		Tissue/cell-type specific sequence design
	    </li>
	</ul>

    <li>
	<u><b>Inferring cellular communication via cell states and organization in tissues</b></u>: Causal representation learning to model cell states and cellular communities 
    </li>
	<ul>

	    <li>
		Multi-omics data integration (single cell, spatial transcriptomics)
	    </li>
	    <li>
		Cell-cell interactions inference
	    </li>
	    <li>
		Mechanistic modeling of cells in their context to infer cellular function
	    </li>
	    <li>
		Modeling long-range interactions in single-cell and spatial omics
	    </li>
	</ul>

    <li>
	<u><b>Perturbative biology</b></u>: Interpretable and foundation models to understand cellular responses to perturbations
    </li>
	<ul>

	    <li>
		Translating genetic perturbations to understandable and actionable molecular changes
	    </li>
	    <li>
		Causal reasoning for learning gene regulatory networks
	    </li>
	    <li>
		Integrating multimodal perturbation readouts (transcriptomic and phenotypic) to better characterize the broader molecular effects
	    </li>
	    <li>
		Large-scale foundation models for predicting transcriptional outcomes of novel perturbations
	    </li>
	    <li>
		Generalizability of perturbation predictive models across cell lines and cellular contexts
	    </li>
	</ul>
</ul>

<h5>From first principles: AI for Genomics Exploration</h5>
-->

<ul>
    <li><b>Foundation models for genomics</b>
    </li>
    <li><b>Biological sequence design</b>
    </li>
    <li><b>Interpretability and Generalizability in genomics</b>
    </li>
    <li><b>Causal representation learning</b>
    </li>
    <li><b>Perturbation biology</b>
    </li>
    <li><b>Modeling long-range dependencies in sequences, single-cell and spatial omics</b>
    </li>
    <li><b>Integrating multimodal perturbation readouts</b>
    </li>
    <li><b>Active learning in genomics</b>
    </li>
    <li><b>Generative models in Biology</b>
    </li>
    <li><b>Multimodal representation learning</b>
    </li>
    <li><b>Uncertainty quantification</b>
    </li>
    <li><b>Optimal transport</b>
    </li>
    <li><b>Experimental design for Biology</b>
    </li>
    <li><b>Graph neural network and knowledge graph</b>
    </li>
    <li><b>New datasets and benchmarks for genomics explorations</b>
    </li>
</ul>

<p>
Both contributions introducing new ML methods to existing problems and those that highlighting and explaining open problems are welcome. 
We also encourage submissions related to application of molecular biology, including but not limited to, single-cell RNA analysis, bulk RNA studies, proteomics, and microscopy imaging of cells and/or tissues.</p>

<!--
<h3 class="blackpar_title">Submission Instructions</h3>
<p>
Similar to the main ICLR conference, submissions will be double blind.  
We use <a href="https://openreview.net/group?id=ICLR.cc/2024/Workshop/MLGenX#tab-your-consoles">OpenReview</a> to host papers. There will be a strict upper limit of 6 pages for the main text of the submission, with unlimited additional pages for citations and appendices. To prepare your submission, please use the <a href="https://github.com/ICLR/Master-Template/raw/master/iclr2024.zip">ICLR template style</a>.
</p>
<p>
Submissions that are identical to versions that have been previously published, or accepted to the main ICLR conference are not allowed. However, papers that cite previous related work by the authors and papers that have appeared on non-peer reviewed websites (like arXiv) do not violate the policy. Submission of the paper to archival repositories such as arXiv is allowed during the review period.
</p>
<p>
<b>Note:</b><span style="color: #D2042D"> Authors are permitted to submit works that are currently under review by other venues. Additionally, accepted papers are not considered archival and can be subsequently published in other conferences or journals.</span> 
</p>
<p>
We plan to offer <b>Best Paper</b> Award(s), and exceptional submissions will be chosen for oral presentations. Please note that while our workshop is not archival, accepted papers will be featured on the workshop website.
</p>

<p> <b>Note:</b> Official reviews are anonymous, and unlike the main ICLR conference track, the papers and reviews are not made public until acceptance!</p>
-->

<!--
<h3 class="blackpar_title">Call for Reviewers</h3>
<p>
We are looking for reviewers with expertise in machine learning or computational biology. If you are interested in joining us, kindly complete this <a href="https://forms.gle/tZoUCQJXYHVjSe6Z8">form</a>.
</p> -->

<h3 class="blackpar_title" id="dates">Important Dates</h3>
<p>
All deadlines are 11:59 pm UTC -12h ("Anywhere on Earth"). All authors must have an OpenReview profile when submitting.
<p>
<ul>
    <li>Submission Deadline: <del> February 8, 2024 </del></li> 
    <li>Acceptance Notification: <del> March 3, 2024 </del> </li>
    <li>Camera-Ready Deadline: <del> April 26, 2024 </del> </li>
    <li>Workshop Date: <b>Saturday, May 11, 2024</b> (in-person)</li>
</ul>
</p>

<h3 class="blackpar_title">Workshop Registration</h3>
<p>
Whether you're a seasoned professional or a curious enthusiast, all are welcome to attend! Don't worry if you don't have an accepted paper – participation is open to everyone.</p>

<p> If you have already registered for ICLR, you can join us at the MLGenX workshop. However, if you're solely interested in the workshop, you can still participate in the MLGenX workshop by registering for the "Saturday Workshop 1 Day Pass". Please visit <a href="https://iclr.cc/Register/view-registration">this link</a> to secure your spot. </p>

<p>We look forward to meeting you in Vienna!
</p>

<br>
<h2 class="blackpar_title" id="speakers">Speakers & Panelists</h2>
<p>
{% include speakers.html %}
</p>



<!-- Schedule -->
<h2 class="blackpar_title" id="schedule">Schedule (CET)</h2>
<p>
{% include schedule.html %}
</p>


<!-- Organizers -->
<h2 class="blackpar_title" id="organizers">Organizers</h2>
<p>
{% include organizers.html %}
</p>

<br>
<!-- Technical Committee -->
<h2 class="blackpar_title" id="technical_committee">Technical Committee</h2>
<p>
{% include technical_committee.html %}
</p>
<br><br>


<!--
<h2 class="blackpar_title">Sponsor</h2>
<div class="row">
    <div class="col">
        <center>
            <img src="">
        </center>
    </div>
    <div class="col">
        <center>
            <img src="" width="250px">
        </center>
    </div>
</div>-->


<!--ends inverted colors-->
<!-- Default Statcounter code for mlgenx
https://mlgenx-workshop.github.io/ -->
<script type="text/javascript">
var sc_project=12885210;
var sc_invisible=1;
var sc_security="21af2424";
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/12885210/0/21af2424/1/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->
