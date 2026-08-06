# Griptape Nodes Directory

The repository serves as directory for nodes created for Griptape Nodes.

## Node Development Guide

If you’re building your own nodes or node libraries, start with the official guide:

- **[Griptape Nodes Node Development Guide](https://github.com/griptape-ai/griptape-nodes-node-development-guide)**

> 🧪 marks a Labs library — experimental and under active development. Expect breaking changes.

## 🛹 Griptape team contributed nodes

### 🏗️ Foundations

- 🧪 **[Modular Diffusers](https://github.com/griptape-ai/griptape-nodes-library-diffusers)** - compose image and video generation workflows from modular Diffusers pipeline stages — build a pipeline once, then chain, branch, or reorder the individual noise, diffuse, transform, and decode steps as nodes. Supports Flux, SDXL, Qwen-Image, Z-Image, LTX, and WAN, with LoRA and ControlNet.

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-diffusers"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🎲 3D

- **[Cartwheel](https://github.com/griptape-ai/griptape-nodes-library-cartwheel)** - AI-driven 3D character animation via the Cartwheel motion orchestration API, with text- and video-based motion generation, character creation, and mascot creation

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-cartwheel"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Hyper3D Rodin](https://github.com/griptape-ai/griptape-nodes-library-rodin)** - generate 3D models from text prompts or images using Hyper3D's Rodin API with support for text-to-3D, image-to-3D, multi-image generation, and multiple output formats (GLB/USDZ)

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-rodin"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[SAM 3D Objects](https://github.com/griptape-ai/griptape-nodes-sam-3d-objects-library)** - reconstruct full 3D shape, texture, and layout from a single image using Meta's SAM 3D Objects, with PLY/OBJ/GLB output and turntable video previews

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-sam-3d-objects-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🖼️ Image

- **[Annotate](https://github.com/griptape-ai/griptape-nodes-library-annotate)** - A Griptape Nodes library for drawing directly on images — no external tools required. Add paint strokes, labels, arrows, boxes, and ellipses right inside your workflow, then pass the result downstream to any node that accepts an image.

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-annotate"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Black Forest Labs](https://github.com/griptape-ai/griptape-nodes-library-blackforestlabs)** - interact with Black Forest Labs' FLUX APIs, enabling high-quality image generation and editing capabilities

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-blackforestlabs"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[CorridorKey](https://github.com/griptape-ai/griptape-nodes-library-corridorkey)** - neural green/blue screen keying for single frames using [CorridorKey](https://github.com/nikopueringer/CorridorKey), producing a clean straight alpha matte, a despilled foreground, and a premultiplied RGBA matte for compositing

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-corridorkey"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Decart](https://github.com/griptape-ai/griptape-nodes-library-decart)** - generate images from text prompts and transform existing images using Decart's Lucy Pro models with text-to-image and image-to-image capabilities

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-decart"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[FAL](https://github.com/griptape-ai/griptape-nodes-library-fal)** - upscale images using the SeedVR2 model directly via the fal.ai API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-fal"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Google AI](https://github.com/griptape-ai/griptape-nodes-library-googleai)** - generate images from text prompts using Google's Imagen & Gemini 2.5 Flash Image models with comprehensive customization options

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-googleai"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[LoRA Training](https://github.com/griptape-ai/griptape-nodes-lora-training-library)** - Generate training datasets and train LoRA models using [kohya-ss/sd-scripts](https://github.com/kohya-ss/sd-scripts)

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-lora-training-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Luma AI](https://github.com/griptape-ai/griptape-nodes-library-luma)** - generate and modify images using Luma's Photon models with support for image generation, modification, and intelligent aspect ratio reframing

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-luma"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Minimax](https://github.com/griptape-ai/griptape-nodes-library-minimax)** - generate high-quality images from text prompts with multiple aspect ratios, custom dimensions, and batch generation support

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-minimax"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[SAM3](https://github.com/griptape-ai/griptape-nodes-library-sam3)** - promptable segmentation for images (and videos) using Facebook's SAM3 model

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-sam3"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Topaz Labs](https://github.com/griptape-ai/griptape-nodes-library-topazlabs)** - denoise and enhance images with Topaz Labs models via their API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-topazlabs"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🎥 Video

- **[CorridorKey](https://github.com/griptape-ai/griptape-nodes-library-corridorkey)** - neural green/blue screen keying across a video clip or image sequence using [CorridorKey](https://github.com/nikopueringer/CorridorKey), with a choice of BiRefNet, GVM, or VideoMaMa as the per-frame alpha hint source

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-corridorkey"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Decart](https://github.com/griptape-ai/griptape-nodes-library-decart)** - generate videos from text prompts, convert images to videos, and transform existing videos using Decart's Lucy Dev and Lucy Pro models with text-to-video, image-to-video, and video-to-video capabilities

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-decart"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[FAL](https://github.com/griptape-ai/griptape-nodes-library-fal)** - upscale videos using the SeedVR2 model directly via the fal.ai API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-fal"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Google AI](https://github.com/griptape-ai/griptape-nodes-library-googleai)** - generate high-quality videos from text prompts and images using Google's Veo model with advanced controls for aspect ratio, resolution, and duration

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-googleai"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[InfiniteTalk](https://github.com/griptape-ai/griptape-nodes-infinite-talk-library)** - audio-driven talking video generation with InfiniteTalk — animate a still image to speak driving audio, or dub an existing video with new audio

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-infinite-talk-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Kling](https://github.com/griptape-ai/griptape-nodes-library-kling)** - generate videos from text prompts, images, or extend existing videos

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-kling"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Luma AI](https://github.com/griptape-ai/griptape-nodes-library-luma)** - generate, modify, and reframe videos using Luma's Ray models with support for text-to-video, image-to-video, style transfer, prompt-based editing, and intelligent aspect ratio changes

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-luma"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Minimax](https://github.com/griptape-ai/griptape-nodes-library-minimax)** - generate videos from text prompts, animate images, or create smooth transitions between keyframes with advanced camera controls and multiple resolution options

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-minimax"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[MiniMax-Remover](https://github.com/griptape-ai/griptape-nodes-minimax-remover-library)** - AI-powered video object removal using the MiniMax-Remover diffusion model with mask guidance

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-minimax-remover-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[RunwayML](https://github.com/griptape-ai/griptape-nodes-library-runwayml)** - generate videos from images and text prompts

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-runwayml"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[SAM3](https://github.com/griptape-ai/griptape-nodes-library-sam3)** - promptable segmentation for videos (and images) using Facebook's SAM3 model

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-sam3"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Topaz Labs](https://github.com/griptape-ai/griptape-nodes-library-topazlabs)** - upscale and denoise videos and perform frame interpolation to 60fps with Topaz Labs models via their API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-topazlabs"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[VOID](https://github.com/griptape-ai/griptape-nodes-void-library)** - physics-aware video object removal using [Netflix's VOID model](https://github.com/Netflix/void-model)

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-void-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🎵 Audio

- **[Chatterbox](https://github.com/griptape-ai/griptape-nodes-chatterbox-library)** - text-to-speech with voice cloning using Chatterbox TTS, supporting 23+ languages

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-chatterbox-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[ElevenLabs](https://github.com/griptape-ai/griptape-nodes-library-elevenlabs)** - high-quality text-to-speech, voice cloning, voice design, voice changer, sound effects generation, and music generation using ElevenLabs' API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-elevenlabs"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Google AI](https://github.com/griptape-ai/griptape-nodes-library-googleai)** - generate 30-second instrumental music using Google's Lyria model with creative prompt guidance and copyright protection

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-googleai"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[ACE-Step-1.5](https://github.com/griptape-ai/griptape-nodes-ace-step-1.5-library)** - a highly efficient open-source music foundation model that brings commercial-grade generation to consumer hardware

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-ace-step-1.5-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[SAM Audio](https://github.com/griptape-ai/griptape-nodes-sam-audio-library)** - isolate specific sounds from an audio track using text, temporal, or span prompts with Meta's SAM Audio model

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-sam-audio-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🔍 Media Analysis

- **[Depth Anything 3](https://github.com/griptape-ai/griptape-nodes-depth-anything-3-library)** - monocular depth estimation from images and videos using the Depth Anything 3 models

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-depth-anything-3-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Google AI](https://github.com/griptape-ai/griptape-nodes-library-googleai)** - analyze images, videos, and audio using Google's Gemini model with media description capabilities and precise timecode extraction

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-googleai"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[TwelveLabs](https://github.com/griptape-ai/griptape-nodes-library-twelve-labs)** - index, search, and analyze videos via the TwelveLabs API, routed through the Griptape Cloud proxy

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-twelve-labs"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🖥️ Display Utilities

- **[Google AI](https://github.com/griptape-ai/griptape-nodes-library-googleai)** - dynamic multi-video and multi-audio display nodes with grid layouts and individual output ports

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-googleai"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🎬 VFX / Color & Image I/O

- **[OpenColorIO](https://github.com/griptape-ai/griptape-nodes-library-opencolorio)** - professional color management built on [OpenColorIO](https://opencolorio.org/) (OCIO), the industry-standard color management system used across film, VFX, and animation pipelines

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-opencolorio"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[OpenEXR](https://github.com/griptape-ai/griptape-nodes-library-openexr)** - load, inspect, display, and save [OpenEXR](https://openexr.com/) image files for VFX and HDR pipelines

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-openexr"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 💻 Third Party Tools/Software

- **[Autodesk Flow Production Tracking](https://github.com/griptape-ai/griptape-nodes-library-flow-production-tracking)** - connect to Autodesk Flow Production Tracking (formerly ShotGrid) to create, update, and query projects, assets, tasks, and entities

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-flow-production-tracking"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[AWS](https://github.com/griptape-ai/griptape-nodes-aws-library)** - upload files to and download files from AWS S3 using boto3 credentials

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-aws-library"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Blender](https://github.com/griptape-ai/griptape-nodes-library-blender)** - Nodes and MCP server for Blender

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-blender"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Google Maps](https://github.com/griptape-ai/griptape-nodes-library-maps)** - fetch Google Street View images from an address or lat/lng coordinates via the Google Street View Static API

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-maps"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Neo4j](https://github.com/griptape-ai/griptape-nodes-library-neo4j)** - Nodes for managing and accessing a [Neo4j graph database](https://neo4j.com/)

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-neo4j"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[Nuke](https://github.com/griptape-ai/griptape-nodes-library-nuke)** - publish and work with [Foundry Nuke](https://www.foundry.com/products/nuke-family/nuke) from Griptape Nodes

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-nuke"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

- **[OpenAssetIO](https://github.com/griptape-ai/griptape-nodes-library-openassetio)** - resolve and publish asset metadata between Griptape Nodes and any OpenAssetIO-compatible asset management system

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-openassetio"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### ☁️ Workflow Execution

- **[AWS Deadline Cloud](https://github.com/griptape-ai/griptape-nodes-library-deadline-cloud)** - Submit Nodes workflow executions as [Deadline Cloud Jobs](https://docs.aws.amazon.com/deadline-cloud/latest/userguide/deadline-cloud-jobs.html), with powerful worker instances and parallel exeuction

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/griptape-ai/griptape-nodes-library-deadline-cloud"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

## 🧑‍🤝‍🧑 Community contributed nodes

### 🖼️ Image

- **[Storyboard](https://github.com/ian-griptape-ai/griptape-nodes-library-storyboard)** - create storyboard grid layouts from multiple images with customizable columns, padding, and output resolutions

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/ian-griptape-ai/griptape-nodes-library-storyboard"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🎵 Audio

- **[Suno (Unofficial)](https://github.com/ian-griptape-ai/griptape-nodes-libary-suno)** - generate AI-powered music tracks using the Suno API with custom lyrics, styles, vocal preferences, and multiple model versions

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/ian-griptape-ai/griptape-nodes-libary-suno"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>

### 🔧 Miscellaneous

- **[SendGrid](https://github.com/ian-griptape-ai/griptape-nodes-library-sendgrid)** - send emails through the SendGrid API with support for plain text, HTML content, and multiple attachment types

  <p align="right"><a href="https://nodes.griptape.ai/#library-management?git=https://github.com/ian-griptape-ai/griptape-nodes-library-sendgrid"><img src="images/add_to_griptape_nodes.png" width="150" alt="Add to Griptape Nodes"></a></p>
