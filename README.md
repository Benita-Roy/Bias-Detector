# Bias-Detector
Goal: To develop a chrome extension that will highlight words that suggest gender or racial bias in news or articles to users.

Flow: User opens a webpage -> Clicks on the Chrome extension -> Extension scans the text -> Sends the text to the backend -> NLP logic detects biased words from a known list -> Extension highlights those words and gives alternatives

Project Progress
Day 1: Setting up the folders and files necessary
  Chrome extension(Frontend)
      manifest.json (to define the extension to chrome)
      content.js (to read the page content)
      popup.js (UI shown when user clicks the extension)
  NLP(Backend)
      bias_detector.py
  Data
      bias_detector.json
