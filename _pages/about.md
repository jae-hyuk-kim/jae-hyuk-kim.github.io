---
layout: about
title: Jaehyuk Kim
permalink: /

profile:
  align: left
  image: jae-hyuk-kim-2026.jpg
  image_circular: true
  address: "<div style='font-family: sans-serif; margin-top: 15px; line-height: 1.5;'><b style='font-size: 1.15rem;'>Jaehyuk Kim</b><br><span style='font-size: 0.9rem; color: #666;'>Ph.D. Candidate in ISE</span><br><span style='font-size: 0.9rem; color: #666;'>NC State University</span><hr style='margin: 10px 0; border-top: 1px solid #eee;'><div style='font-size: 0.9rem;'><i class='fas fa-map-marker-alt'></i> Raleigh, NC<br><i class='fas fa-envelope'></i> <a href='mailto:jkim226@ncsu.edu'>jkim226@ncsu.edu</a><br><i class='fas fa-graduation-cap'></i> <a href='https://scholar.google.com/citations?user=1CtgrgEAAAAJ&amp;view_op=list_works&amp;sortby=pubdate' target='_blank'>Google Scholar</a><br><i class='fab fa-linkedin'></i> <a href='https://www.linkedin.com/in/jaehyuk-kim-486a7b227/' target='_blank'>LinkedIn</a></div></div>"
  more_info: "<div style='font-family: sans-serif; margin-top: 15px; line-height: 1.5;'><b style='font-size: 1.15rem;'>Jaehyuk Kim</b><br><span style='font-size: 0.9rem; color: #666;'>Ph.D. Candidate in ISE</span><br><span style='font-size: 0.9rem; color: #666;'>NC State University</span><hr style='margin: 10px 0; border-top: 1px solid #eee;'><div style='font-size: 0.9rem;'><i class='fas fa-map-marker-alt'></i> Raleigh, NC<br><i class='fas fa-envelope'></i> <a href='mailto:jkim226@ncsu.edu'>jkim226@ncsu.edu</a><br><i class='fas fa-graduation-cap'></i> <a href='https://scholar.google.com/citations?user=1CtgrgEAAAAJ&amp;view_op=list_works&amp;sortby=pubdate' target='_blank'>Google Scholar</a><br><i class='fab fa-linkedin'></i> <a href='https://www.linkedin.com/in/jaehyuk-kim-486a7b227/' target='_blank'>LinkedIn</a></div></div>"
---

<style>
  /* 상단 기본 제목 영역을 숨깁니다 */
  .post-header { display: none; }

  a {
    color: #0056b3 !important; /* Academic Blue */
    text-decoration: none;
  }

  a:hover {
    color: #004494 !important; /* 마우스 올렸을 때 조금 더 진한 파란색 */
    text-decoration: underline;
  }
</style>

<div style="display: block; overflow: hidden; padding-left: 30px;" markdown="1">

<h1 style="margin-top: 0; padding-top: 0;">About Me</h1>

I am a Ph.D. candidate in the Department of Industrial and Systems Engineering at North Carolina State University, working under the supervision of Professor <a href="https://www.ise.ncsu.edu/people/oyozalti/" target="_blank">Osman Y. Özaltın</a>. My research centers on developing **mathematical models** and **efficient, scalable algorithms** for large-scale combinatorial optimization. I specialize in **sequential decision-making** problems under uncertainty within the **adaptive robust optimization** framework, which are formulated as two- and multi-stage models. I develop **advanced solution methodologies**, including both decomposition-based and ML-augmented approaches, to overcome the computational intractability inherent in these models, applying them to complex societal systems where system resilience and operational efficiency are paramount.

<br>

## Research Interests

* Sequential Decision-Making under Uncertainty
* Robust/Stochastic Optimization
* Large-scale Combinatorial Optimization 
* ML-Augmented Optimization

<br>

## Education

| Degree | Major | Institution | Year |
| :--- | :--- | :--- | :--- |
| **Ph.D.** | Industrial and Systems Engineering<br><small>(Minor: Operations Research)</small><br><span style="font-size: 11px; color: #666;">GPA: 3.8 / 4.0</span> | NC State University | 2027 (Exp.) |
| **M.S.** | Industrial Management Engineering<br><span style="font-size: 11px; color: #666;">GPA: 4.2 / 4.5</span> | Korea University | 2022 |
| **B.S.** | Mechanical Engineering<br><span style="font-size: 11px; color: #666;">GPA: 4.1 / 4.5</span> | Chung-Ang University | 2019 |
| **B.S.** | Electrical and Electronics Engineering<br><span style="font-size: 11px; color: #666;">GPA: 4.2 / 4.5</span> | Chung-Ang University | 2019 |

<br>

## Research & Publications

* **Jaehyuk Kim**, M. Bodur, M. E. Mayorga, and O. Y. Özaltın, "Evacuation Planning for Disaster Preparedness: An Adaptive Robust Optimization Approach", *Submitted*. [<a href="https://arxiv.org/pdf/2608.04225" target="_blank">Link</a>]
  <details>
  <summary style="cursor: pointer; color: gray; font-size: 0.9em;">View full contributions</summary>
  <ul style="margin-top: 10px; font-size: 0.95em; list-style-type: circle;">
    <li>We develop, to our knowledge, the first two-stage adaptive robust evacuation planning framework that jointly optimizes strategic relief supply prepositioning and adaptive post-disaster relief distribution under demand uncertainty while integrating shelter location and evacuation route planning.</li>
    <li>Within the proposed framework, we formulate two traffic assignment variants: a centralized constrained system-optimal model and a decentralized user route choice model. The latter introduces a novel decision-dependent structure in which evacuees choose among acceptable routes, with the choice set determined by shelter opening decisions. Together, these variants enable an assessment of the operational value of centralized route planning under uncertainty.</li>
    <li>We provide theoretical complexity insights for adaptive robust evacuation planning, showing that the computational difficulty arises from multiple layers of the problem: the deterministic version is NP-hard and the full adaptive robust decision problem with a bounded polyhedral uncertainty set is $\Sigma_2^p$-complete. We also identify a polynomially solvable recourse subproblem, clarifying which part remains tractable.</li>
    <li>Building on the complexity insights, we develop a partition-and-bound algorithm with a problem-tailored active-partition refinement rule that produces strong upper and lower bounds while controlling the growth of the search tree. Computational experiments show that the method achieves better solution quality within comparable solution time to existing partition-based benchmarks. Although designed to efficiently solve the proposed evacuation planning model, the method is generic and can be applied to other two-stage adaptive robust optimization problems with mixed-integer recourse.</li>
    <li>We provide computational and managerial insights through a case study on the Sioux Falls network, demonstrating the practical tractability of the proposed approach and characterizing the trade-off between unmet relief item demand and evacuation time, the value of centralized route planning, and the benefits of adaptive post-disaster relief distribution under varying resource availability and operational priorities.</li>
  </ul>
  </details>
* **Jaehyuk Kim** and O. Y. Özaltın, "Multistage Adaptive Robust Optimization for Resilient Power Systems: A Machine Learning-Augmented Approach", *Working Paper*.
* **Jaehyuk Kim**, O. Y. Özaltın, and N. R. Chowdhury, "Contextual Risk-Averse Stochastic Optimization for Evacuation Planning: A Decision-focused Learning Approach", *In Preparation*.
* **Jaehyuk Kim** and Y. Seo (2022), "Integrated Optimization of Facility Layout and Job Shop Scheduling in a Reconfigurable Manufacturing System", *Journal of the Korean Institute of Industrial Engineers*.
* **Jaehyuk Kim** and S. Kim (2021), "A Study of Productivity Analysis Method Based on Manufacturing Big Data Using the FOM System in the FOMs Package", *Journal of the Korean Society of Manufacturing Technology Engineers*.
  
<br>

## Conferences & Proceedings

* **Jaehyuk Kim**, M. Bodur, M. E. Mayorga, and O. Y. Özaltın, "Shelter Location and Evacuation Planning under Demand Uncertainty: An Adaptive Robust Optimization Approach", *INFORMS Annual Meeting 2025*. 
* A. Abu Orabi, **Jaehyuk Kim**, A. R. Escobedo, and O. Y. Özaltın, "Data-Driven Solutions for Waste Material Composition Prediction: Bridging Industrial Engineering and Sustainability", *Proceedings of the IISE Annual Conference & Expo 2025*<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Selected as one of three finalists for the Sustainable Development Best Track Paper Award.*</small>

<br>

## Honors & Awards

* **Edward P. Fitts Fellowship**, Dept. of ISE, NCSU, 2023<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Highly competitive, fully funded fellowship for academic excellence and research potential.*</small>
* **Edward P. Fitts Fellowship**, Dept. of ISE, NCSU, 2022<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Highly competitive, fully funded fellowship for academic excellence and research potential.*</small>
* **Full Academic Excellence Scholarship**, Chung-Ang University, 2019<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Awarded for ranking 1st out of 100+ students in the department.*</small>
* **Full Academic Excellence Scholarship**, Chung-Ang University, 2018<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Awarded for ranking 1st out of 100+ students in the department.*</small>
* **Grand Prize in Winter Internship Program Contest**, Chung-Ang University, 2018<br>&nbsp;&nbsp;&nbsp;&nbsp;<small>*Awarded for ranking 1st in the Mechanical Engineering Short Term Research Program.*</small>

<br>

## Patents & Books

* S. Kim and **Jaehyuk Kim** (2021). "Big data analysis detailed process and method of FOM analysis module in smart factory FOMs Package", South Korea, *Patent No. 10-2021-0052334*.
* S. Kim and **Jaehyuk Kim** (2020). "Smart Factory FOMs Package and Method for Smart Manufacturing Innovation", South Korea, *Patent No. 10-2020-0032342*.
* S. Lee, K. Roh, S. Kim, and **Jaehyuk Kim** (2020). *Site Control of Smart Manufacturing*, South Korea, ISBN: 978-89-6345-295-1-13320.

</div>

<!-- 구글 검색엔진을 위한 프로필 정보 -->
<script type="application/ld+json">
{
  "@context": "https://schema.org/",
  "@type": "Person",
  "name": "Jaehyuk Kim",
  "jobTitle": "Ph.D. Candidate",
  "affiliation": {
    "@type": "Organization",
    "name": "North Carolina State University"
  },
  "url": "https://.github.io/",
  "image": "https://jae-hyuk-kim.github.io/assets/img/jae-hyuk-kim-2026.jpg"
}
</script>
