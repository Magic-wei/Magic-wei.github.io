---
title: "Projects"
layout: splash
permalink: /projects_index/
classes: wide
excerpt: "about autonomous driving and autonomous systems."
header:
  overlay_color: "#000"
  overlay_filter: "0.2"
  overlay_image: ./assets/images/project_s.jpg
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"

feature_ugvchallenge2018:
  - image_path: /assets/images/toyota_2018.jpg
    alt: "placeholder image 2"
    title: "Unmanned Ground Vehicle Challenge 2018"
    excerpt: 'The competition was aimed at off-road complicated environment with high demands on the mobility of unmanned vehicles. As the leader of motion control group, I was responsible for the formulation of motion control framework, x-by-wire actuators redign and development and verification of motion control algorithms. To meet the requirements of operating on endure rough terrain, we identified the dynamic characteristics of our unmanned vehicles on various off-road terrain and developed dynamic-based speed tracking and acceleration control algorithms, and helped planning group improve speed planning in off-road scenes. Plus, since we were facing narrow and curving segments along with delayed steering control system, we developed and refined our MPC-based path tracking algorithms by considering the delays. Finally in this competition, we won the third and sixth place with two participating vehicles.'
#    url: "/ugvchallenge2018_project"
#    btn_label: "Read More"
#    btn_class: "btn--primary"

feature_path_tracking_review:
    - image_path: /assets/images/path_tracking_review.png
      alt: "placeholder image 2"
      title: "Path Tracking Algorithms Review and Verification"
      excerpt: 'Leading a group of four beginner-level members, I sponsored this research to review papers and implement some practical algorithms in V-REP and real vehicles to make better assessment for path tracking algorithms in a unified framework and platform. I developed a new framework for motion control algorithms for better developing and verifying, which unified the interfaces used in real vehicle platform and V-REP simulation platforms.'
#      url: "/path_tracking_review_project"
#      btn_label: "Read More"
#      btn_class: "btn--primary"

feature_row:
  - image_path: /assets/images/toyota_2016.jpg
    alt: "placeholder image 1"
    title: "Unmanned Ground Vehicle Challenge 2016"
    excerpt: "Designed, implemented and refined automatic shifting mechanisms and automatic steering mechanisms for two unmanned ground vehicles, and was responsible for hardware maintenance."
  - image_path: /assets/images/4d_rcs.png
    alt: "placeholder image 2"
    title: "4D/RCS Framework Development"
    excerpt: "Migrated path tracking algorithms to RCS framework."
  - image_path: /assets/images/minibus.png
    title: "Autonomous Minibus Development"
    excerpt: "Verified and improved path tracking algorithms for minibus trial operation in Shenzhen, China."

---

## Selected Projects

{% include feature_row id="feature_ugvchallenge2018" type="right" %}

{% include feature_row id="feature_path_tracking_review" type="left" %}

## Previous Projects

{% include feature_row %}
