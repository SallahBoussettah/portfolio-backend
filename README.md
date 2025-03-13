# Portfolio Backend

This is the backend for the portfolio website, built with Netlify serverless functions.

## Features

- RESTful API endpoints for portfolio data
- Contact form submission handling
- Mock data for development and demonstration
- CORS enabled for frontend integration
- Ready for Netlify deployment

## API Endpoints

### Blog Posts
- `GET /api/blog` - Get all blog posts (with optional filtering)
- `GET /api/blog/:id` - Get a specific blog post by ID

### Projects
- `GET /api/projects` - Get all projects (with optional filtering)
- `GET /api/projects/:id` - Get a specific project by ID

### Artwork
- `GET /api/artwork` - Get all artwork (with optional filtering)
- `GET /api/artwork/:id` - Get a specific artwork by ID

### Skills
- `GET /api/skills` - Get all skills data
- `GET /api/skills/:category` - Get skills by category

### Contact
- `POST /api/contact` - Submit contact form

## Setup

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Create a `.env` file based on `.env.example`
4. For local development, install the Netlify CLI:
   ```
   npm install -g netlify-cli
   ```
5. Run the development server:
   ```
   netlify dev
   ```

## Deployment

1. Connect your repository to Netlify
2. Configure the build settings:
   - Build command: `npm run build` (if applicable)
   - Publish directory: `public`
   - Functions directory: `functions`
3. Set up environment variables in the Netlify dashboard
4. Deploy!

## Future Enhancements

- Database integration (MongoDB, PostgreSQL, etc.)
- Authentication for admin access
- Content management system
- Image upload and storage
- Analytics integration

## License

MIT