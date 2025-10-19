# HEMS Logger v1.4.2 (Date Robust Fix)
- Replaced valueAsDate with local formatter (YYYY-MM-DD) to avoid iOS timezone bug.
- Updates date on load, after Save, on app resume, and checks periodically for midnight rollover.
- Keeps v1.4 features (Flight Time HH:MM, compact log).