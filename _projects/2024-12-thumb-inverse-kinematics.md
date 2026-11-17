---
title: "Numerical Inverse Kinematics of the Human Thumb"
collection: projects
excerpt: "A Python implementation of inverse kinematics for the human thumb using a damped Jacobian pseudoinverse with null-space optimization to minimize joint-angle change while respecting anatomical joint limits."
date: 2024-12-01
date_range: "October – December 2024"
affiliation: "Independent project"
location: "Swarthmore, PA, USA"
header:
  teaser: projects/thumb-inverse-kinematics.png
pdfurl: /files/projects/thumb-inverse-kinematics.pdf
---

This project solved the inverse kinematics problem for the human thumb numerically in Python. A damped Jacobian pseudoinverse drives the fingertip toward target positions while remaining stable near singular configurations, and a null-space optimization term uses the remaining redundancy to minimize total joint-angle change and keep each joint within its anatomical range of motion.
