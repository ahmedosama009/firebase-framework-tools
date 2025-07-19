# **App Name**: AlKayan AI Hub

## Core Features:

- Dashboard: Display key metrics such as revenue, active clients, AI content generation volume, and upcoming calendar events. Personalised per tenant (company-level metrics only)
- Client Management (CRM): Manage and store client details. Track activity history, status (active/inactive), and interactions. Support both online and offline services
- Brand Identity Management: Each company can define brand tone, colors, and voice, select a primary language (Arabic by default), and add logos and brand descriptions. This data feeds into AI content generation
- AI Content Generation – “Spaces”: Each “Space” represents a service or offering. Users can describe the service, link it to brand identity, and trigger AI to generate content. AI respects brand tone, style, and preferred language (Arabic first)
- AI Sales Assistant – Leila: An AI tool assistant visible to users before login that handles onboarding and service selection inquiries. It speaks Arabic by default, switches to English if needed, and transfers conversations to other assistants if out of scope. First interaction allowed before login
- Multi-Tenant Architecture: Each organization (tenant) has its own dashboard and its own data (clients, spaces, brand, users). A Super Admin Panel exists for the platform owner to manage all tenants
- Authentication: Login/signup options: Google Sign-In and WhatsApp (via WhatsApp Cloud API). Session tracking and assistant history are stored post-login

## Style Guidelines:

- #000000
- #ffffff
- #a80000
- Space Grotesk (sans-serif)
- Minimalistic, line-based
- Subtle transitions, smooth loaders
- Arabic (primary), English (secondary)
- Full RTL & LTR switching dynamically