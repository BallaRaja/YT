# YouTube Homepage Clone

This project is a static recreation of the YouTube homepage using pure HTML and CSS. It mimics the core layout, including the header (with search bar and icons), sidebar navigation, and a grid of video previews. The design is responsive and adapts to different screen sizes using CSS media queries.

## Table of Contents

- Description
- Features
- Technologies Used
- Project Structure
- Installation
- Usage
- Screenshots
- Contributing
- License

## Description

This is a front-end only clone of the YouTube homepage as of the provided design (featuring elements like video thumbnails, channel profiles, and basic navigation). It does not include any JavaScript functionality (e.g., no interactive search, video playback, or dynamic content loading). The focus is on replicating the visual structure and styling for educational purposes or as a starting point for further development.

The video grid alternates between two sample videos:

- "Stranger Things 5 | Official Telugu Trailer | Netflix" from Netflix India.
- "Shang-Chi VS Xu Wenwu Final Fight | Shang-Chi and the Legend of the Ten Rings | Official Clip" from Marvel Entertainment.

Assets like thumbnails, profile pictures, and icons are referenced in the HTML and should be placed in the appropriate directories (e.g., thumbnails/, channel-pics/, icons/).

## Features

- **Header Section**: Includes a menu icon, YouTube logo, search bar with icons (search and voice), notification bell with count, and profile icon.
- **Sidebar Navigation**: Fixed sidebar with links for Home, Explore, Subscriptions, and Originals, each with SVG icons.
- **Video Grid**: Responsive grid displaying video previews with:
    - Thumbnails and video duration overlays.
    - Channel profile pictures.
    - Video titles, authors, view counts, and upload dates.
- **Responsive Design**: Uses CSS Grid and Flexbox for layout. Adjusts columns based on screen width:
    - 2 columns for screens < 750px.
    - 3 columns for screens 751px–999px.
    - 4 columns for screens ≥ 1000px.
- **Styling**: Custom CSS for hover effects, positioning, and typography.

## Technologies Used

- **HTML5**: For structure and semantic markup.
- **CSS3**: For styling, including Flexbox, Grid, media queries, and pseudo-elements.
- **SVGs and Images**: Inline SVGs for icons and external images for logos, thumbnails, and profiles.

No external libraries or frameworks are used.
