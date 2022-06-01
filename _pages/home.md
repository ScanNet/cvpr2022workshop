---
layout: project
urltitle:  "ScanNet Indoor Scene Understanding Challenge"
title: "ScanNet Indoor Scene Understanding Challenge"
categories: cvpr, workshop, computer vision, computer graphics, visual learning, simulation environments, robotics, machine learning, natural language processing, reinforcement learning
permalink: /
favicon: /static/img/ico/favicon.png
bibtex: true
paper: true
acknowledgements: ""
---

<br>
<div class="row">
  <div class="col-xs-12">
    <center><h1>ScanNet Indoor Scene Understanding Challenge</h1></center>
    <center><h2>CVPR 2022 Workshop, New Orleans, LA</h2></center>
    <center><h3 style="color:darkblue;font-weight:100">June 19, 2022, Afternoon</h3></center> <!-- location-->
  </div>
</div>

<hr>

<div class="row" id="intro">
  <div class="col-md-12">
    <img src="{{ "/static/img/splash.jpg" | prepend:site.baseurl }}">
  </div>
</div>

<br>
<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Introduction</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      3D scene understanding for indoor environments is becoming an increasingly important area.
      Application domains such as augmented and virtual reality, computational photography, interior design, and autonomous mobile robots all require a deep understanding of 3D interior spaces, the semantics of objects that are present, and their relative configurations in 3D space.
    </p>
    <p>
      We present the first comprehensive challenge for 3D scene understanding of entire rooms at the object instance-level with 5 tasks based on the ScanNet dataset.
      The ScanNet dataset is a large-scale semantically annotated dataset of 3D mesh reconstructions of interior spaces (approx. 1500 rooms and 2.5 million RGB-D frames).
      It is used by more than 480 research groups to develop and benchmark state-of-the-art approaches in semantic scene understanding.
      A key goal of this challenge is to compare state-of-the-art approaches operating on image data (including RGB-D) with approaches operating directly on 3D data (point cloud, or surface mesh representations).
      Additionally, we pose both object category label prediction (commonly referred to as semantic segmentation), and instance-level object recognition (object instance prediction and category label prediction).
      We propose five tasks that cover this space:
    </p>
    <ul>
      <li>
        <strong>2D semantic label prediction</strong>: prediction of object category labels from 2D image representation
      </li>
      <li>
        <strong>2D semantic instance prediction</strong>: prediction of object instance and category labels from 2D image representation
      </li>
      <li>
        <strong>3D semantic label prediction</strong>: prediction of object category labels from 3D representation
      </li>
      <li>
        <strong>3D semantic instance prediction</strong>: prediction of object instance and category labels from 3D representation
      </li>
      <li>
        <strong>Scene type classification</strong>: classification of entire 3D room into a scene type
      </li>
    </ul>
      <h3 style="color:orange;font-weight:800">Highlight - Data Efficient Challenge!</h3>
    <p>In the data efficient challenge, training is conducted on  Limited Scene Reconstructions (LR) or Limited Scene Annotations (LA), for the tasks of 3D Semantic Segmentation, Instance Segmentation and Object Detection. 
    </p>
    <p>
      For each task, challenge participants are provided with prepared training, validation, and test datasets, and automated evaluation scripts.
      In addition to the public train-val-test split, benchmarking is done on a hidden test set whose raw data can be downloaded without annotations; in order to participate in the benchmark, the predictions on the hidden test set are uploaded to the evaluation server, where they are evaluated.
      Submission is restricted to submissions every two weeks to avoid finetuning on the test dataset.
      See more details at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/documentation">http://kaldir.vc.in.tum.de/scannet_benchmark/documentation</a> if you would like to participate in the challenge.
      The evaluation server leaderboard is live at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/">http://kaldir.vc.in.tum.de/scannet_benchmark/</a>.
      See the new data efficient <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient/documentation">documentation</a> and <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/data_efficient">leaderboard</a>!.
    </p>
  </div>
</div>
<br>

<div class="row" id="tasks">
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic instance prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic instance prediction</p>
  </div>
  <!-- <div class="col-md-4">
    <p>&nbsp;</p>
  </div> -->
  <!-- <div class="col-md-4">
    <img src="{{ "/static/img/scene_type_classification.jpg" | prepend:site.baseurl }}">
    <p>Scene type classification</p>
  </div> -->
</div>

<!-- 
<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>
 -->
 
<!-- 
<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr><td>TBD</td><td>TBD</td></tr>
        <tr>
          <td>Poster Submission Deadline</td>
          <td>May 20 2020</td>
        </tr>
        <tr>
          <td>Notification to Authors</td>
          <td>May 25 2020</td>
        </tr>
        <tr>
          <td>Workshop Date</td>
          <td>June 19 2020</td>
        </tr>
      </tbody>
    </table>
  </div>
</div><br>
 -->
<!-- 
<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Posters</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      To submit a poster to the workshop, please email the poster as .pdf file to scannet@googlegroups.com.
    </p>
  </div>
</div><br>
-->

<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Schedule (All times in CDT)</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
     <table class="table table-striped">
      <tbody>
        <tr>
          <td>Welcome and Introduction</td>
          <td>12:50pm - 1:00pm</td>
        </tr>
        <tr>
          <td>Invited Talk: Peter Kontschieder</td>
          <td>1:00pm - 1:50pm</td>
        </tr>
        <tr>
          <td>Winner Talk 1</td>
          <td>1:50pm - 2:05pm</td>
        </tr>
        <tr>
          <td>Winner Talk 2</td>
          <td>2:05pm - 2:20pm</td>
        </tr>
        <tr>
          <td>Winner Talk 3 </td>
          <td>2:20pm - 2:35pm</td>
        </tr>
        <tr>
          <td>Break</td>
          <td>2:35pm - 3:00pm</td>
        </tr>
        <tr>
          <td>Invited Talk: Francis Engelmann </td>
          <td>3:00pm - 3:50pm</td>
        </tr>
        <tr>
          <td>Invited Talk: Gim Hee Lee</td> 
          <td>4:00pm - 4:50pm</td>
        </tr>
        <tr>
          <td>Panel Discussion and Conclusion</td>
          <td>5:00pm - 5:45pm</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br>
<div class="row" id="speakers">
  <div class="col-xs-12">
    <h2>Invited Speakers</h2>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://www.comp.nus.edu.sg/~leegh/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/gim_hee_lee.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://www.comp.nus.edu.sg/~leegh/">Gim Hee Lee</a></b> is an Associate Professor at the Department of Computer Science at the National University of Singapore (NUS), where he leads the Computer Vision and Robotic Perception (CVRP) Laboratory. He was a researcher at Mitsubishi Electric Research Laboratories (MERL), Cambridge Massachusetts, USA from June 2014 to July 2015. Prior to MERL, he did his PhD in Computer Science at ETH Zurich from January 2009 to March 2014 under the supervision of Prof. Marc Pollefeys. He received his B.Eng with first class honors and M.Eng degrees from the Department of Mechanical Engineering at NUS in June 2005 and February 2008, respectively. He worked at DSO National Laboratories in Singapore as a Member of Technical Staff from August 2007 to December 2008. He has served as an Area Chair for BMVC 2020, 3DV 2020, CVPR 2021, ICCV 2021, BMVC 2021, WACV 2022 and ECCV 2022, and will be part of the organizing committee as one of the Program Chairs for 3DV 2022 and the Exhibition/Demo Chair for CVPR 2023.
    </p>
  </div>
</div><br>
<div class="row">
  <div class="col-md-12">
    <a href="https://francisengelmann.github.io/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/francis_engelmann.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://francisengelmann.github.io/">Francis Engelmann</a></b> is a postdoctoral fellow at the AI Center of ETH Zurich working with Prof. Dr. Siyu Tang and Prof. Dr. Otmar Hilliges. Previously, he completed his Ph.D. in Computer Vision, Machine Learning and 3D Scene Understanding in the Computer Vision Group of Prof. Dr. Bastian Leibe at RWTH Aachen University. His research focuses on 3D scene understanding, human-scene interaction and synthesis.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://scholar.google.com/citations?user=CxbDDRMAAAAJ&hl=en"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/peter_kontschieder.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://scholar.google.com/citations?user=CxbDDRMAAAAJ&hl=en">Peter Kontschieder</a></b> is a research scientist manager at Meta. He received his MSc and PhD degrees from the Graz University of Technology, Graz, Austria, in 2008 and 2013, respectively. From 2013-2016, he was a postdoctoral researcher with the Machine Intelligence and Perception Group, Microsoft Research in Cambridge, United Kingdom. In 2016, he joined Mapillary and founded Mapillary Research – Mapillary’s Research Lab focusing on basic research in computer vision and machine learning. With the acquisition of Mapillary in 2020, he became a research scientist manager with Facebook. He received the Marr Prize in 2015 for his contribution of Deep Neural Decision Forests, joining deep learning with decision forests. 
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-2">
    <a href="https://angeladai.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angela.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angeladai.github.io/">Angela Dai</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://angelxuanchang.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angel.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angelxuanchang.github.io/">Angel X. Chang</a>
      <h6>Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://msavva.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/manolis.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://msavva.github.io/">Manolis Savva</a>
      <h6>Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">
      <img class="people-pic" src="{{ "/static/img/people/matthias.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">Matthias Niessner</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgments</h2>
  </div>
</div>
<a name="/acknowledgements"></a>
<div class="row">
  <div class="col-xs-12">
    <p>
      Thanks to <span style="color:#1a1aff;font-weight:400;"> <a href="https://visualdialog.org/">visualdialog.org</a></span> for the webpage format.
    </p>
  </div>
</div>
