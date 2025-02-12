# Learning Path Recommendation System for CodePTIT

## Project Overview
An intelligent recommendation system that leverages state-of-the-art AI/ML models to provide personalized learning paths for students based on their historical performance data from online judge systems (similar to LeetCode, HackerRank). The system analyzes student performance patterns, exercise difficulty, and learning progress to generate optimized study plans and targeted recommendations.

## Purpose

##### Goals:

1. Generate optimal, individualized learning paths for each student.
2. Reduce student struggles and dropout rates.

##### Approach:

1. Component grades consist of: attendance (10%), practical exercises (20%)
2. The final exam (70%) has 5 questions (corresponding to the number of correct questions, the scores will be as follows: 1 question 4 points, 2 questions 6 points, 3 questions 7.5 points, 4 questions 9 points, 5 questions 10 points).
3. The questions will have different types of exercises, of course, there are easy and difficult ones. What I want is for you to build a recommendation system based on student data. Let students know what type of exercise they should review to achieve what score? (A+, A, B+, B, ......)

## Grading Components
- Attendance: 10%
- Practical Exercises: 20%
- Final Exam (70%):
  - 1 question: 4 points
  - 2 questions: 6 points
  - 3 questions: 7.5 points
  - 4 questions: 9 points
  - 5 questions: 10 points

## Key Features

### 1. Intelligent Knowledge Tracing
- Hybrid architecture combining Deepseek-v3 with specialized CodeBERT
- Graph Neural Networks for concept relationship modeling
- Multi-modal knowledge state tracking
- Real-time learning progress analysis

### 2. Advanced Exercise Analysis
- StarCoder/CodeGen for deep code understanding
- Difficulty assessment using neural networks
- Prerequisites and concept mapping
- Solution pattern recognition
- Complexity scoring

### 3. Smart Path Optimization
- Hybrid reranking system (BM25 + MonoT5/ColBERT)
- RAG-enhanced personalized recommendations
- Dynamic difficulty adjustment
- Multi-objective path optimization
- Adaptive learning sequences

### 4. Performance Prediction
- E5-large-v2 embeddings for semantic understanding
- Vector similarity search with Milvus/Qdrant
- Grade forecasting and weak area identification
- Early intervention triggers
- Progress tracking


## Technical Innovation

### Advanced AI Stack
- Base LLM: [Deepseek-v3](https://huggingface.co/deepseek-ai/DeepSeek-V3) (GGUF quantized)
- Code Understanding: CodeBERT/StarCoder
- Reranking: BM25 + [ViRanker](https://huggingface.co/namdp-ptit/ViRanker)
- Embeddings: [VoVanPhuc/sup-SimCSE-VietNamese-phobert-base](https://huggingface.co/VoVanPhuc/sup-SimCSE-VietNamese-phobert-base)
- Vector Search: Milvus/Qdrant

### Hybrid Architecture Benefits
- Combines multiple SOTA models
- Local deployment optimized
- Resource-efficient processing
- Real-time adaptation
- Scalable design

## Key Use Cases

1. Student Onboarding
- Initial knowledge assessment
- Baseline establishment
- Starting path generation

2. Weekly Study Planning
- Performance-based exercise sequencing
- Dynamic difficulty adjustment
- Time management optimization

3. Performance Tracking
- Real-time progress monitoring
- Weak area identification
- Intervention recommendations

4. Topic Mastery
- Concept relationship mapping
- Knowledge state tracking
- Prerequisite validation

5. Adaptive Learning
- Dynamic exercise selection
- Difficulty optimization
- Personalized pacing

6. Progress Analytics
- Detailed performance metrics
- Learning pattern analysis
- Achievement tracking

## System Requirements
- CPU: Modern multi-core processor
- RAM: 16GB+ recommended
- Storage: 10GB+ free space
- GPU: Optional but recommended
- OS: Windows/Mac/Linux

## Key Advantages

1. State-of-the-art Performance
- Advanced AI/ML models
- Hybrid architecture
- Efficient processing
- Accurate recommendations

2. Practical Implementation
- Local deployment
- Resource optimization
- Easy maintenance
- Scalable design

3. Comprehensive Analysis
- Multi-modal assessment
- Deep code understanding
- Pattern recognition
- Predictive analytics

4. User-Focused Design
- Personalized recommendations
- Adaptive learning paths
- Clear progress tracking
- Actionable insights
