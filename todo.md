# CV Shortlister - Project TODO

## Phase 1: Foundation
- [x] Database schema: job_descriptions, screening_sessions, candidates, cv_files tables
- [x] Gemini API key secret configuration
- [x] Google Drive OAuth credentials setup

## Phase 2: Backend
- [x] Google Drive integration: OAuth flow, folder browsing, file listing
- [x] CV file fetching from Google Drive (PDF/DOCX support)
- [x] CV parsing engine using Gemini API (extract name, contact, skills, experience, education, work history)
- [x] Intelligent matching algorithm scoring CVs 0-100% against job description
- [x] Job description CRUD API (create, read, update, delete)
- [x] Screening session management API
- [x] Candidate results storage and retrieval API
- [x] Batch processing endpoint with progress tracking (200+ CVs)

## Phase 3: Frontend Core
- [x] Elegant landing/home page with premium design
- [x] Dashboard layout with sidebar navigation
- [x] User authentication (login/logout via Manus OAuth)
- [x] Job description form (title, skills, experience level, qualifications)
- [x] Google Drive connector UI (OAuth connect, folder browser)
- [x] Batch processing UI with progress bar and status tracking
- [x] Ranked candidate list dashboard (sorted by match score, key highlights)
- [x] Detailed candidate comparison report (matched vs missing criteria)

## Phase 4: Advanced Features
- [x] Job description history page (save and reuse previous job profiles)
- [x] Export shortlisted results as CSV
- [x] Export shortlisted results as PDF report
- [x] Gemini API key configuration UI (secure storage)

## Phase 5: Polish & Delivery
- [x] UI polish: animations, transitions, empty states, loading skeletons
- [x] Vitest unit tests for backend procedures (25 tests passing)
- [x] PDF/Report export functionality
- [x] Final checkpoint and delivery


## Bug Fixes & Issues
- [x] Add navigation link to Job Descriptions page from Dashboard
- [x] Fix NewSession page file upload form submission
- [x] Verify tRPC job descriptions list query works
- [x] Test file upload to /api/sessions/:sessionId/upload-cvs endpoint
- [x] Ensure Google Drive OAuth flow is properly connected
- [x] Verify all form validations work correctly
