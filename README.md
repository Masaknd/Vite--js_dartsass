# Vite--js_dartsass

this is a prototype vite compiler for MPA with Vanilla JS and sass

A bug: inconsistency of the result of running dev mode and build
Problem; running dev mode doesn't compile scss link directory to css on html thus changes are not reflected on HRM

Discovering the solution of the problem above and found some resources below:
https://github.com/vitejs/vite/issues/4556

I tried "vite-plugin-rewrite-all" but didn't work for my project
