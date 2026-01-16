A powerful Text → Handwriting web application that converts typed text into realistic handwritten pages, designed to closely resemble real student exam notebooks.

This project goes beyond simple font rendering and simulates human handwriting behavior, including mistakes, corrections, pressure variations, and pencil effects.

🚀 Features
📝 Core Features

Convert typed text into handwritten pages

Multiple handwriting fonts

Custom font upload (.ttf, .otf)

Ink color selection (Blue / Black / Red)

Font size, spacing, margins, and page controls

A4 page layout

Image & PDF export

Dark mode support

Works on desktop & mobile

✏️ Advanced Human-Like Realism (Key Highlight)

This project simulates real human handwriting imperfections, including:

✔ Pencil-Style Margin Line

Pencil-black margin line only

Slight blur & uneven graphite texture

Looks hand-drawn, not digital

✔ Handwriting Mistakes & Corrections

Letter-level overwriting

Half-erased words with smudge marks

Strike-outs & exam-style scribble corrections

Caret correction marks (^) above words

✔ Exam Behavior Simulation

Pressure increases near bottom of page

Ink fade variation across page

Panic scribbles near page end

Random letter tilt per font

Different mistake profiles per handwriting font

✔ Handedness Logic

Left-hand vs right-hand smudge near margins

Applied randomly per page for realism

🧩 Diagram Support

Draw diagrams using canvas

Upload diagram images

Auto-fit diagrams into paper

Realistic scanned / pencil look

Exported diagrams appear inside handwritten page

🖼 Output Examples

Looks like real handwritten assignments

Suitable for:

College assignments

Exam practice sheets

Notes

Demonstrations & prototypes

⚠️ This project is for educational and demonstration purposes only.

🛠 Tech Stack

HTML5

CSS3

JavaScript (ES Modules)

Canvas API

html2canvas

jsPDF

PWA support

No backend required — runs entirely in the browser.

📂 Project Structure
text-to-handwriting/
│
├── index.html
├── css/
│   ├── index.css
│   ├── features.css
│
├── js/
│   ├── app.mjs
│   ├── helpers.mjs
│   ├── generate-utils.mjs
│   ├── draw.mjs
│
├── fonts/
│   ├── QESamRoberts.ttf
│   ├── QEBradenHill.ttf
│   ├── QEBEV.ttf
│
├── images/
├── manifest.webmanifest
└── README.md

⚙️ How It Works (High Level)

User types or pastes text

Text is processed with:

Randomized human mistakes

Letter-level transformations

Font-specific behavior

Page styling simulates:

Pencil ink

Pressure variation

Margin smudges

Canvas rendering converts page into image

Images can be:

Downloaded individually

Exported as a PDF

📱 Mobile Support

Touch-enabled diagram drawing

Responsive layout

Optimized canvas resolution for mobile devices

🧪 Experimental Features

Upload custom handwriting fonts

Upload custom paper backgrounds

Diagram canvas overlay

(Some features may behave differently across browsers.)

📌 Known Limitations

Some fonts may require spacing adjustments

Not all handwriting fonts behave identically

Diagram realism depends on image quality

📜 License

This is a read-only educational project.

You are free to:

Study the code

Modify for personal learning

Build your own version

You may not claim this project as original work if redistributed.

🙌 Credits

Inspired by real student handwriting behavior, exam patterns, and notebook layouts.

Built with a strong focus on visual realism and human imperfection.

⭐ Final Note

This is not just a “text to handwriting” tool —
it is a handwriting simulation engine.