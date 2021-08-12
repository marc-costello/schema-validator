v2.0.0
=============================
BREAKING
- validateSchema now returns _errors_ and _warnings_ separately, rather than concatenating them together. Consumers can now choose if they want to treat warnings as show stoppers.