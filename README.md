# Short URL
# Short URL Generator - Laravel Project

This is a Laravel-based project for generating and managing short URLs. Users can register, log in, and create shortened URLs for any long URLs they provide. The system tracks the number of times each short URL is clicked and allows users to manage their profile. Future features will include support for non-authenticated users with temporary URLs that expire after 24 hours.

## Project Demo

You can access the project [here](https://shorturl.nymul-islam-moon.com/registration).

## Features

- **User Registration and Login**: Users must register and log in to use the system.
  - After registering, the "Login Here" button redirects users to the login page.
- **Short URL Generation**: 
  - Users can input a long URL into the provided field on the home page.
  - Upon clicking the "Generate" button, a new row is added to the table containing:
    - Original URL
    - Generated short URL
    - Click count
    - Delete action button
- **Click Tracking**: Every time a short URL is clicked or searched, the click count increments by 1 in real-time.
- **URL Management**: 
  - Users can copy the generated short URL to use anywhere.
  - Users can delete short URLs directly from the table.
- **Profile Management**: Users can update their profile details, including uploading a profile photo.
- **Upcoming Features**:
  - Allow non-authenticated users to create URLs with a 24-hour expiration limit.
  - Additional features to be added in future releases.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/nymul-islam-moon/short-url.git

