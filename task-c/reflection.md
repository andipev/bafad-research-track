# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**
> Complete **after** finishing Tasks A and B.

---

## Instructions

Write your responses directly in this file (replace the placeholder text).
Aim for **150–200 words total** across both questions.
Be specific — reference your actual experience with the data and code.

---

## Question 1 — Connecting the Work to Research

*After completing Tasks A and B, how does hands-on data exploration relate to the research problem described in **Anomaly Detection in Tactical Sensor Streams** (the document you read before the Canvas quiz)?*

Consider: What patterns did you observe in the SMAP data? How might those patterns complicate or inform the design of an autoencoder-based anomaly detector?

**Your response (75–100 words):**

The SMAP data showed that anomalies were a small part of the dataset, with only 24 out of 500 timesteps labeled as anomalies. Looking at the channel 00 graph and the heatmap also showed that telemetry values can change over time and across different channels. Some anomaly values overlapped with normal values, which could make detection harder. These patterns are important for an autoencoder because it needs to learn what normal sensor behavior looks like. If normal and anomalous patterns are similar, the model may have difficulty separating them.


## Question 2 — Self-Assessment of Readiness

*What specific gaps in your current knowledge — Python skills, statistics concepts, or ML background — do you expect to encounter if you join the research group? What is your plan for addressing them?*

Be honest. There are no wrong answers — this helps us plan the onboarding schedule.

**Your response (75–100 words):**

My biggest gaps are in Python, statistics, and machine learning. I can understand basic Python code, but I still need more practice with pandas, data analysis, and writing code without examples. I also need to get more comfortable with statistics concepts like distributions, standard deviation, and IQR. My ML knowledge is limited, especially when it comes to autoencoders and anomaly detection. I plan to practice Python and pandas regularly, review statistics from STAT 270, and learn the basic concepts behind neural networks and autoencoders before starting research.

*Submission: commit this file to your fork and include it in the GitHub repo URL you submit on Canvas.*
