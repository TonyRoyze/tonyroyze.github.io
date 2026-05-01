---
title: Bachelor of Science (Hons.) in Data Science
location: University of Colombo
institute: University of Colombo
date: Since 2023
tags:
  [
    "Statistics",
    "Pure Mathematics",
    "Applied Mathematics",
    "Computer Science",
    "Statistical Modelling",
    "Machine Learning",
    "Analytics"
  ]
---

### Projects


**Flight Analytics Dashboard**

A comprehensive flight data analytics dashboard built with Next.js, featuring three distinct user modes tailored for different travel needs — **Local Traveller**, **Business Traveller**, and **Tourist Traveller**. Each mode offers relevant cards and charts, including price breakdowns by airline, departure time, stops, and duration, as well as an interactive map of Indian airports with tourist attractions for the tourist mode. Business and tourist modes also include real-time currency conversion to **USD, EUR, GBP, and INR**. The dashboard handles **300,000+ flight records** with indexed data processing for ultra-fast filtering, and is built with **Recharts** for interactive visualizations and **Leaflet** for maps. [GitHub](https://github.com/TonyRoyze/flight-dash.git)



**EduCost — Education Cost Predictor**

EduCost is a high-performance web application designed for education consultants and prospective international students. It uses **CatBoost** and **Multivariate Regression** models to predict the total cost of education — including tuition, living expenses, rent, and visa fees — across different countries and programs. The platform features a **Live Card Builder** that lets consultants generate, customize, and export premium education cost cards for marketing use, with support for bulk CSV uploads. Built with a **Next.js** and **TypeScript** frontend using **Tailwind CSS** and **Shadcn/UI**, it integrates a **Python-based ML inference backend** deployed on Vercel Serverless. [GitHub](https://github.com/TonyRoyze/education-cost-prediction.git)



**Surge Pricing & Profit Dashboard**

A machine learning-powered web application designed to optimize ride-sharing fares and track profitability in real time. It addresses  the inefficiencies of fixed duration-based pricing by introducing dynamic fare predictions that account for demand surges, driver availability, and weather conditions. The app features live fare prediction with instant AI-driven estimates, a profit tracking dashboard with historical and simulated ride data, and a multi-model ML backend using **scikit-learn** with **SHAP-based feature selection** for model interpretability. The frontend is built with **React 19**, **TypeScript**, **Vite**, **Tailwind CSS**, and **Framer Motion** for smooth price transition animations, while the backend runs on **FastAPI** with **Uvicorn**.[GitHub](https://github.com/TonyRoyze/surge-pricing-dashboard.git)


**Anomalize — Weather Anomaly Detection**

Anomalize is a weather analytics desktop application designed to identify anomalies from historical and live weather data, featuring a native **Rust-based inference engine** powered by **ONNX Runtime**. Users can explore weather datasets for specific cities and date ranges, predict **5-day anomaly risks** using machine learning models, and visualize forecast timelines with interactive charts and confidence bands. The app offers two scoring modes — **Conservative (XGBoost)** and **Sensitive (Random Forest)** — giving users flexibility in how anomalies are detected, with automatic fallback between historical archive and live forecast APIs via **Open-Meteo** for continuous data availability. Built as a **Tauri v2** desktop shell (with a macOS DMG available), the frontend is powered by **SvelteKit 5**, **TypeScript**, and **Tailwind CSS**, with visualizations rendered using **LayerChart** and **D3.js**. The backend runs on **Rust** with **Axum** and **Tokio**, performing in-process model scoring via the `ort` crate and `ndarray`, while models were trained in **Python** using **scikit-learn** and **XGBoost** before being exported to ONNX. [GitHub](https://github.com/TonyRoyze/weather-anomaly-detection.git)