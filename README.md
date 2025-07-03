System Architecture Overview                                             │
│                                                                                                                      │
│                                                  Backend (FastAPI)                                                   │
│                                                                                                                      │
│ Your backend is a well-structured mental health support API built with FastAPI that provides:                        │
│                                                                                                                      │
│ Core Features:                                                                                                       │
│                                                                                                                      │
│  • User Authentication & Registration - Phone-based login with optional Google OAuth                                 │
│  • Mental Health Assessments - GAD-7 (anxiety) and PHQ-9 (depression) scoring                                        │
│  • 4-Session Therapy Program - Structured CBT-based therapy sessions                                                 │
│  • AI-Powered Chat - Multiple chat interfaces using Google Gemini AI                                                 │
│  • Career Counseling - Dedicated counseling module with form submission                                              │
│  • Payment Integration - Razorpay for practitioner bookings                                                          │
│  • Progress Tracking - Homework assignments and improvement visualization                                            │
│                                                                                                                      │
│ Technical Stack:                                                                                                     │
│                                                                                                                      │
│  • Framework: FastAPI with Pydantic models for validation                                                            │
│  • Database: Supabase (PostgreSQL) with async connections                                                            │
│  • AI/ML: Google Gemini AI, LangChain for conversation management                                                    │
│  • Caching: Redis for chat history storage                                                                           │
│  • Logging: Comprehensive production-ready logging system                                                            │
│  • Security: CORS, input validation, environment-based configuration                                                 │
│                                                                                                                      │
│                                               Frontend (React + Vite)                                                │
│                                                                                                                      │
│ Your frontend is a modern React SPA that provides:                                                                   │
│                                                                                                                      │
│ Key Components:                                                                                                      │
│                                                                                                                      │
│  • Authentication Flow - Login/Register with phone number validation                                                 │
│  • Main Chat Interface - Primary therapy chat with AI therapist                                                      │
│  • Career Counseling - Separate counseling interface with form submission                                            │
│  • User Profile Management - Profile settings and data management                                                    │
│  • Reports & Progress - Visual progress tracking and PDF generation                                                  │
│                                                                                                                      │
│ Technical Features:                                                                                                  │
│                                                                                                                      │
│  • React Router for navigation                                                                                       │
│  • Axios for API communication                                                                                       │
│  • Bootstrap for styling                                                                                             │
│  • PDF Generation with jsPDF                                                                                         │
│  • Real-time Chat interfaces                                                                                         │
│                                                                                                                      │
│                                                                                                                      │
│                                              Key Architectural Patterns                                              │
│                                                                                                                      │
│  1 Modular Design - Clear separation between endpoints, models, and business logic                                   │
│  2 Async/Await - Full async support for database and AI operations                                                   │
│  3 Error Handling - Custom exception hierarchy with proper logging                                                   │
│  4 Configuration Management - Environment-based settings with validation                                             │
│  5 API Documentation - Auto-generated OpenAPI docs at /docs                                                          │
│                                                                                                                      │
│                                                                                                                      │
│                                                      Data Flow                                                       │
│                                                                                                                      │
│  1 User authenticates via phone number                                                                               │
│  2 Completes mental health assessments (GAD-7, PHQ-9)                                                                │
│  3 Engages in structured therapy sessions with AI                                                                    │
│  4 Can access career counseling with separate AI counselor                                                           │
│  5 Progress is tracked and visualized over time                                                                      │
│                                                                                                                      │
│                                                                                                                      │
│                                                   Notable Features                                                   │
│                                                                                                                      │
│  • Multi-language Support - Configurable language preferences                                                        │
│  • Session Management - Redis-based chat history persistence                                                         │
│  • Comprehensive Logging - Production-ready logging with structured format                                           │
│  • Payment Integration - Razorpay for monetization                                                                   │
│  • Mobile-Responsive - Bootstrap-based responsive design                                                             │
│                                                                                                                      │
│ The codebase demonstrates good software engineering practices with proper separation of concerns, comprehensive      │
│ error handling, and production-ready features.            
