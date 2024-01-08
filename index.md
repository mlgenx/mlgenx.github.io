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
    <h1 class="blackpar_title" style="text-align: center; font-weight: bold; line-height: 1.2; text-shadow: 0px 0px 5px black;">Machine Learning for Genomics Explorations (MLGenX)</h1>
</div>



<br>
<p>
The main objective of this workshop is to bridge the gap between machine learning (ML) and functional genomics (Gen), focusing on target identification---a pivotal aspect of drug discovery. Our goal is to explore this challenging aspect of modern drug development, where we aim to identify biological targets that play a critical role in modulating diseases. We will delve into the intersection of ML and genomics, with a specific focus on areas where the availability of data has expanded due to emerging technologies (e.g., large-scale genomic screens, single cell, and spatial omics platforms). From a biological perspective, our discussions will encompass sequence design, molecular perturbations, single cell, and spatial omics, shedding light on key biological questions in target identification. On the ML front, we aim to address topics such as interpretability, foundation models for genomics/biology, generalizability, and causal discovery, emphasizing the significance of ML in advancing target identification.</p>

<br>



<!--starts inverted colors-->
<div class="inverted">

<br><br>
<h2 class="blackpar_title" id="overview">Overview</h2>
<p>
The critical bottleneck in drug discovery is still our limited understanding of the biological mechanisms underlying diseases. Consequently, often we do not know why patients develop specific diseases, and many drug candidates fail in clinical trials.  Recent advancements in new genomics platforms and the development of diverse omics datasets have ignited a growing interest in the study of this field. In addition, machine learning plays a pivotal role in improving success rates in language processing, image analysis, and molecular design. The boundaries between these two domains are becoming increasingly blurred, particularly with the emergence of modern foundation models that stand at the intersection of data-driven approaches, self-supervised techniques, and genomic explorations. This workshop aims to elucidate the intricate relationship between genomics, target identification, and fundamental machine learning methods. By strengthening the connection between machine learning and target identification via genomics, new possibilities for interdisciplinary research in these areas will emerge. 
</p>
<p>
The goal of this workshop is to bring together communities at the intersection of machine learning and genomics to discuss areas of interaction and explore possibilities for future areas of research.
During this workshop, participants will gain valuable insights into the synergies between ML and genomics research, and help refine the next generation of applied and theoretical ML methods for target identification. We look forward to your participation in this exciting discourse on the future of (foundational) genomics and AI.
</p>

<br>
<!-- Call for Papers -->
<h2 class="blackpar_title" id="call_for_papers">Call for Papers</h2>

<p>
We invite researchers, scientists, students, and industry professionals working in the domains of artificial intelligence, machine learning, computational biology, bioinformatics, and related areas to submit their original research or review papers.
The scope of this workshop includes but is not limited to the following topics.
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
    <li><b>New datasets and benchmarks for genomics explorations</b>
    </li>
    <li><b>Multimodal representation learning</b>
    </li>
    <li><b>Uncertainty quantification</b>
    </li>
</ul>

<br>
<h2 class="blackpar_title">Submission Instructions</h2>
<p>
You are invited to submit your papers in our OpenReview submission <a href="https://openreview.net/group?id=ICLR.cc/2024/Workshop/MLGenX#tab-your-consoles">portal</a>.
All submissions must be anonymous for double-blind review.
The content of the paper (excluding the references and supplementary materials) should not be longer than 6 pages,
with strict adherence to the ICLR template style,
which can be found <a href="https://github.com/ICLR/Master-Template/raw/master/iclr2024.zip">here</a>.
</p>
<p>
Authors may submit up to 100 MB of supplementary materials separately.
Authors are highly encouraged to submit their code for reproducibility.
</p>
<p>
According to the ICLR workshop guidelines, we do not accept the
re-submission of already-published papers,
but you are allowed to submit ArXiv pre-prints or those currently under submission.
Moreover, a work that is presented at the ICLR main conference should not appear in a workshop.
Please be sure to indicate conflicts of interest for all authors on your paper.
</p>
<p>
To encourage higher quality submissions, we will offer <b>Best Paper</b> Award(s)
based on nomination by the reviewers and extensive discussions among the chairs.
Furthermore, outstanding submissions will also be selected for oral presentations.
Bear in mind that our workshop is not archival,
but accepted papers will be hosted on the workshop website.
</p>

<br>
<h2 class="blackpar_title" id="deadlines">Important Dates:</h2>
<p>
All deadlines are 11:59 pm UTC -12h ("Anywhere on Earth"). All authors must have an OpenReview profile when submitting.
<p>
<ul>
    <li>Submission Deadline: February 4, 2024</li>
    <li>Acceptance Notification (tentative): March 1, 2024</li>
    <li>Workshop Date: <b>Saturday, May 11, 2024</b> (in-person)</li>
</ul>
</p>

<br>
<h2 class="blackpar_title" id="speakers">Speakers & Panelists</h2>
<p>
{% include speakers.html %}
</p>



<!-- Schedule -->
<!-- 
<h2 class="blackpar_title" id="schedule">Schedule (CET)</h2>
<p>
{% include schedule.html %}
</p>-->


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
