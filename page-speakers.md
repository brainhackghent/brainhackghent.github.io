---
title: OpenMR Benelux 2020
subtitle: Program and Speakers
layout: page
show_sidebar: false
#tabs: example_tabs
#hero_image: assets/ext_images/Home_logo.png
---

<!--- ## Information about the confirmed speakers -->

<html>
<head>
<style>
.accordion:after {
  content: '\002B'; /* Unicode character for "plus" sign (+) */
  font-size: 13px;
  color: #ffffff;
  float: right;
  margin-left: 5px;
}
.active:after {
  content: "\2212"; /* Unicode character for "minus" sign (-) */
  font-size: 13px;
  color: #ffffff;
  float: right;
  margin-left: 5px;
}
/* Style the buttons that are used to open and close the accordion panel */
.accordion {
  background-color: #004777;
  color: #ffffff;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  text-align: left;
  border: none;
  outline: none;
  transition: 0.4s;
}
/* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
.active, .accordion:hover {
  background-color: #004777;
}
/* Style the accordion panel. Note: hidden by default */
.panel {
  padding: 0 18px;
  background-color: #ffffff;
  display: none;
  overflow: hidden;
}
</style>
</head>
<body>
  
<h2 style="color:#004777"> Speakers </h2>
<h3 style="color:#004777"> Tuesday, 21 January 2020 </h3>

<div style="overflow-x:auto;">
  
<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="marjan"></a>
{% include speaker-card.html
  avatarurl="marjan.png"
  profilename="Marjan Bakker"
  affiliation="Tilburg School of Social and Behavioral Sciences <br>Department of Methodology and Statistics <br>Tilburg University"
  city="Tilburg, The Netherlands"
  homepage="http://www.marjanbakker.eu/"%}
</td>
<td width="500px" align="left" valign="center">
<a name="cassandra"></a>
{% include speaker-card.html
  avatarurl="cass.png"
  profilename="Cassandra Gould van Praag"
  affiliation="Psychopharmacology and Emotion Research Laboratory <br>Department of Psychiatry <br>University of Oxford"
  city="Oxford, UK"
  homepage="https://www.psych.ox.ac.uk/team/cassandra-gould-van-praag"
  git="https://github.com/cassgvp"
  twitter="https://twitter.com/cassgvp" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Marjan Bakker is an assistant professor at the Methods and Statistics department at Tilburg University. She is part of the Meta-Research Center in Tilburg at which they study the scientific system in psychology; in general to find its flaws and empirically test potential solutions. She wants to improve science by investigating problems and possible solutions. Her interests consist of reporting errors, the use of questionable research practices, statistical power, outliers in data, publication bias, and preregistration. Currently, she is mainly working on some larger projects on preregistration and on a project to replicate Mahoney’s seminal study on publication bias (for which she got an NWO replication grant).</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Diving Into Metascience – Doing Research on Research</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Cass is a postdoctoral researcher at the University of Oxford Department of Psychiatry. She provides support for (f)MRI experimental design and analysis in the investigation of treatments for mood disorders. In this role she has to stay up to speed with the leading edge of analytic tools, and is constantly on the lookout for tips, tricks and techniques to make this research quicker, slicker, and more effective. This goes hand-in-hand with making the research more transparent and reproducible, and freely sharing the outputs of our labour. She is a contributor to <a href="https://the-turing-way.netlify.com/introduction/introduction">The Turing Way</a> and works with the <a href="https://www.win.ox.ac.uk/open-neuroimaging/open-neuroimaging-project">Wellcome Centre for Integrative Neuroimaging Open Community Team</a>. She is a passionate believer in accessibility and the equitable dissemination of knowledge, and spends a lot of time showing people that programming isn’t scary.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Analytic flexibility and questionable research practices in MRI</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>The number of methods available for MRI analysis is growing every year. Each of these methods requires the specification of a bewildering array of parameters, not all of which are amenable to optimisation by consensus. The combination of these factors leads to an almost infinite number of ways in which we may analyse our data, and accordingly and infinite number of results which we may choose to report, or not. In this talk I will discuss concerns of such analytic flexibility and the draw of questionable research practices to help uncover the "publishable story" in our data. I will present recent developments in our discipline which may assist the identification of robust effects, and what individual actions we may take in order to retain confidence in our own findings.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="pim"></a>
{% include speaker-card.html
  avatarurl="pim.png"
  profilename="Pim Pullens"
  affiliation="Department of Radiology (Ghent University - Ghent University hospital) and Ghent Institute for Functional and Metabolic Imaging (GIfMI)"
  city="Ghent, Belgium" 
  twitter="https://www.twitter.com/pim_pullens"
  researchgate="https://www.researchgate.net/profile/Pim_Pullens" %}
</td>
<td width="500px" align="left" valign="center">
<a name="joao"></a>
{% include speaker-card.html
  profilename="Joao Periquito" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>How can Open Science Contribute to (Clinical) Research in Radiology?</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="daniele"></a>
{% include speaker-card.html
  avatarurl="daniele.png"
  profilename="Daniele Marinazzo"
  affiliation="Department of Data Analysis <br>Faculty of Psychology and Educational Sciences <br>Ghent University"
  city="Ghent, Belgium"
  homepage="http://users.ugent.be/~dmarinaz/"
  twitter="https://twitter.com/dan_marinazzo"                                                                                                
  git="https://github.com/danielemarinazzo"
  researchgate="https://www.researchgate.net/profile/Daniele_Marinazzo" %}
</td>
<td width="500px" align="left" valign="center">
<a name="kirstie"></a>
{% include speaker-card.html
  avatarurl="kirstie_2.png"
  profilename="Kirstie Whitaker"
  affiliation="The Alan Turing Institute"
  city="London, UK"
  homepage="https://kirstiewhitaker.com/"
  twitter="https://twitter.com/kirstie_j"
  git="https://github.com/KirstieJane"
  researchgate="https://www.researchgate.net/profile/Kirstie_Whitaker" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Daniele Marinazzo is an associate professor in the department of Data Analysis of the Faculty of Psychology and Educational Sciences at Ghent University. His team focuses on methodological and computational aspects of neuroscience research, and on the dynamical networks subserving function, as well as thorough statistical validation of the results. They develop new techniques for inferring connectivity architectures from the dynamics of the recorded data, in challenging cases of short, noisy and redundant time series, as those encountered in neuroimaging. Daniele cares about open science and ways to improve the review/editorial process. He is an editor at several journals in his field, including PLOS Computational Biology, PLOS One, NeuroImage, Brain Topography, Network Neuroscience. Visit Daniele’s <a href="https://publons.com/researcher/663417/daniele-marinazzo">Publons review profile</a> for more.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Current and Future Scenarios for Open Scientific Publishing and Reviewing</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Communicating our research is a fundamental part of our work as scientists, and a duty towards the society. Typically this communication happens through articles published in scientific journals, after having been reviewed by our peers. We will discuss several aspects of scholarly communication and in particular of scientific publishing and peer review. Some of these aspects are (un-)surprisingly in clear contrast with the idea of science as an open and collaborative public mission. Several solutions and improvements have been proposed and sometimes implemented over the years, on some of them there’s wide consensus, on others there is not. And even when there is consensus to change, the change is slow. We will explore the state of the art and different future perspectives, and discuss our experiences and expectations.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>The Turing Way: Reproducible, Inclusive, Collaborative Data Science</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Reproducible research is necessary to ensure that scientific work can be trusted. By sharing data, analysis code and the computational environment used to generate the results, researchers can more effectively stand on the shoulders of their peers and colleagues and deliver high quality, trustworthy and verifiable outputs. This requires skills in data management, library sciences, software development, and continuous integration techniques: skills that are not widely taught or expected of academic researchers. Skills that are unreasonable, in fact, to expect in one individual team member. <br> The Turing Way is a handbook to support students, their supervisors, funders and journal editors in ensuring that reproducible research is "too easy not to do". It includes training material on version control, analysis testing, collaborating in distributed groups, open and transparent communication skills, and effective management of diverse research projects. The Turing Way is openly developed and any and all questions, comments and recommendations are welcome at our GitHub repository: https://github.com/alan-turing-institute/the-turing-way. <br>In this talk, Kirstie Whitaker, lead developer of The Turing Way, will take you on a whirlwind tour of the chapters that already exist, the interactive demonstrations you can use and re-use for your own research, and the directions in which we're continuing to develop. All participants will leave the talk knowing that "Every Little Helps" when making their work reproducible, where to ask for help as they start or continue their open research journey, and how they can contribute to improve The Turing Way for future readers.</p>
</div>
</td>
</tr>
</table>

</div>

<h3 style="color:#004777"> Wednesday, 22 January 2020 </h3>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="fatma"></a>
{% include speaker-card.html
  avatarurl="fatma.png"
  profilename="Fatma Deniz" %}
</td>
<td width="500px" align="left" valign="center">
<a name="remi"></a>
{% include speaker-card.html
  avatarurl="remi.png"
  profilename="Rémi Gau"
  affiliation="Université catholique de Louvain"
  city="Louvain-la-Neuve, Belgium"
  homepage="https://remi-gau.github.io/"
  git="https://github.com/Remi-Gau"
  twitter="https://www.twitter.com/RemiGau"
  researchgate="https://www.researchgate.net/profile/Remi_Gau" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Software Version Control with git and GitHub</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="sofie"></a>
{% include speaker-card.html
  avatarurl="sofie.png"
  profilename="Sofie Van Den Bossche"
  affiliation="Department of Data Analysis <br> Faculty of Psychology and Educational Sciences <br> Ghent University"
  city="Ghent, Belgium"
  git="https://github.com/sofievdbos"
  twitter="https://www.twitter.com/sofie_vdbos"
  researchgate="https://www.researchgate.net/profile/Sofie_Van_Den_Bossche2" %}
</td>
  <td width="500px" align="left" valign="center">
<a name="serena"></a>
{% include speaker-card.html
  avatarurl="serena.png"
  profilename="Serena Bonaretti"
  affiliation="Transparent MSK Research"
  homepage="https://sbonaretti.github.io/"
  git="https://github.com/sbonaretti"
  twitter="https://www.twitter.com/SerenaBonaretti" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Sofie is currently doing a PhD at the department of Data Analysis (Ghent University, Ghent, Belgium), supervised by Prof. Dr. Daniele Marinazzo. Her research focuses on the intertwined domains of (resting-state) neuroscience and lateralization/handedness. During her PhD adventure, she has also been involved in Open Science events, either as part of the organizing committee (e.g. BrainHack Ghent 2017/2018) or as a volunteer (e.g. Pint of Science, Ghent). Creating an Open Science community and communicating Open Science to a broader public is something she wants to be progressively involved in.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Software Version Control with git and GitHub</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Serena Bonaretti is founder and research scientist at <a href="https://sbonaretti.github.io/transparentMSKresearch.html">Transparent MSK Research</a>. Previously, she was research scientist and postdoctoral fellow at the Departments of Radiology at Stanford University and University of California, San Francisco. She holds a PhD in Biomedical Engineering from the University of Bern, Switzerland. Her background is image acquisition, image processing, and biomechanics to investigate aging diseases of the musculoskeletal system. She has recently released <a href="https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsbonaretti.github.io%2FpyKNEEr%2F&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142714487&sdata=kWnO3g%2F3wM%2F0vQJmjgETe6wJVf%2Fxi2BxmkSS4%2F4f2Sk%3D&reserved=0">pyKNEEr</a>, an image analysis workflow for open and reproducible research on femoral knee cartilage. Previously, she developed <a href="https://eur01.safelinks.protection.outlook.com/?url=http%3A%2F%2Fwebapps.radiology.ucsf.edu%2Frefline%2F&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142724500&sdata=kjT0exJ6lnMijM1Gd8CnYyUV7nKUy15PYM%2F6Hn0RINo%3D&reserved=0">Reference line</a>, a web application to train and evaluate HR-pQCT operators. As a member of the quantitative musculoskeletal imaging (QMSKI) working group for transparent research, she is creating hands-on <a href="https://eur01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2FQMSKI%2FTransparentQMSKI%2Fwiki&data=02%7C01%7Ce.oei%40erasmusmc.nl%7C6137dad6bbfd42f536c408d6d3bc5313%7C526638ba6af34b0fa532a1a511f4ac80%7C0%7C0%7C636929203142734504&sdata=vCR7GAdJJOzI4JoiJSvH66D%2BO2iQDyP18pPaLFh5%2FcI%3D&reserved=0">guidelines</a> on how to conduct open and reproducible research.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>The basics of Python and Jupyter Notebooks for medical image analysis</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Python and Jupyter notebooks are becoming more and more essential tools to conduct open and reproducible research. In this workshop, first we will briefly discuss how these tools can facilitate transparent science. Then, we will have a hands-on session where we will code in Jupyter notebook using python. We will create reproducible workflows using packages that are both basic and specific for medical image analysis (e.g. SimpleITK). Information and material at https://github.com/sbonaretti/2020_OpenMR_jupyter.</p>
</div>
</td>
</tr>
</table>

</div>

<h3 style="color:#004777"> Thursday, 23 January 2020 </h3>

<div style="overflow-x:auto;">

<table border="0" cellpadding="0 15px 0 15px;">
<tr>
<td width="500px" align="left" valign="center">
<a name="malvika"></a>
{% include speaker-card.html
  avatarurl="malvika.png"
  profilename="Malvika Sharan" %}
</td>
<td width="500px" align="left" valign="center">
<a name="natalia"></a>
{% include speaker-card.html
  avatarurl="natalia.png"
  profilename="Natalia Bielczyk"
  affiliation="Founder, Director and Chairperson Stichting Solaris Onderzoek en Ontwikkeling <br> <br> eLife Associate <br> <br> Career Development and Mentoring Manager Organization for Human Brain Mapping"
  homepage="https://www.nataliabielczyk.com/"
  twitter="https://www.twitter.com/nbielczyk_neuro" 
  researchgate="https://www.researchgate.net/profile/Natalia_Bielczyk2" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Natalia Bielczyk has a background in Physics, Mathematics and Psychology (3 x MSc), obtained at the College of Interfaculty Studies in Mathematics and Natural Sciences, University of Warsaw. She is now completing her thesis within the Donders Graduate School, Donders Institute for Brain, Cognition and Behavior, Nijmegen, the Netherlands. Her research concerns developing new methods for connectomics in the domain of cognitive neuroimaging, i.e. for functional and effective connectivity research. Natalia also currently holds a position of a Career Development and Mentoring Manager within the <a href="https://www.ohbmtrainees.com/">Organization for Human Brain Mapping Student and Postdoc Special Interest Group</a>, and serves as an eLife Associate within the <a href="https://elifesciences.org/inside-elife/a946c355/elife-community-ambassadors-243-volunteers-join-the-programme-in-2019">eLife Ambassadors community</a>. In private, she is also a dedicated <a href="https://www.nataliabielczyk.com/">blogger</a>, and a speaker, giving workshops and talks about self-development in academia and transitions to industry. In November 2018, she founded Stichting Solaris Onderzoek en Ontwikkeling in a response to lack of assistance for early career researchers in career development in academia and beyond.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Where to go next? The landscape of Post-PhD career tracks</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>There is a growing disparity between the number of new PhD graduates and the available faculty positions. Effectively, most of the PhD graduates needs to find jobs outside academia. Yet, there is little amount of services dedicated to assisting early career researchers in discovering their core competencies, in searching for employers and landing their dream jobs in industry. Ideally, one should anticipate the potential future market sectors after completing the PhD, and focus on developing transferable skills during the PhD on that basis. This however, remains a rare practice in the graduate schools. Therefore, in this workshop, we will assume that you have no prior experience with job market in industry. We will discuss the following: the demand for PhDs in different branches of industry; paycheck or entrepreneurship? Is a traineeship at a company a good start after a PhD?; defining your key competences, including both hard- and soft skills; searching for employers who are likely to search for these competences; searching for employers who share your personal values; the role of networking in searching for jobs; restructuring your CV and writing a competitive motivational letter; preparing for job interviews. The workshop will be interactive: we will debunk certain myths related to the job market with use of polls and quizzes. Sharing personal experience by participants will be highly encouraged. The goal of the workshop is to give the participants the information and confidence so they can further search for relevant information on their own, and take first steps towards finding their dream job in industry.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="sarah"></a>
{% include speaker-card.html
  avatarurl="sarah.png"
  profilename="Sarah Genon"
  affiliation="Cognitive Neuroinformatics, Institute of Neuroscience and Medicine,
Brain & Behaviour"
  homepage="https://www.fz-juelich.de/SharedDocs/Personen/INM/INM-7/EN/genon_s.html?nn=654218"
  researchgate="https://www.researchgate.net/profile/Sarah_Genon" %}
</td>
  <td width="500px" align="left" valign="center">
<a name="stephanklein"></a>
{% include speaker-card.html
  avatarurl="stephanklein.png"
  profilename="Stefan Klein" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Sarah Genon is a Research Group Leader of the working group ‘Cognitive Neuroinformatics’, which is part of the Institute of Neuroscience and Medicine, Brain & Behaviour (INM-7), located in the Research Centre Jülich (Germany)</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Probing brain organization and function with neuroimaging markers of connectivity</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Across the past years, many developments arose in connectivity analyses based on MRI data offering now a wide range of connectivity markers. Capitalizing on this wealth of neuroimaging markers, connectivity-based parcellation can be used to unravel the complexity of brain organization. Furthermore, large population-based neuroimaging datasets with extensive psychometric characterization now open promising perspectives to link brain organization to behavior. In particular, interindividual variability in brain’s region functional connectivity can be related to interindividual variability in psychometric data by using a connectivity-based psychometric prediction approach. Despite some challenges associated to the use of these data-driven approaches, they also offer opportunities to better understand the relationships between brain connectivity and human behavior.</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="marcel"></a>
{% include speaker-card.html
  avatarurl="marcel.png"
  profilename="Marcel Zwiers" %}
</td>
  <td width="500px" align="left" valign="center">
<a name="robert"></a>
{% include speaker-card.html
  avatarurl="robert.png"
  profilename="Robert Oostenveld" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="tim"></a>
{% include speaker-card.html
  avatarurl="tim.png"
  profilename="Tim van Mourik"
  affiliation="Donders Institute for Brain, Cognition and Behaviour"
  homepage="https://timvanmourik.com/"
  city="Nijmegen, The Netherlands"
  twitter="https://twitter.com/tim_van_mourik?lang=nl"                                  
  git="https://github.com/TimVanMourik"
  researchgate="https://www.researchgate.net/profile/Tim_Van_Mourik" %}
</td>
  <td width="500px" align="left" valign="center">
<a name="tony"></a>
{% include speaker-card.html
  avatarurl="tony.png"
  profilename="Tony Stöcker" 
  affiliation="MR physics group German Center for Neurodegenerative Diseases"
  city="Bonn, Germany"
  researchgate="https://www.researchgate.net/profile/Tony_Stoecker" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Open Source Neuroimaging Pipelines with GiraffeTools</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Numerical Simulation of MR physics</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>MR simulations based on the Bloch Equations are of high educational value. Further, they serve as essential tools in MRI method development, e.g. for MR sequence design and protocol optimization or generating ground truth data for image reconstruction and post-processing algorithms. This lecture provides insight into practical implementation of computer simulations based on classical MR physics. Analytical solutions versus numerical implementations will be discussed. Based on pictorial examples, an introduction to various MRI simulator software packages will be given. The JEMRIS simulation environment will serve for most of the examples shown in this lecture.</p>
</div>
</td>
</tr>

<tr>
<td width="500px" align="left" valign="center">
<a name="oliver"></a>
{% include speaker-card.html
  avatarurl="oliver.png"
  profilename="Oliver Schmid" %}
</td>
<td width="500px" align="left" valign="center">
<a name="stephan"></a>
{% include speaker-card.html
  avatarurl="stephan.png"
  profilename="Stephan Heunis"
  affiliation="Eindhoven University of Technology"
  city="Eindhoven, The Netherlands"
  homepage="https://www.fmrwhy.com/"
  git="https://github.com/jsheunis/"
  twitter="https://www.twitter.com/fmrwhy"
  researchgate="https://www.researchgate.net/profile/Stephan_Heunis2" %}
</td>
</tr>
<tr>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>TBA</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
<td width="500px">
<button class="accordion"><i class="fas fa-id-card" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Bio</button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>Stephan is a researcher and PhD candidate at the Electrical Engineering department of the Eindhoven University of Technology in the Netherlands. His research focuses on developing new acquisition and signal processing methods for functional neuroimaging that allow the real-time tracking and visualisation of distributed MRI brain activity patterns. Stephan is passionate about making research and scientific practice more transparent, rigorous and inclusive. He started the <a href="https://osceindhoven.github.io/">Open Science Community Eindhoven</a>, which is part of a wide Dutch network of researchers and university employees that focuses on improving scientific practice. He is also the founder of <a href="https://openmrbenelux.github.io/">OpenMR Benelux</a>, a community working on wider adoption of open science principles in MRI research through talks, discussions, workshops and hackathons.</p>
</div>
<button class="accordion"><i class="far fa-comments" style="position: relative; top: -5px; text-indent: 0px; vertical-align: middle; color:white"></i>&nbsp;&nbsp;Abstract: <b>Sharing GDPR compliant neuroimaging research data</b></button>
<div class="panel">
  <p align="justify" style="font-family: arial;"><br>TBA</p>
</div>
</td>
</tr>

</table>

</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    /* Toggle between adding and removing the "active" class,
    to highlight the button that controls the panel */
    this.classList.toggle("active");

   /* Toggle between hiding and showing the active panel */
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>

</body>
</html>
