---
title: 'Background Job System'
description: 'Async image processor that crops, downscales, and resizes images for Discord avatar restrictions, with results stored in the cloud.'
pubDate: 2026-01-29
githubUrl: 'https://github.com/KristerJLawlor/Background-Job-System'
tags: ['Java', 'JavaScript', 'Docker', 'Background Jobs', 'Cloud Storage']
---

## Overview

A web-based image processing tool that handles cropping, downscaling, and resizing images to meet Discord avatar size and dimension restrictions. Supports both single-image and batch processing workflows.

Processing is handled as an asynchronous background task so the user isn't blocked waiting for results — jobs are queued, processed in the background, and the output is stored in the cloud for retrieval.

## Features

- Single and batch image processing modes
- Automatic cropping and resizing to Discord avatar specifications
- Asynchronous job execution via a background task queue
- Cloud storage for processed results

## Tech Stack

- **Java** — core application and background job execution
- **JavaScript / HTML / CSS** — web front-end
- **Docker** — containerized deployment
