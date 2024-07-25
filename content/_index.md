---
title: 'Home'
date: 2024-06-25
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Numbers tell the truth
      text: You have to know how to read them though 🧐
      primary_action:
        text: Read the docs
        url: /docs/
      # secondary_action:
      #   text: Read the docs
      #   url: /docs/
      # announcement:
      #   text: "Last articles"
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "Data"
          description: |
            Uncover insights hidden in the numbers
        - statistic: "AI"
          description: |
            Exploring the frontiers of machine learning and cognition
        - statistic: "Stats"
          description: |
            Extracting meaningful patterns from complex dataset
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Economics
      text: Deciphering the forces that shape our financial world.Unveiling the intricate dance of supply, demand, and human behavior.
      items:
        - name: Data-driven decision making
          icon: star
          description: AI and statistics rely on vast amounts of data to inform economic policies and predictions.
        - name: Predictive modeling
          icon: rectangle-group
          description: AI and statistical techniques are crucial for forecasting economic trends and market behaviors.
        - name: Resource optimization
          icon: sparkles
          description: Economic principles guide how we allocate resources in data management and AI development.
        - name: Technological disruption
          icon: code-bracket
          description: AI and data analytics are reshaping economic landscapes, creating new markets and transforming existing ones.
          - name: Knowledge extraction
          icon: code-bracket
          description: AI and statistical methods enable the transformation of raw data into actionable economic insights and knowledge.
          - name: Risk assessment
          icon: exclamation
          description:  Data analytics and AI-powered models enhance economic risk evaluation and management across various sectors and markets.

  - block: cta-card
    content:
      title: "Modern economics is deeply intertwined with data, AI, and statistics, forming the backbone of evidence-based policy and decision-making."
      text: This blog explores the fascinating intersection of these fields, uncovering how they collectively shape our understanding of markets, technology, and society.
      button:
        text: Get Started
        url: /docs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
