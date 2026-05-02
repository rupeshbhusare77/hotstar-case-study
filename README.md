# Hotstar: A System Design Case Study

Welcome to my repository! This project is an in-depth system design case study exploring how India's largest OTT platform handles massive scale and live streaming traffic.

## 📖 Project Overview
Ever wondered how Hotstar streams live cricket matches to over 61 million users at the exact same time without crashing? 

As a Computer Science student, I developed this case study for my course, **CS540: Fundamentals of Computing Systems Design**, to understand the engineering magic behind it. Along with my team, we broke down Hotstar's architecture to see how they tackle the "Thundering Herd" problem, manage huge traffic tsunamis, and deliver buffer-free video to millions of different devices across varying network speeds.

This repository contains our complete research, translated into an easy-to-understand infographic and a detailed presentation.

## 📂 What's in this Repo?
*   **The Infographic (`Hotstar_case_study_Infograph.pdf`):** A single-page, high-level visual breakdown of the entire architecture, from the API gateway to the data storage layer.
*   **The Presentation:** The detailed slide deck covering the business model, functional requirements, load testing, and cloud infrastructure. Due to file size limits, the presentation is hosted externally. 
    *   🔗 [**Get the Full Presentation (Google Drive)**](https://docs.google.com/presentation/d/1ZLHoSJaNoq3jlO_TLx4e-50f9ujyqouW/edit?usp=sharing&ouid=102098631087423746617&rtpof=true&sd=true)

## 👁️ How to View the Work
The best way to get a quick understanding of the system is to look at the **Infographic**. You can get pdf here in repo itself, or [**click here**](link) for webview.

If you want to dive deeper into the technical details and our research, get the ppt from [**here**](https://docs.google.com/presentation/d/1ZLHoSJaNoq3jlO_TLx4e-50f9ujyqouW/edit?usp=sharing&ouid=102098631087423746617&rtpof=true&sd=true)

## 🚀 Key Concepts Explored
Through this case study, we learned about:
*   **Predictive AI Scaling:** How to spin up servers *before* a traffic spike hits, rather than waiting for it to happen.
*   **The Video Pipeline:** How a live camera feed is ingested, transcoded into different qualities, and sent through CDNs in real-time.
*   **System Resilience:** Using "Load Shedding" to turn off non-essential features (like recommendations) just to keep the main video playing during peak traffic.

## 👨‍💻 The Team
*   **Rupesh Hemant Bhusare**
*   **Bhavanam Harsha Vardhan Reddy**
*   **Ritesh Prakashrao Phulari**
