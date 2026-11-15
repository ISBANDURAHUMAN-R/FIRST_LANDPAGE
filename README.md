<p align="center">
  <img src="assets/banner.png" alt="FIRST_LANDPAGE Banner" width="100%">
</p>

# ◈ Moon Landing Page

[![CI](https://github.com/ISBANDURAHUMAN-R/CODSOFT_taskno_LANDPAGE/actions/workflows/ci.yml/badge.svg)](https://github.com/ISBANDURAHUMAN-R/CODSOFT_taskno_LANDPAGE/actions/workflows/ci.yml)

## ◆ About the Project
Moon Landing Page is a responsive promotional webpage developed using HTML and CSS as part of the CodSoft Web Development Internship. The project demonstrates core front-end styling principles including CSS Flexbox layouts, typography hierarchy, and asset composition.

## ❖ Key Features
- Central hero section with heading typography, descriptive body text, and call-to-action buttons.
- Responsive layout adapting smoothly to desktop, tablet, and mobile viewport sizes.
- Clean lunar aesthetic featuring custom CSS styling and imagery.

## ◆ System Architecture
```mermaid
graph TD
    subgraph DOMStructure ["HTML5 Document Object Model"]
        Head["Document Head<br/>Meta Tags & Viewport Configuration"]
        Body["Document Body Root"]
        Body --> Nav["Navigation Bar & Brand Identity"]
        Body --> Hero["Hero Section Container"]
        Hero --> Content["Headline & Descriptive Copy"]
        Hero --> CTA["Call-to-Action Action Buttons"]
        Hero --> Visual["Hero Visual Asset / moon.jpg"]
    end

    subgraph StylingPipeline ["CSS3 Layout Engine"]
        Reset["CSS Global Reset & Typography"] --> FlexBox["CSS Flexbox Alignment"]
        FlexBox --> MediaQueries["Responsive Breakpoints<br/>Desktop • Tablet • Mobile"]
        MediaQueries --> VisualStyles["Color Contrast & Hover Transitions"]
    end

    subgraph ClientExecution ["Browser Runtime"]
        DOMStructure --> RenderTree["Render Tree Construction"]
        StylingPipeline --> RenderTree
        RenderTree --> LayoutPass["Layout & Paint Engine"]
        LayoutPass --> Viewport["Responsive Browser Display"]
    end
```

## ⬢ Technologies Used
- HTML5
- CSS3

## § Requirements
- Modern web browser

## ▲ Installation & Execution
```bash
# Open index.html directly or serve locally
python -m http.server 8000
```
Open `http://localhost:8000` in your web browser.

## ※ Developer
Developer: ISBANDU RAHUMAN R  
GitHub: https://github.com/ISBANDURAHUMAN-R
