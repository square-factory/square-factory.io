---
title: "A propos"
page_header_bg: "images/bg/section-bg4.jpg"
description: "This is meta description"
layout: "about"
draft: false

######################### Counter ####################
counter:
  enable: true
  title : "En quelques <b>chiffres</b>"
  counter_item:
  # counter item loop
  - icon : "ti-thumb-up" # here we use themify icon pack : https://themify.me/themify-icons
    title : "experts à votre service"
    count : "1730"
    unit : "+"
    
  # counter item loop
  - icon : "ti-face-smile" # here we use themify icon pack : https://themify.me/themify-icons
    title : "clients déjà aidés"
    count : "12"
    unit : ""
    
  # counter item loop
  - icon : "ti-thumb-up" # here we use themify icon pack : https://themify.me/themify-icons
    title : "personnes formées"
    count : "125"
    unit : "+"

####################### Promo video ######################
video:
  enable: false
  title : "TOCHANGE-Example video"
  video_thumb: "images/about/img-34.png"
  video_embed_link : "https://www.youtube.com/embed/ScMzIvxBSi4"
  content : "
  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint earum, eos esse non error facilis ad, maiores eum quae vero libero voluptas! Reprehenderit sunt similique, quae quidem voluptatem odit natus.


  * TOCHANGE-liste1

  * TOCHANGE-liste2

  * TOCHANGE-liste3
  "
  button:
    enable : true
    label : "TOCHANGE-button"
    link : "service"

################################## Team ########################
team:
  enable : true
  title : "Nos experts"
  content : "Dicta cupiditate, incidunt quia obcaecati itaque cumque, nostrum ipsum est voluptatibus, porro provident a quam quibusdam. Ducimus possimus, nesciunt minima magni aspernatur."
  team_member:
  # team member loop
  - name : "Kyan"
    image : "images/370x420.png"
    designation : "Role4"

  # team member loop
  - name : "VictorBlanc"
    image : "images/370x420.png"
    designation : "Role1"
    
  # team member loop
  - name : "Victoria"
    image : "images/370x420.png"
    designation : "Role2"
    
  # team member loop
  - name : "Victor-san"
    image : "images/370x420.png"
    designation : "Role3"
    

################################ Clients ######################
clients:
  enable : true
  title : "Certifications"
  content : "Nos collaborateurs ont acqueris une reconnaissance via des certifications"
  logos:
  - "images/110px.png" # aws pro sa
  - "images/110px.png" # aws pro devops
  - "images/110px.png" # aws ass dev
  - "images/110px.png" # aws ass sys
  - "images/110px.png" # aws ass sa
  - "images/110px.png" # aws spe netwo
  - "images/110px.png" # aws spe secu
  - "images/110px.png" # aws spe database
  - "images/110px.png" # kube cka
  - "images/110px.png" # kube ckad
  - "images/110px.png" # gke
    
########################## Testimonial ########################
testimonial:
  enable: true
  # testimonial content comes from "data/homepage.yml" file.
---