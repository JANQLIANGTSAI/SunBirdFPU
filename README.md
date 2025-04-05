# SunBirdFPU

Author: Max Tsai (mt8168@gmail.com)
Reference: [GitHub Repository](https://github.com/janq-liang.tsai/Gemini_API_Chatbot_using_streamlit)

# Business Statement
"The Sunny Sunbird AI assistant will serve as a holistic digital companion for Fresno Pacific University (FPU). Its purpose is to enhance the educational experience for students, their families, and the surrounding community. By offering instant access to information about FPU, guiding users through the admissions process, academic programs, campus life, and post-graduation support, The Sunny Sunbird aims to foster engagement, streamline communication, and establish FPU as a pioneer in AI-driven solutions for academic success."

# Functional Product Design (Features)

## Pre-Academic Journey
- **Admissions Guidance**: Interactive step-by-step support for prospective students, from inquiry to enrollment. Personalized recommendations based on interests and academic goals.
- **Program Exploration**: Detailed descriptions of degree programs, certificates, and extracurricular activities.
- **Financial Assistance Information**: Comprehensive support with scholarships, tuition plans, and financial aid applications.
- **Virtual Campus Tour**: A generative AI-powered virtual experience showcasing the campus and facilities.

## During the Academic Journey
- **Student Support Services**: Information and troubleshooting for registration, advising, library services, and student life.
- **Smart Scheduling Assistance**: Course selection and timetable management based on students’ academic goals.
- **Knowledge Hub**: Access to FAQs, academic policies, events, and announcements.
- **AI Tutoring and Study Recommendations**: On-demand assistance and suggestions tailored to coursework and learning styles.

## Post-Academic Journey
- **Career Counseling**: Tools for resume building, interview preparation, and job search based on industry preferences.
- **Alumni Network Integration**: Connecting graduates with alumni events and networking opportunities.
- **Lifelong Learning Opportunities**: Support for continuing education, workshops, and certificates.

## Community Engagement
- **Community Resource Hub**: Information on public events, workshops, and university outreach programs.
- **Feedback and Suggestions**: Open channels for user feedback to continuously improve The Sunny Sunbird’s capabilities.

# Technical Focus (Aligned with Repository)
- Backend API Integration: Utilize Gemini API for chatbot functionality.
- Frontend Interface: Develop using Streamlit for an intuitive and interactive user experience.
- Data Management: Ensure seamless integration with predefined intents and entities, leveraging the structure from the provided repository.

---

# Scope Statement for 6-Week Proof of Concept (PoC)

# Scope Statement for 6-Week Proof of Concept (PoC)

## Project Objective
The objective of the 6-week Proof of Concept (PoC) is to develop a functional prototype of The Sunny Sunbird AI assistant for Fresno Pacific University (FPU). This PoC will focus on delivering core features that showcase the assistant's ability to provide dynamic answers through AI capabilities, retrieve relevant data from web and document repositories, and guide prospective students effectively. It will also implement Retrieval-Augmented Generation (RAG) to improve the contextual accuracy of responses.

## Deliverables
1. **Admissions FAQ Module:**
   - A chatbot feature capable of answering predefined FAQs about admissions, financial aid, and application processes via content from FPU websites (scraped) and PDF documents.
   - Integration with Gemini API to handle natural language queries dynamically.

2. **Program Exploration Feature:**
   - A feature that provides detailed information about 1–3 academic programs using a conversational approach.
   - Dynamic responses powered by the Gemini API.

3. **Interactive Chatbot Interface:**
   - A web-based interface built with Streamlit for easy interaction.
   - Simple input and output features for seamless user experience.

4. **RAG (Retrieval-Augmented Generation):**
   - Implement RAG to enhance the chatbot's contextual knowledge by retrieving data from predefined sources.
   - Incorporate information from both structured FAQs and external document repositories.

5. **Website Scraping:**
   - Include the ability to scrape relevant data from FPU's public website for real-time updates.
   - Focus on extracting admissions deadlines, program details, and contact information.

6. **PDF Document Repository Integration:**
   - Add functionality to process and retrieve information from a repository of PDF documents (e.g., FPU brochures, financial aid documents).
   - Integrate PDF parsing tools (such as PyPDF2 or PDFplumber) to enhance the chatbot's knowledge base.

7. **Feedback Mechanism:**
   - Allow users to rate responses or submit comments for iterative improvements.

8. **Documentation and Deployment:**
   - Create technical documentation detailing the system design, features, and integration approach.
   - Deploy the PoC on a local server or cloud platform for demonstration purposes.

## Out of Scope
- Full implementation of RAG across all university data systems (focus is limited to FAQs, web scraping, and PDFs).
- Advanced chatbot capabilities such as scheduling integration or virtual campus tours.

## Success Criteria
- The chatbot successfully retrieves and generates accurate responses for at least 80% of test cases.
- Website scraping and PDF repository integration provide reliable and relevant data for user queries.
- Stakeholders recognize the PoC's potential for scalability and real-world application.

## Assumptions
- Access to Gemini API, PDF documents, and public FPU website data will be provided throughout the project.
- Development tools for RAG, web scraping, and PDF parsing will be compatible with the project setup.

## Constraints
- The project duration is limited to 6 weeks.
- Development team resources are restricted and must balance other commitments.
