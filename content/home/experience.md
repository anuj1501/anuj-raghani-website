---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Engineer
    company: Deutsche Bank
    company_url: ''
    company_logo: Deutsche
    location: India
    date_start: '2022-07-18'
    date_end: ''
    description: >-
      Chief Technology Office | Production Engineering | Service Automation

      * Contributed to developing an AI search engine that extracts semantic insights from incident 
        descriptions and recommends solutions from past resolved incident tickets, improving the bank’s 
        operational resilience.
      * Efforts have resulted in reduction of MTTD (Mean Time To Diagnose) by at least 53% and MTTR (Mean 
        Time To Recover) by at least 65% compared to manual ticket handling. 
      * Currently working on exploring approaches to optimize search retrieval and benchmarking state-of- 
        the-art Transformer models to improve accuracy.
      * Key part of another tribe that looks into ITSM data sourcing and warehousing, aiding in improving the 
        performance of data pull jobs.
      * Actively involved in the designing and implementation of web applications at scale for end users.

  - title: Data Science Intern
    company: Argoid
    company_url: 'https://www.argoid.ai/'
    company_logo: Argoid
    location: India
    date_start: '2021-12-15'
    date_end: '2021-09-01'
    description: >-
      * Worked thoroughly with an ecommerce client to create a recommendation engine with features like You May Also Like (YMAL) and 
        similar items. Tried various approaches and deployed jobs on Hadoop system for production usage.
      * View my work of recommendation engine here: https://odette.in/.
      * Researched on creating customer embeddings to understand and model their behavior and successfully improved the performance of the
        recommendations.

  - title: Summer Analyst
    company: Citi Bank
    company_url: ''
    company_logo: Citi
    location: India
    date_start: '2021-05-17'
    date_end: '2021-07-21'
    description: >-
      * Worked as a part of Equities Business Unit and implemented an ETL Pipeline to fetch configuration 
        details of various micro services hosted on different servers.
      * Also contributed in creating a client simulator which mimics orders placed by clients and helps QA 
        team understand the fixes required in the latest OMS releases.

  - title: Research Engineer Intern
    company: Spherical Defence
    company_url: ''
    company_logo: SD
    location: Remote
    date_start: '2021-05-15'
    date_end: '2021-02-01'
    description: >-
      * Focused on optimizing the accuracy-latency tradeoff to enhance the performance of their LLM API 
        service, a critical tool used by financial firms to detect anomalous transactions. 
      * Worked on novel SOTA techniques to reduce the training time of models and the inference time and
        explored techniques like TensorRT, training on multiple GPUs, Mixed precision training (FP16).
      * Used Pytorch framework and pushed the final code into their research repositories.
  
  - title: Undergraduate Researcher
    company: Indrapasth Institue of Information Technology (IIIT Delhi)
    company_url: ''
    company_logo: iiitd
    location: Remote
    date_start: '2020-12-01'
    date_end: '2021-12-01'
    description: >-
      * Pursuing a thorough research on dynamic computation offloading of IOT devices in FOG Network 
        using deep reinforcement learning under Dr. Arani Bhattacharya. 
      * Conducted thorough literature surveys, analyzed and experimented with existing approaches and built 
        a framework for simulating this ecosystem.
design:
  columns: '2'
---
