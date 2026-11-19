# AP Physics 2 — Unit 12 student website

Start: open `index.html` in a web browser (works offline).

Included:
- `index.html`: Unit 12 student homepage
- `equations.html`: all seven equations in the MAGNETISM portion of the AP Physics 2 reference sheet and four relevant constants
- `12.1/index.html`: 23 click-to-reveal discussion questions, 20-question self-marking quiz with two feedback modes, and Next Unit Prep
- `12.1/12.1_Student_Worksheet.pdf`: questions with handwriting lines
- `12.1/12.1_One_Page_Summary.pdf`: one-page revision sheet
- `assets/*.svg`: crisp vector diagrams, geometrically constructed as **schematic** representations. The bar magnet diagram explicitly shows complete N-to-S external and S-to-N internal loops.
- `12.2/index.html`: 40 guided discussion questions (answers revealed on click), step-by-step derivations and worked examples, two embedded interactive tools, 28-item MCQ with two feedback modes, and Next Unit Prep.
- `12.2/moving-charge-field.html`: independent moving-charge source-field explorer; drag observation point P, vary charge sign and speed; illustrates B direction and *relative* magnitude. Uses an idealized low-speed source-field model; numerical point-charge-field calculations are not required in AP Physics 2.
- `12.2/visualizer.html`: topic-specific, separate copy of the previously created 3D Version 6 visualizer; defaults to Charge questions and retains particle motion modes. The original V6 HTML is NOT modified.
- `12.2/12.2_Student_Worksheet.pdf`: eight-page student worksheet with space for handwritten reasoning, blank vector and Hall-effect diagrams, and numerical calculations.
- `12.2/12.2_One_Page_Summary.pdf`: one-page physics summary and vectors.
- `assets/force_positive_negative.svg` and `assets/hall_effect_electrons.svg`: verified, crisp vector illustrations (no AI art).
- `12.3/`, `12.4/`, `experimental-design/`, `revision/`: working **Coming soon** placeholder pages.

The homepage now activates Topic 12.2; Topic 12.1 remains unchanged.

Topic 12.2 scope notes:
- College Board CED 12.2.A: direction and qualitative strengths of magnetic fields produced by moving charged objects.
- College Board CED 12.2.B: force on moving charge, right-hand rule, independent electric and magnetic forces, and Hall effect.
- College Board boundary: numerical magnetic-force calculations use only 0°, 90°, 180° between velocity and magnetic field; other angles qualitative.
- Circular orbit radius and velocity-selector speed are explicitly *derived* applications, not additional printed AP magnetism equations.
- Animated 3D field/motion visualizer and interactive field explorer are separate self-contained HTML files; they can also be opened directly and work without internet.

To add future topics, replace the contents of each placeholder folder's `index.html` and add its assets to `assets/`; homepage URLs will not need to change. No local web server, frameworks or network connection are required for the actual lessons or equation rendering. Official College Board links require internet access.

Curriculum sources:
- College Board CED Topics 12.1 and 12.2, printed pages 82–86; Topic 12.1 pages 82–84 (PDF pages 89–91), overview printed page 80 (PDF page 87): https://apcentral.collegeboard.org/media/pdf/ap-physics-2-course-and-exam-description.pdf
- College Board official AP Physics 2 reference information: https://apcentral.collegeboard.org/media/pdf/ap-physics-2-equations-sheet.pdf

Field diagrams are explanatory schematics, not numerical simulations of a finite bar magnet. Field-line direction, closed loop topology and domain alignment are represented faithfully.

Quiz: the twenty questions and answers are embedded in 12.1/index.html. Each new attempt randomizes answer positions. Immediate mode reveals an explanation after checking each attempted question; end mode withholds correctness/explanations until all questions have been answered and submitted.
