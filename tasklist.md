# 🚀 AI Circular Fashion Hackathon Roadmap (July 15 – July 30)

> **Goal:** Build a polished, AI-first circular fashion platform that showcases sustainability, personalization, and real-world impact.

---

# 📅 July 15 — Planning & Project Setup

## 👥 Together

* [ ] Finalize the product vision, target users, and one-line elevator pitch.
* [ ] Complete the Product Requirements Document with all MVP features.
* [ ] Draw the complete user journey from signup to AI recommendations.
* [ ] Create low-fidelity wireframes for every major application screen.
* [ ] Finalize frontend, backend, database, AI, and deployment tech stack.
* [ ] Create GitHub repository issues for every feature and milestone.
* [ ] Setup GitHub Project board with feature-based task assignments.
* [ ] Define Git branching strategy and pull request workflow.

### 👩 Tamanna

* [ ] Design complete PostgreSQL/Supabase database schema with relationships.
* [ ] Plan backend folder structure and API architecture.
* [ ] Initialize backend project with required dependencies and configuration.
* [ ] Configure Docker environment for consistent local development.
* [ ] Connect backend to development database successfully.
* [ ] Setup environment variables and API key management.

### 👩 Sthiti

* [ ] Initialize frontend project with chosen React framework.
* [ ] Install Tailwind CSS and required UI component libraries.
* [ ] Configure frontend routing and project folder structure.
* [ ] Create reusable navigation bar and application layout.
* [ ] Configure application theme, typography, and color palette.
* [ ] Build landing page skeleton with placeholder sections.

---

# 📅 July 16 — Authentication

## 👩 Tamanna

* [ ] Design user schema supporting authentication and profile information.
* [ ] Implement secure signup API with password hashing.
* [ ] Implement login API returning JWT authentication token.
* [ ] Build authentication middleware for protected backend routes.
* [ ] Test authentication APIs using Postman thoroughly.

## 👩 Sthiti

* [ ] Build responsive signup page with complete validation.
* [ ] Build login page connected to backend APIs.
* [ ] Design basic user profile page layout.
* [ ] Store authentication token securely after successful login.
* [ ] Handle login errors and invalid credentials gracefully.

---

# 📅 July 17 — Wardrobe Foundation

## 👩 Tamanna

* [ ] Create wardrobe database schema with clothing metadata fields.
* [ ] Implement wardrobe image upload backend endpoint.
* [ ] Integrate cloud storage for uploaded clothing images.
* [ ] Store uploaded image URLs and metadata correctly.
* [ ] Test upload endpoint with multiple clothing images.

## 👩 Sthiti

* [ ] Build wardrobe upload interface with drag-and-drop support.
* [ ] Display uploaded clothing items in responsive card layout.
* [ ] Implement clothing edit functionality for wardrobe items.
* [ ] Add delete option with confirmation dialog.
* [ ] Connect wardrobe UI with backend upload endpoint.

---

# 📅 July 18 — AI Wardrobe

## 👩 Tamanna

* [ ] Finalize clothing metadata schema used across recommendation engine.
* [ ] Create backend endpoint for AI clothing analysis requests.
* [ ] Store AI-generated clothing metadata inside database automatically.
* [ ] Validate AI responses before saving wardrobe information.
* [ ] Connect upload flow with backend AI analysis pipeline.

## 👩 Sthiti

* [ ] Integrate Gemini Vision API for clothing image analysis.
* [ ] Write prompt generating structured clothing metadata JSON.
* [ ] Parse AI response safely into frontend application.
* [ ] Display AI-generated clothing tags below every wardrobe item.
* [ ] Improve wardrobe cards with category, style, and occasion badges.

---

# 📅 July 19 — Marketplace

## 👩 Tamanna

* [ ] Design marketplace schema supporting buy, rent, and swap listings.
* [ ] Build listing creation backend API with validation.
* [ ] Implement listing update and deletion endpoints.
* [ ] Add ownership verification before editing any listing.
* [ ] Store listing availability and rental status correctly.

## 👩 Sthiti

* [ ] Build marketplace homepage displaying available clothing listings.
* [ ] Design create-listing form with image upload support.
* [ ] Implement listing detail page with complete clothing information.
* [ ] Build filters for category, occasion, and clothing type.
* [ ] Research AI-assisted pricing prompt for used clothing.

---

# 📅 July 20 — AI Listing Generator

## 👩 Tamanna

* [ ] Create backend endpoint generating AI listing suggestions.
* [ ] Connect uploaded images with AI listing generation pipeline.
* [ ] Store AI-generated descriptions before user approval.
* [ ] Implement backend validation for generated listing content.
* [ ] Test listing generation using diverse clothing examples.

## 👩 Sthiti

* [ ] Design effective prompt for clothing title generation.
* [ ] Generate AI descriptions, categories, and suggested clothing tags.
* [ ] Generate estimated resale price using prompt engineering.
* [ ] Build review page allowing users to edit AI suggestions.
* [ ] Publish edited listing directly into marketplace.

---

# 📅 July 21 — Style Learning

## 👩 Tamanna

* [ ] Create SwipeHistory table storing user preference interactions.
* [ ] Implement backend APIs recording swipe actions.
* [ ] Store embeddings representing user style preferences.
* [ ] Build similarity scoring logic for recommendations.
* [ ] Test preference updates using sample swipe data.

## 👩 Sthiti

* [ ] Build Tinder-style swipe interface with smooth animations.
* [ ] Add like, dislike, and undo interactions.
* [ ] Design style categories used throughout recommendation engine.
* [ ] Connect swipe interface with backend preference APIs.
* [ ] Display progress while AI learns user preferences.

---

# 📅 July 22 — Semantic Search

## 👩 Tamanna

* [ ] Generate embeddings for wardrobe and marketplace clothing items.
* [ ] Setup vector database for semantic similarity search.
* [ ] Build backend retrieval pipeline returning relevant clothing.
* [ ] Optimize search results using similarity thresholds.
* [ ] Test search quality using multiple natural language queries.

## 👩 Sthiti

* [ ] Design semantic search page with conversational interface.
* [ ] Write prompts converting user requests into search intent.
* [ ] Display AI explanation describing recommended clothing choices.
* [ ] Connect frontend search with semantic backend APIs.
* [ ] Handle loading and empty-state user experiences.

---

# 📅 July 23 — Outfit Generator

## 👩 Tamanna

* [ ] Retrieve relevant wardrobe and marketplace clothing candidates.
* [ ] Rank clothing items based on relevance and availability.
* [ ] Build outfit generation backend endpoint.
* [ ] Test outfit generation using multiple occasions.
* [ ] Optimize response speed for smoother user experience.

## 👩 Sthiti

* [ ] Write stylist prompt generating complete outfit recommendations.
* [ ] Generate reasoning explaining every outfit suggestion.
* [ ] Explain sustainability benefit of selected outfit choices.
* [ ] Design visually attractive outfit recommendation page.
* [ ] Allow users to regenerate alternative outfit suggestions.

---

# 📅 July 24 — Sustainability Engine

## 👩 Tamanna

* [ ] Build decision engine prioritizing reuse before new purchases.
* [ ] Calculate estimated environmental impact for recommendations.
* [ ] Estimate approximate water savings using published clothing metrics.
* [ ] Estimate approximate carbon savings for reused garments.
* [ ] Return sustainability metrics alongside recommendation results.

## 👩 Sthiti

* [ ] Research reliable lifecycle data for clothing environmental impact.
* [ ] Write AI explanations for sustainable recommendation decisions.
* [ ] Design attractive sustainability impact cards.
* [ ] Display money, carbon, water, and garment savings clearly.
* [ ] Improve dashboard storytelling using simple environmental comparisons.

---

# 📅 July 25 — Dashboard

## 👩 Tamanna

* [ ] Build dashboard APIs returning wardrobe and marketplace statistics.
* [ ] Generate recommendation history for logged-in users.
* [ ] Calculate user sustainability metrics dynamically.
* [ ] Return dashboard analytics efficiently.
* [ ] Test dashboard endpoints with realistic sample data.

## 👩 Sthiti

* [ ] Design personal dashboard with clean information hierarchy.
* [ ] Build reusable statistic cards for environmental impact.
* [ ] Add timeline showing recent wardrobe activities.
* [ ] Create weekly wardrobe insight cards using AI.
* [ ] Polish dashboard layout for desktop and mobile devices.

---

# 📅 July 26 — AI Fashion Assistant

## 👩 Tamanna

* [ ] Build conversational backend integrating wardrobe and marketplace retrieval.
* [ ] Add memory for ongoing user conversations.
* [ ] Retrieve wardrobe before marketplace recommendations.
* [ ] Connect assistant with recommendation engine.
* [ ] Test complete conversational recommendation flow.

## 👩 Sthiti

* [ ] Design conversational prompt acting as AI fashion stylist.
* [ ] Build modern chat interface with streaming responses.
* [ ] Display reasoning behind every recommendation clearly.
* [ ] Highlight sustainable alternatives before suggesting new purchases.
* [ ] Test assistant using interview, farewell, and wedding scenarios.

---

# 📅 July 27 — Polish

## 👩 Tamanna

* [ ] Fix backend bugs discovered during integration testing.
* [ ] Improve API performance and response consistency.
* [ ] Optimize database queries reducing unnecessary latency.
* [ ] Prepare backend deployment configuration.
* [ ] Review API documentation completeness.

## 👩 Sthiti

* [ ] Improve animations across all major application screens.
* [ ] Make application fully responsive on smaller devices.
* [ ] Improve accessibility and keyboard navigation.
* [ ] Add consistent loading, empty, and error states.
* [ ] Polish typography, spacing, and overall UI consistency.

## 👥 Together

* [ ] Test every AI prompt and improve response quality.
* [ ] Perform complete end-to-end application walkthrough.

---

# 📅 July 28 — Integration

## 👥 Together

* [ ] Merge all feature branches into main safely.
* [ ] Resolve merge conflicts carefully before deployment.
* [ ] Perform complete end-to-end feature testing.
* [ ] Fix critical bugs affecting user experience.
* [ ] Improve mobile responsiveness across every screen.
* [ ] Verify AI workflows using multiple realistic scenarios.

---

# 📅 July 29 — Deployment & Presentation

## 👩 Tamanna

* [ ] Deploy backend services and verify production APIs.
* [ ] Deploy production database and configure secrets securely.
* [ ] Verify AI integrations using production environment.
* [ ] Monitor backend logs for unexpected runtime issues.

## 👩 Sthiti

* [ ] Deploy frontend application to production hosting.
* [ ] Polish landing page and application branding.
* [ ] Create demo flow showcasing strongest AI features.
* [ ] Prepare presentation screenshots and promotional visuals.

## 👥 Together

* [ ] Record polished demo video under submission time limit.
* [ ] Write comprehensive README with architecture explanation.
* [ ] Create clean system architecture diagram.
* [ ] Complete Devpost submission carefully with all required details.
* [ ] Practice live demo until presentation feels completely natural.

---

# 📅 July 30 — Submission Day

## 👥 Together

* [ ] Perform final end-to-end testing before submission deadline.
* [ ] Fix only critical issues discovered during testing.
* [ ] Capture final screenshots for documentation.
* [ ] Verify all deployment links work correctly.
* [ ] Submit project before deadline with sufficient buffer time.
* [ ] Celebrate completing the hackathon together 🎉
