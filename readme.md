# Crystal Beauty WordPress Theme

Crystal Beauty is a premium, custom-built WordPress theme designed specifically for beauty salons, spas, and wellness centers. Based on the elegant Crystal Beauty HTML template, this theme provides a seamless blending of aesthetics and functionality, featuring full WooCommerce integration and a custom appointment management system.

## 🌟 Key Features

- **Responsive Design:** Optimized for all devices, from desktops to mobile phones.
- **Appointment System:** Built-in appointment booking form with automated email notifications.
- **WooCommerce Ready:** Full support for selling products and services, including custom product types like "Package Service".
- **Dynamic Homepage:** Easily customize sections via the WordPress Customizer.
- **Shortcode Library:** A wide range of custom shortcodes for building various page sections effortlessly.
- **Gallery with Filtering:** Categorized gallery to showcase beauty services and results.
- **Testimonials & Experts:** Showcase client reviews and your team of experts.
- **Partner/Brand Integration:** Display logos of brands you work with.

## 🛠️ Technological Stack

- **PHP/WordPress:** Developed using modern WordPress coding standards.
- **Custom Functions:** Modular logic for WooCommerce enhancements, mailing, and custom UI components.
- **Frontend Plugins:**
  - **Owl Carousel:** For smooth, touch-enabled sliders.
  - **Isotope:** For filtered gallery layouts.
  - **Fancybox:** For media lightboxes.
  - **Selectize:** For enhanced dropdown selections.
  - **Datepicker:** For the appointment booking interface.
- **CSS Architecture:** Vanilla CSS with Bootstrap-compatible utility patterns.

## 🧩 Shortcode Reference Guide

The theme includes several custom shortcodes to build pages quickly:

| Shortcode | Description | Parameters |
|-----------|-------------|------------|
| `[appointment-form]` | Renders the booking form | `main-heading`, `sub-heading`, `heading-visibility` |
| `[about-section]` | Displays the "About Us" section | - |
| `[gallery]` | Displays the filtered photo gallery | - |
| `[slider]` | Renders the main homepage slider | - |
| `[offer]` | Shows products with active sale prices | - |
| `[call-to-action]`| Displays a CTA banner | - |
| `[contact-form]` | Renders the contact section | - |
| `[partner]` | Displays partner/brand logos | - |
| `[service]` | Lists beauty services | - |
| `[simple-products]`| Grid of simple WooCommerce products | - |
| `[testimonials]` | Client review carousel | - |
| `[experts]` | Team member profiles | - |
| `[package-service]`| Displays bundled service packages | - |
| `[container-start]`| Opening tag for content containers | - |
| `[container-end]` | Closing tag for content containers | - |

## 🚀 Installation & Setup

1. **Upload Theme:** Zip the project folder and upload it via `Appearance > Themes > Add New`.
2. **Activate:** Once uploaded, click "Activate".
3. **WooCommerce:** Ensure WooCommerce is installed and active to use shop and service features.
4. **Customize:** Navigate to `Appearance > Customize > Theme Homepage` to configure your site settings.

## 📂 Project Structure

- `/fns/`: Contains modular PHP functions (Shortcodes, Widgets, WooCommerce logic).
- `/template-parts/`: Reusable HTML/PHP snippets for the theme.
- `/plugins/`: Third-party assets used by the theme.
- `/js/` & `/css/`: Custom scripts and styling.
- `functions.php`: Theme entry point and feature initialization.
