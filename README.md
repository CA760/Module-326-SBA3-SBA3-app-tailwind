# Frontend Mentor - Chat App Illustration

## Project Overview

This project is a responsive implementation of the **Chat App tailwind Illustration** challenge from [Frontend Mentor](https://www.frontendmentor.io/). The page recreates a mobile chat interface for a dog-walking booking service, alongside a short description of the service. The interface includes a profile header, incoming and outgoing messages, dog photos, walk-payment options, and a message input area.

## Approach and Customizations

The layout is built with HTML, CSS style, and CSS was changed to Tailwind CSS utility classes. Flexbox is used to arrange the phone mockup and description, while Tailwind responsive variants adapt the layout for larger screens. Custom color values, gradients, rounded message bubbles, and spacing utilities reproduce the challenge's visual style.



## Challenges and Solutions

New to tailwind so it was hard to design with tailwind. The signed was done in CSS style and later chance to tailwind which was hard. One challenge was preventing the phone from shrinking when it was placed in a flex layout. This was addressed with `shrink-0` and fixed width and height utilities. Another challenge was controlling the stacking order of the decorative background shapes and the phone. Positioning and z-index utilities keep the phone and description above the background. Finally, overflow utilities remove scrollbars; because scrolling is disabled, the chat content needs to fit within the phone's available height.

## Reflection

Building this project helped me practise translating a design into a responsive layout with Tailwind CSS. One challenge was keeping the phone mockup at a consistent size inside a flex container. I solved this by applying `shrink-0` and setting explicit width and height values. I also had to manage the decorative background shapes so they would not cover the phone or description, which I addressed with positioning and z-index utilities. Removing scrolling made the presentation cleaner, but it also meant I had to pay closer attention to the amount of content that could fit inside the phone. If I had more time, I would refine the spacing and proportions against the original challenge design, test the page at more screen sizes, and improve accessibility with clearer image descriptions and semantic labels. I would also consider making the message input interactive rather than leaving it as a visual element.
