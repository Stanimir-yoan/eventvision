EventVision Camera Scan Prototype

What it does
- Requests rear camera through getUserMedia
- Lets you tap room corners over live video
- Closes the polygon and generates a top-view shape
- Lets you enter one real wall length to estimate scale/area

Important
- This is a UX prototype, not true AR measurement.
- iPhone camera access requires a secure HTTPS origin in most browsers.
- Opening index.html directly from Files may block live camera access.
- Host it on any HTTPS static host (e.g. Netlify Drop, GitHub Pages, Vercel) to test live camera reliably.

For true Apple Measure-style geometry, the next technical version should use native iOS ARKit/RoomPlan.
