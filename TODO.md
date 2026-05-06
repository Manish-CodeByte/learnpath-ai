# TODO - LearnPath AI Transformation

## Step 1 — Branding audit + update (approved)
- [x] Search for occurrences of “Study Board/StudyBoard”
- [ ] Update `app/layout.tsx` metadata (title/description already present: verify)
- [x] Update landing hero headline/subheading/CTAs + footer and marketing copy in `components/landing-page.tsx`

- [x] Update logo text from “Study Board” to “LearnPath AI” in `components/ui/logo.tsx`

- [ ] Update remaining docs/legal/onboarding/email branding strings where needed

## Step 2 — Futuristic UI palette + premium styling
- [ ] Align base dark theme variables to requested palette (#0F172A, #6366F1, #8B5CF6, #06B6D4, #F8FAFC)
- [ ] Ensure glassmorphism cards + glowing gradients are applied consistently

## Step 3 — Dashboard content mapping
- [ ] Update `components/dashboard/dashboard-view.tsx` and widgets to show the 7 education sections
- [ ] Update sidebar labels to education-path naming

## Step 4 — AI roadmap generation flow
- [ ] Locate Gemini API usage under `app/api/ai/*`
- [ ] Implement/extend endpoint to generate roadmap + recommended skills
- [ ] Add “Generate Roadmap” UI with loading + skeleton states

## Step 5 — Weekly goals, skill tracking, analytics
- [ ] Add/skin Weekly Goals card
- [ ] Add/skin Skill Tracking
- [ ] Add/skin Completion Analytics (Recharts)

## Step 6 — Final QA
- [ ] Run lint/build
- [ ] Smoke test: Landing page + auth + roadmap generation

