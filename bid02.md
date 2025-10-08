# **Project Bid for P2025-18 Translating Videos**

## **Team 20205.24**

<center>Yiqi Cheng · Xuanchen Qian · Yijun Sun · Xiaoyan Gong · Ding Shao</center>

---

## **Project Motivation and Team Suitability**

Our team is highly motivated to participate in this project because it sits at the intersection of language processing, deep learning, and multimedia systems—areas that align with our collective technical interests and backgrounds.
One of our members has practical experience in translation and video editing, having used tools such as **Whisper AI** and **FFmpeg** to translate and re-dub YouTube videos for publishing on Bilibili. This prior exposure provides valuable insight into the challenges of speech recognition, timing synchronization, and language localization in video content.

Our team also includes members with strong programming and software engineering backgrounds, allowing us to design and implement an efficient, AI-assisted video translation system that delivers natural and accurate multilingual outputs.

## Team Member Profile

- Ding Shao: Completed the **UI/UX Design and Interactive Systems Program** at the National University of Singapore (NUS) School of Computing, has hands-on experience on software engineering and user experience design. Has formal experience in machine learning and data processing.
- Xiaoyan Gong: Member of a Youtuber's official translator team, experienced with using AI to translate and re-dub videos. Could give out suggestions in multiple aspects including the automation of video processing and choosing which AI framework to use.
- Xuanchen Qian: Has foundational experience with AI model implemention in computer vision, could provide insight in video postprocess such lip synchronization.
- Yijun Sun: Awarded third prize in the Dimension Cup National Mathematical Modeling Competition, capable for forming mathematical model for this project.
- Yiqi Cheng: Has hands-on experience with Python and AI model implementation through participation in the FURP project. Demonstrates strong analytical thinking, adaptability, and an ability to apply algorithm strategies to practical applications.

---

## **Initial Project Ideas**

We aim to develop a **user-friendly, AI-assisted video translation system** that can automatically process English videos and generate Chinese-translated versions with precise lip synchronization. The system will consist of the following core components:

1. **Frontend Interface**

   * Provide a simple and intuitive web or desktop interface for users to upload videos, configure subtitle and translation options, and preview results.
   * Include basic settings for voice style, subtitle layout, and translation mode (literal vs. adaptive).

2. **AI-Assisted Backend**

   * Use **Whisper** or similar Automatic Speech Recognition models to transcribe English audio.
   * Apply a **Neural Machine Translation** model (or use DeepL) for English–Chinese translation.
   * Employ **TTS (Text-to-Speech)** and **lip-sync correction** modules (e.g., Wav2Lip) to generate synchronized dubbed audio.
   * Use **FFmpeg** for final video composition, audio mixing, and subtitle embedding.

3. **System Design Goals**

   * Ensure modularity and scalability for future integration with other languages or voice styles.
   * Optimize inference pipeline for efficiency and output quality.
   * Provide logging, progress tracking, and error handling for usability.

---

## **Estimated Timeline and Deliverables Schedule**

| **Duration**        | **Main Objectives and Deliverables**                                                                                                            |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Oct 13 – Oct 25** | Conduct background research on existing video translation pipelines and lip-syncing methods. Define functional and non-functional requirements. |
| **Oct 26 – Nov 10** | Set up development environment; prepare datasets and APIs for ASR, translation, and TTS modules.                                                |
| **Nov 11 – Dec 1**  | Develop and test the backend translation and synchronization pipeline. Begin frontend UI prototyping.                                           |
| **Dec 2 – Dec 4**   | Prepare and submit **Interim Report**, including design documents, prototype screenshots, and progress summary.                                 |
| **Dec 5 – Dec 20**  | Integrate frontend and backend; enable basic end-to-end translation workflow.                                                                   |
| **Dec 21 – Jan 15** | Optimize lip-sync alignment and test translation accuracy. Conduct user testing with sample videos.                                             |
| **Jan 16 – Feb 15** | Improve performance, error handling, and user interface. Add optional features (e.g., subtitle export, multi-language support).                 |
| **Feb 16 – Mar 15** | Final testing, documentation, and performance evaluation.                                                                                       |
| **Mar 16 – Mar 25** | Final presentation, demonstration, and submission of the **Final Report**.                                                                      |

---

## **Key Milestones and Demonstrable Deliverables**

| **Milestone**                                 | **Date**  | **Deliverable**                                                                    |
| --------------------------------------------- | --------- | ---------------------------------------------------------------------------------- |
| **Requirement Analysis Complete**             | Oct 25    | Requirement specification document finalized.                                      |
| **Core ASR + Translation Pipeline Prototype** | Dec 1     | Working prototype that can transcribe and translate speech.                        |
| **Interim Report Submission**                 | **Dec 4** | Interim report detailing architecture, methodology, and initial prototype results. |
| **End-to-End Translation System**             | Dec 20    | Integrated system translating full videos with subtitles and audio output.         |
| **Lip-Sync Optimization**                     | Jan 15    | Improved synchronization between dubbed speech and speaker lip motion.             |
| **Final Demonstration**                       | Mar 25    | Fully functional AI-assisted video translation system and final documentation.     |

---

## **Expected Outcomes**

By the end of the project, we aim to deliver:

* A functional **English-to-Chinese video translation system** with natural lip synchronization.
* A **frontend interface** for uploading, configuring, and previewing translated videos.
* **Reusable AI pipeline** integrating ASR, NMT, and TTS components.
* Comprehensive **technical documentation** and a demonstration video showcasing the system.

This project will demonstrate the feasibility of automated multilingual video localization using state-of-the-art AI techniques and provide a foundation for future extensions to other languages and domains such as e-learning or media production.
