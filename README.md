# PMKIN Next.js Blog with Bootstrap 4

This project demonstrates how to create a blog using [PMKIN](https://pmkin.io), [Next.js](https://nextjs.org/), and Bootstrap 4. It showcases the power of combining a modern Headless CMS with a fast and flexible React framework, all styled with the popular Bootstrap library.

## Features

- Fetches blog posts from PMKIN using GraphQL
- Server-side rendering with Next.js for optimal performance
- Responsive design using Bootstrap 4
- Dynamic routing for individual blog posts
- Easy content management through PMKIN's user-friendly interface

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or later)
- npm (v6 or later)
- A PMKIN account with an API key

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/pmkin-nextjs-blog.git
   cd pmkin-nextjs-blog
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your environment variables:
   Create a `.env.local` file in the root directory and add your PMKIN API key:
   ```
   PMKIN_API_KEY=your_api_key_here
   ```

4. Run the development server:
   ```
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

- `pages/` - Next.js pages, including the main blog listing and individual post pages
- `components/` - Reusable React components
- `styles/` - Global styles and Bootstrap customizations
- `lib/` - Utility functions and API client setup

## Key Files

- `pages/index.js` - The main blog listing page
- `pages/blog/[slug].js` - Dynamic route for individual blog posts
- `lib/apollo-client.js` - Apollo Client setup for GraphQL queries

## Customization

- Modify the GraphQL queries in `pages/index.js` and `pages/blog/[slug].js` to fetch additional fields from PMKIN.
- Adjust the styling by editing the Bootstrap variables in `styles/custom-bootstrap.scss`.
- Create new components in the `components/` directory to extend functionality.

## Deployment

This project can be easily deployed to platforms like Vercel or Netlify. Make sure to set up your environment variables in your deployment platform's settings.

## Learn More

To dive deeper into the technologies used in this project, check out the following resources:

- [PMKIN Documentation](https://pmkin.io/developers/docs/introduction)
- [Next.js Documentation](https://nextjs.org/docs)
- [Bootstrap 4 Documentation](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [Apollo Client Documentation](https://www.apollographql.com/docs/react/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
