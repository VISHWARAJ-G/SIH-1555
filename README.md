# Smart India Hackathon Workshop
# Date:
## Register Number:
## Name:
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush


## Idea

Develop a Virtual Herbal Garden that is interactive, educational, and immersive. It should provide a comprehensive platform to explore medicinal plants used in Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy (AYUSH). The goal is to promote awareness and provide credible information on Indian medicinal plants.

---

## Proposed Solution / Architecture Diagram

### Key Modules:

- **3D Plant Models:** Realistic, rotatable plant models using WebGL (Three.js or Blender exports)
- **Informational Database:** Structured details like botanical/common names, habitat, medicinal uses, cultivation, and AYUSH relevance
- **Multimedia Content:** Images, videos, and guided audio narration in English and Indian languages
- **Smart Search & Filter:** By region, AYUSH system, ailment, or plant part
- **Guided Virtual Tours:** Themes like "Herbs for Immunity" or "Digestive Wellness"
- **User Features:** Login/Registration, bookmarking, note-taking, sharing
- **Gamification (Optional):** Quizzes, badges, and engagement rewards

### System Architecture Diagram:

![image](https://github.com/user-attachments/assets/c84ffaf2-e242-4290-94ea-80a57aa9a744)

---

## Use Cases

### User:
![image](https://github.com/user-attachments/assets/75c7f66f-cf42-4b44-8282-3f0e38fb3eaa)
### Admin:
![image](https://github.com/user-attachments/assets/96a51814-aa9b-4bc9-9564-9ce9afc15e27)

## Technology Stack

### Frontend:
- **Framework:** React or Next.js (for Server-Side Rendering)
- **3D Rendering:** Three.js + GLTF model support
- **Styling:** TailwindCSS
- **Routing:** React Router

### Backend:
- **API:** Node.js with Express
- **Database:** MongoDB (NoSQL)
- **Authentication:** Firebase Auth or JWT

### Storage & Hosting:
- **Media Storage:** Firebase Storage or AWS S3
- **Hosting:** GitHub Pages / Vercel (frontend), Render or AWS EC2 (backend)

### Optional AI/ML Enhancements:
- Natural language question answering (using OpenAI Embeddings)
- Personalized herbal recommendations

---

## Dependencies

- **Three.js** – for 3D model rendering
- **Blender** – for creating/exporting GLTF plant models
- **MongoDB** – to store plant metadata
- **Firebase / AWS S3** – for storing and serving images, videos, and audio
- **Firebase Auth / JWT** – for user authentication
- **TailwindCSS** – for responsive and clean UI
- **OpenAI API** (optional) – for intelligent search and Q&A
