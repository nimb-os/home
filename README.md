# NimbOS

## A Central Hub

This repository is intended to be a central hub for organizing and executing this project. Proposals that don't match an existing repo should be created as issues here. The wiki of this repo should be used for building a general knowledge base about navigating this project.

## Introduction

NimbOS is a project to generate a flavor of linux that is preferable to OS X as a desktop environment for developing and deploying cloud-based applications.

Some initial concepts we have include:

- Designed as a feature pack on top of `ubuntu:latest`
- Improve hi-dpi support
- Improve power management on laptops
- Make sure popular developer tools work seemlessly out-of-the-box
- Include a tiling window manager by default
- Extend cloud infrastructure to common desktop metaphors
  - folders symlinked to bucket storage
  - deploy directories as containers through the context menu
    - either docker local, fargate, vagrant, ec2, etc.
- Streamable desktop environment from cloud instance
- Touchbar support for all the people stuck on a newer MBP
