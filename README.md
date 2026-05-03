# README.md

# Worknoon WordPress Assessment

## Project Overview
This project was developed as part of the Worknoon WordPress Developer (SEO + Systems Specialist) assessment. The objective was to create a lightweight, responsive, and SEO-optimised WordPress landing page while demonstrating system thinking, technical SEO understanding, schema implementation, and clean development practices.

The landing page was built using WordPress, Astra Theme, and Elementor with a focus on:

- Responsive UI/UX
- Performance optimization
- SEO readiness
- Clean architecture
- Scalable structure
- Minimal plugin usage

# Features
- Responsive landing page
- Hero section with CTA
- Services section
- Testimonials section
- Contact form integration
- Analytics integration
- Performance optimization
- Mobile responsiveness
- JSON-LD schema implementation

# Technologies & Tools Used

## CMS & Builder
- WordPress
- Elementor
- Astra Theme

## Plugins
- WPForms Lite
- WPCode Lite
- LiteSpeed Cache
- Cloudfare
- GTM4WP - A Google Tag Manager (GTM) plugin for WordPress

## SEO & Testing
- Google Rich Results Test
- Google PageSpeed Insights
- Chrome DevTools

## Version Control
- Git
- GitHub
All commits were done by uploading and editing files on github repository.

# Folder Structure

worknoon-wordpress-assessment/
│
├── README.md
│
├── wordpress-files/
│   ├── elementor-template/
│   ├── screenshots/
│   ├── plugins-used.md
│   └── local-setup-notes.md
│
├── schema/
│   ├── organization-schema.json
│   ├── person-schema.json
│   └── website-schema.json
│
├── docs/
│   ├── knowledge-panel-strategy.md
│   ├── seo-diagnosis.md
│   ├── short-answers.md
│   └── system-thinking-reflection.md
│
└── assets/
    ├── logo/
    └── images/

# Setup Instructions
1. Install WAMPServer
2. Install WordPress locally
3. Install Astra Theme
4. Install Elementor plugin
5. Install required plugins:
   * LiteSpeed Cache
   * Elementor
   * WPForms Lite
   * WPCode Lite
   * Cloudfare
   * GTM4WP - A Google Tag Manager (GTM) plugin for WordPress
   
6. Configure responsive settings
7. Optimize images before upload

# Performance Optimization
The following optimization practices were implemented:

* Lightweight Astra theme
* Optimized image sizing and compression
* Minimal plugin installation
* Full-width responsive layout
* LiteSpeed Cache configuration
* Avoided unnecessary scripts and widgets
* Mobile-first responsive adjustments

# SEO & Schema Implementation
JSON-LD schema markup was implemented for:
* Organization
* Person
* Website

This improves:

* Search engine understanding
* Entity recognition
* Knowledge Graph eligibility
* Rich search result opportunities

Schema files are included in the `/schema` directory.

# Architecture Decisions

## Why Astra?
Astra was selected because it is lightweight, performance-focused, SEO-friendly, and integrates efficiently with Elementor.

## Why Elementor?
Elementor allows for rapid responsive page development while maintaining a clean visual structure and flexible layout control.

## Why Minimal Plugins?
Reducing plugin usage improves:
* performance
* maintainability
* security
* scalability

# Challenges Encountered

## Responsive Layout Adjustments
Some sections required custom spacing and typography adjustments for mobile responsiveness.

### Resolution
Elementor responsive controls were used to optimize spacing, font sizing, and layout stacking.

## Website Analytics
Site Kit plugin by Google did not work.

### Resolution
I used GTM4WP - A Google Tag Manager (GTM) plugin for WordPress.

## Performance Optimisation
Larger images increased page load time.

### Resolution
Images were compressed and converted to optimized formats before being uploaded to the media library.

# System Thinking Reflection
This project was approached as a lightweight scalable web system rather than only a visual landing page.

Key considerations included:

* maintainable structure
* SEO readiness
* performance optimization
* entity-based schema implementation
* clean user experience
* scalability for future growth

Tradeoffs considered:

* Using a lightweight theme instead of feature-heavy multipurpose themes
* Avoiding unnecessary animations to improve performance
* Prioritising responsiveness and clarity over excessive visual complexity

If rebuilding this project, future improvements would include:

* advanced schema relationships
* headless WordPress architecture
* automated SEO auditing
* improved accessibility testing

# Analytics Integration
Google Analytics integration was implemented using the GTM4WP - A Google Tag Manager (GTM) plugin for WordPress.

This enables:
* traffic monitoring
* performance tracking
* behavioural insights
* conversion analysis

# Demo Video
Demo Video Link:
(https://www.loom.com/share/60a69f881e584be79be795a1247cf2e1
https://www.loom.com/share/5d70a3c7468441a9990009a3c6330e6e
https://www.loom.com/share/eb36556dfd284978a484552a93a22e6c)

# Author
Developed by Oluwaseun Abiodun
