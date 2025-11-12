# 🌟 Ngoc Tho Vien Website Technical Plan Summary

**Goal:** To clearly outline the required Core Features, Database (GIS Requirements), and Sitemap Essentials for the development team.

## 1. Core Features

The project focuses on integrating digital content, e-commerce, and advanced AI/GIS technology.

### A. AI and Digital Knowledge Features

* **Pottery Recognition Tool (CV - Scan):** Allows users to upload or take photos of pottery products. The Computer Vision (CV) system analyzes the image and returns detailed information on the pottery Type/Name, Origin (craft village), Glaze/Material characteristics, and Reference Value[cite: 108, 109, 110].
* **Symbol Decoder:** Analyzes patterns, glaze colors, shapes, and cultural philosophies of the ceramics, integrating AI for image recognition to look up the origin and symbolic meaning of the motifs[cite: 32, 86].
* **24/7 AI Chatbot (Digital Knowledge Assistant):** Supports Q&A, lookups, and automated narration about the history, techniques, symbols, and tourism aspects of Vietnamese pottery[cite: 87].

### B. Digital Map and Information Features

* **"Vietnamese Pottery Journey" Map (GIS):** Displays the precise locations (Geographic Information System) of craft villages nationwide (e.g., Bat Trang, Phu Lang, Bien Hoa) as an interactive map[cite: 94, 95, 96].
* **Multimedia Library:** Compiles 360-degree images, videos of the pottery-making process, and in-depth articles on preserving traditional pottery values[cite: 111, 112].

### C. E-commerce & Community Features

* **E-commerce Marketplace:** Allows producers/artisans to list and sell pottery products online, categorized by craft village and material. Supports secure payment and shipping[cite: 98, 99, 100, 101].
* **Pottery Forum:** An online space for interaction, learning, organizing workshops, and virtual exhibitions among artisans, students, and enthusiasts[cite: 86].

## 2. Database Requirements (GIS System Focus)

The Database must handle both traditional and complex geographical data to support core features.

* **Data Types Required:**
    * **Geographic Data (GIS):** Precise locations (Coordinates) of craft villages, tourist spots, and production addresses for display on the GIS Map[cite: 53].
    * **Digital Knowledge Data:** Historical information, techniques, symbols, cultural philosophies, and training data for the AI/CV models.
    * **E-commerce/Product Data:** Detailed product information, categorization, pricing, inventory, orders, payment, and shipping details.
    * **User/Community Data:** Account information, forum posts, comments, and preference data (for AI suggestions).
    * **Multimedia Data:** Storage metadata and paths for images, 360-degree videos, and 3D models.
* **Recommended Technology:** **PostgreSQL with PostGIS Extension** (Recommended for handling geographical and spatial data).

## 3. Sitemap Essentials (Required Pages)

Based on the platform structure and features, the website requires the following pages:

| Page Name (English/Vietnamese) | Page Type | Primary Function |
| :--- | :--- | :--- |
| **Home Page** (Trang Chủ) | Static | Entry point, general introduction, prominent CTAs. |
| **Heritage Pottery** (Gốm Di sản) | Content/Library | Introduction to history, pottery lines, digital library, and 3D models[cite: 86]. |
| **Symbol Decoder** (Giải Mã Biểu Tượng) | AI Interaction | Tool for image upload (CV Scan) and looking up the meaning/origin of motifs[cite: 86, 107]. |
| **Pottery Journey** (Hành trình Gốm Việt) | Map (GIS) | Interactive map displaying craft villages and visitor addresses[cite: 87, 94]. |
| **Artisans & Techniques** (Nghệ nhân & Kỹ thuật) | List/Detail | Artisan profiles, simulation of production processes, and sharing of craft secrets[cite: 86]. |
| **Pottery Forum** (Diễn đàn Gốm) | Community | Space for discussion, exchange, and hosting virtual workshops/exhibitions[cite: 86]. |
| **Marketplace** (Sàn Thương mại) | E-commerce | Product listings, detailed product pages, categorized by village/material[cite: 98, 99, 100]. |
| **Cart & Checkout** (Giỏ hàng & Thanh toán) | E-commerce | Purchasing, payment, and shipping process[cite: 101]. |
| **Contact/About Us** (Liên Hệ/Về Chúng Tôi) | Static | Contact information, vision, and mission of Ngoc Tho Vien. |

---

**Next Step:** The requirements are clear. Would you like me to help **draft a specific role assignment matrix** for the team members (e.g., assigning AI, GIS, and E-commerce tasks to specific developers)?
