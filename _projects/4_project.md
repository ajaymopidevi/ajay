---
layout: page
title: Grouped Bert for Multi-label Classification
img: assets/img/6.jpg
description: 
importance: 3
category: work
---

<a href="https://valueeval.webis.de/">SemEval 2023 Task 4: ValueEval: Identification of Human Values behind Arguments </a>

 Instead of the modelling the task as a classification problem, we modeled as Natural Language Inference (NIL) problem which determines the logical relationship (human values- output labels) between the argument and the conclusion.

 Designed Grouped-BERT for Multi-label identification of values behind arguments.

<div class="row">
    <div class="col-sm mt-md-0">
        {% include figure.html path="assets/img/4.png" title="Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>







<div>
  <h2>Results</h2>
  <table>
    <tr>
      <th>Model</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1</th>
      <th>Accuracy</th>
    </tr>
    <tr>
      <td>1-Baseline</td>
      <td>0.18</td>
      <td>1.0</td>
      <td>0.28</td>
      <td>0.18</td>
    </tr>
    <tr>
      <td>SVM</td>
      <td>0.30</td>
      <td>0.30</td>
      <td>0.3</td>
      <td>0.77</td>
    </tr>
    <tr>
      <td>BERT</td>
      <td>0.39</td>
      <td>0.30</td>
      <td>0.34</td>
      <td>0.84</td>
    </tr>
    <tr>
      <td>L-label classifier</td>
      <td>0.29</td>
      <td>0.48</td>
      <td>0.36</td>
      <td>0.76</td>
    </tr>
    <tr>
      <td>L-Binary classifiers</td>
      <td>0.3</td>
      <td>0.45</td>
      <td>0.35</td>
      <td>0.77</td>
    </tr>
    <tr>
      <td>Hybrid + CE loss</td>
      <td>0.32</td>
      <td>0.42</td>
      <td>0.39</td>
      <td>0.77</td>
    </tr>
    <tr>
      <td>Hybrid + CE + HD loss</td>
      <td>0.33</td>
      <td>0.43</td>
      <td>0.40</td>
      <td>0.77</td>
    </tr>
  </table>
</div>






<div class="row">
    <div class="col-sm mt-md-0">
        {% include figure.html path="assets/img/5.png" title="Comparison of individual test set F1 scores for each of the labels by the different models" class="img-fluid rounded z-depth-1" %}
    </div>
</div>