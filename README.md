# VYBE — starter prototype

This is the first mobile-first VYBE product prototype. It includes:
- Discover, Likes, Messages, Flirt and Profile tabs
- Sample profiles and local-only demo interactions
- Conversation starter prompts and mood selector
- A separate visual admin dashboard starter
- An initial Supabase/PostgreSQL schema

## Important limitations
This is a **front-end prototype**, not a live dating service. It does not create real accounts, send messages, upload photos, verify age, process payments, or connect to a database. The sample profiles are fictional. Do not enter real sensitive information.

The admin page is only a visual starter and has no login or backend. It must be protected with real admin authentication and server-side authorization before use.

## Easiest way to preview from an Android phone
1. Download and extract this ZIP.
2. Open a browser-based coding workspace that supports importing a ZIP or GitHub repository (for example, StackBlitz).
3. Import the project folder.
4. Run `npm install`.
5. Run `npm run dev` and open the preview.
6. Open `admin/index.html` for the admin dashboard visual preview.

If your chosen browser workspace cannot run the project, use its GitHub import option or ask a developer to run the included Vite project.

## Next engineering steps
1. Create a Supabase project.
2. Review `supabase/schema.sql`; apply it only after adding and testing row-level security policies.
3. Implement authentication, profile creation and image storage.
4. Add server-side age verification and moderation workflows.
5. Implement secure matching and conversation membership.
6. Connect realtime chat only after authorization tests pass.
7. Add an authenticated admin application with role-based access control.
8. Evaluate app-store policies, Kenyan data protection obligations and payment provider requirements before launch.

## Brand direction
VYBE — Feel the chemistry.
Palette: near-black, wine red, hot pink and violet.
