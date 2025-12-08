# Yashwant Gandham

Boulder, CO • gyashwant2002@gmail.com • +1 303-414-8260 • LinkedIn • Github  

---

## Education

**Master of Science in Data Science**  
University of Colorado Boulder — Boulder, CO  
Aug 2024 – Present  

**Bachelor of Technology in Electrical Engineering**  
Jawaharlal Nehru Technological University — Hyderabad, India  
Mar 2019 – Jun 2023  

---

## Experience

**AI Engineer Intern** — NovaChat AI — Boulder, CO  
Aug 2025 – Present  
- Built full-stack lead generation platform with React (Vite) frontend on Vercel, FastAPI middleware on Railway, and Supabase PostgreSQL for lead tracking and analytics.  
- Implemented intelligent rate limiting and message optimization strategy achieving 18% response rate and 0% ban rate across 800+ outreach messages, validated through A/B testing and marketing team feedback.  

**Machine Learning Systems Researcher** — Boulder AI & Infra Lab — Boulder, CO  
Sept 2025 – Present  
- Profiled 3.3B parameter Pi0 VLA model using Perfetto, identified vision encoder bottleneck (sequential processing of cameras) (50ms per camera); designing parallelization strategy to optimize multi-camera inference pipeline toward 73ms latency target.  

**Research Assistant (AI & Robotics)** — HIRO Lab — Boulder, CO  
Oct 2024 – Aug 2025  
- Built computer vision pipeline processing Tobii Pro eye-tracking data using SAM, DINO, and CLIP for attention-based object segmentation, generating multiple visualization outputs from pupil density heatmaps.  
- Implemented reinforcement learning agents (DQN, PPO, A2C) for robotic block assembly in OpenAI Gym environments, achieving >85% task success validated across 500+ episodes.  

---

## Projects

**ML Observability & Drift Monitoring Platform (Python | FastAPI | Docker | PostgresSQL | GCP | SQLAlchemy)**  
2025  
- Designed and implemented an ML observability platform ingesting 100+ predictions/day across multiple binary classifiers, logging predictions, ground-truth labels, and 15+ input features into PostgreSQL; deployed containerized FastAPI on GCP Compute Engine with Docker/systemd achieving <100ms latency for prediction and ingestion.  
- Built monitoring dashboards surfacing signal drift, calibration curves, accuracy, precision, recall, F1-score, and latency percentiles, aggregating 7+ key metrics per model per day into optimized summary tables.  

**DocChat: Semantic Search for Document Archives (Python | FastAPI | Pinecone | GCP | Langraph | VertexAI)**  
2025  
- Deployed a full-stack semantic search system with a React frontend and FastAPI backend on GCP Compute Engine, serving 10+ test users with 99% uptime, configured using systemd services, VPC firewall rules, and Cloud Storage support for 500+ PDF uploads.  
- Designed a cost-efficient RAG pipeline using Gemini embeddings and a Pinecone vector store indexing 10K+ document chunks, reducing LLM context usage by 40% through retrieval-based prompts and improving document search time by 3× for users.  

**Vision-Based Robotic Grasping System (Python | FastAPI | PYBullet | PostgresSQL | Pinecone)**  
2025  
- Trained a lightweight CNN to predict 3D grasp positions from RGB images, using simulated scenes in PyBullet with a Franka Panda arm; achieved a mean error of 1.00 cm and a success rate of 100% below a 5 cm threshold.  
- Built a full simulation-to-inference pipeline with randomized label generation and visual evaluation, enabling autonomous grasping.  

---

## Technologies

- **Cloud & Infrastructure:** GCP (Compute Engine, Cloud Storage), Docker, Railway, Vercel, Linux administration  
- **Backend & APIs:** FastAPI, Python, Supabase, PostgreSQL  
- **Programming & ML:** Python (NumPy, Pandas, PyTorch, scikit-learn), SQL, R, Git, Conda  
- **ML Infrastructure:** Model deployment, Performance profiling (Perfetto), Vector databases (Pinecone), RAG pipelines, LangGraph  
- **Computer Vision:** OpenCV, SAM, DINO, CLIP, PyBullet  
