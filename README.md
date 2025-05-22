# Lab 7
Pranay Jha

Disclaimer: had to change the timeout to 15000 for certain tests (TODOs 3 and 6) since they didn't run fast enough on my machine.

1. Within a GitHub action that runs whenever code is pushed (1). This ensures consistency since it runs in a clean environment, we get very fast feedback, and ensures any code that is merged from a future PR is up to the quality standard and passes any tests.
2. No, we would use a unit test for this.
3. Navigation mode loads the page from scratch and captures network and rendering metrics, while Snapshot mode runs audits against the already-loaded DOM for site-specific metrics.
4. We could:
- Preload the Largest Contentul Paint image to reduce render time.
- Minify the JS files to reduce the payload size and script parse times.
- Properly size images so the browser doesn't have to scale it down to save cellular data and improve load times.






