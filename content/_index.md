---
title: ''
date: 2026-08-11
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      username: admin

  - block: skills
    content:
      title: Skills
      text: ''
      username: admin
    design:
      columns: '1'

  - block: experience
    id: exper
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Independent AI Engineer
          company: Self-employed
          location: Paris, France (Remote worldwide)
          date_start: '2024-05-01'
          date_end: ''
          description: |2-
            • Independent engagements in production AI: LLM/RAG systems, agentic tool-use, computer vision on edge devices, embedded IoT with ML on top.
            • Architecture reviews for teams deploying open-weight LLMs on-prem (Ollama, vLLM, llama.cpp; NVIDIA CUDA vs Apple Silicon vs AMD trade-offs).
            • RAG pipelines with hybrid retrieval and citation-grounded generation.
            • Multi-camera edge CV on Jetson Orin quantized to INT8, deployed to production customer sites.
            • Industrial IoT: LoRaWAN sensor fleet design, custom ESP32-class PCBs, in-house firmware.
            • Hardware review: KiCad schematic audits, USB-C/RP2040 boards, mesh RF networks.

        - title: Embedded Systems Engineer
          company: H2 Fuel-Cell VTOL Drone Startup (Confidential)
          location: Île-de-France, France
          date_start: '2024-06-01'
          date_end: '2025-01-31'
          description: |2-
            • Designed custom PCBs for a hydrogen-airship aerial inspection platform.
            • Wrote embedded C/C++ and Python for test-bench systems.
            • Developed PX4 drivers to integrate sensors with Pixhawk flight controllers.

        - title: Computer Vision & ML Engineer
          company: Freelance
          location: Paris, France (Remote)
          date_start: '2021-07-01'
          date_end: '2024-05-31'
          description: |2-
            • Real-time computer vision applications in C++17 and Python using OpenVINO, TensorRT, and DeepStream SDK.
            • Multi-camera pipelines handling 4+ concurrent streams at 30+ FPS on NVIDIA Jetson and Intel platforms.
            • YOLO-based pipelines for people counting, QR detection, conveyor monitoring; PyTorch → ONNX → TensorRT / OpenVINO IR.
            • Production-grade delivery under NDA for industrial and commercial clients.

        - title: Robotics and Computer Vision Engineer
          company: Prime Smart Systems
          location: Remote
          date_start: '2021-07-01'
          date_end: '2024-09-30'
          description: |2-
            • Computer vision systems using OpenCV and Python for real-world problems across industries.

        - title: Robotics & Control Engineer (Thesis Intern)
          company: ImViA Laboratory
          location: Le Creusot, France
          date_start: '2023-01-01'
          date_end: '2023-06-30'
          description: |2-
            • Robust non-linear control for quadcopters and wheeled robots with computer vision integration for real-time autonomy.
            • Tested on AR Drone 2.0, DJI Tello, and TurtleBot3.

        - title: Robotics & Control Engineer Intern
          company: Z-PARADISE SAS
          location: Staffelfelden, France
          date_start: '2022-06-01'
          date_end: '2022-09-30'
          description: |2-
            • Pool Quality Sensor project: designed PCB and programmed a swimming-pool filtration management system using ESP32, sensors, solar power, and Z-Wave protocol.

        - title: Robotic Software Engineer
          company: Sky High Escape Rooms
          location: Remote
          date_start: '2020-08-01'
          date_end: '2020-10-31'
          description: |2-
            • Node-RED escape-room program for Raspberry Pi with multiple user inputs, camera feeds, HDMI/audio output.

  - block: accomplishments
    content:
      title: 'Certificates'
      subtitle:
      date_format: Jan 2006
      items:
        - certificate_url: https://www.kaggle.com/learn/certification/mutteurrehman/python
          date_end: ''
          date_start: '2023-02-25'
          description: ''
          organization: Kaggle
          organization_url: https://www.kaggle.com
          title: Python
          url: ''
        - certificate_url: https://app.theconstructsim.com/accomplishments/verify/RIA4DE0911ABB7D/
          date_end: ''
          date_start: '2022-12-24'
          description: ''
          organization: The Construct
          organization_url: https://www.theconstructsim.com
          title: Code Foundation for ROS
          url: https://app.theconstructsim.com/learning-paths/code-foundation-for-ros/
        - certificate_url: https://courses.edx.org/certificates/a586a82803f444ffa6fed29dc4239415
          date_end: ''
          date_start: '2021-04-01'
          description: ''
          organization: edx
          organization_url: https://www.edx.org
          title: 'Technology Entrepreneurship: Lab to Market'
          url: ''
        - certificate_url: https://www.linkedin.com/learning/certificates/0909b94f3357aeac061b6703b26de8b308a8007fbbf90ad4bf5439607189508a
          date_end: ''
          date_start: '2022-10-01'
          description: ''
          organization: LinkedIn
          organization_url: https://www.linkedin.com
          title: 'Machine Learning with Python: Foundations'
          url: ''

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
    design:
      columns: '1'
      view: 3
      flip_alt_rows: false

  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: contact
    id: contact
    content:
      title: Contact
      email: muttequreshi@gmail.com
      phone: +33 07 83 85 3998
      appointment_url: 'https://calendly.com/muttequreshi'
      address:
        city: Paris
        postcode: '75019'
        country: France
        country_code: FR
    design:
      columns: '2'
---
