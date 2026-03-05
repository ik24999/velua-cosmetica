# Responsive Design

- Mobile-first: write base styles for mobile, then use `sm:`, `md:`, `lg:`, `xl:` for larger screens.
- Breakpoints (Tailwind defaults): sm=640px, md=768px, lg=1024px, xl=1280px, 2xl=1536px.
- Navigation must collapse into a hamburger menu on mobile.
- Touch targets must be at least 44x44px on mobile.
- Test at these widths: 375px (phone), 768px (tablet), 1024px (laptop), 1440px (desktop).
- Use `max-w-7xl mx-auto px-4` as the standard content container.
- Images must be responsive: `w-full h-auto` or use `object-cover` with fixed height.
- Hide non-essential elements on mobile with `hidden md:block` if they clutter the UI.
- Avoid horizontal scroll — never use fixed widths wider than the viewport.
