# Calcite Website

This is the official website for Calcite, an open-source multipurpose Discord bot. The website is built using Zola static site generator and Tailwind CSS.

## Prerequisites

- [Zola](https://www.getzola.org/documentation/getting-started/installation/) (v0.17.0 or later)
- Node.js and npm (for development)

## Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/calcite-website.git
cd calcite-website
```

2. Start the development server:
```bash
zola serve
```

The website will be available at `http://127.0.0.1:1111`

## Building

To build the website for production:

```bash
zola build
```

The built files will be in the `public` directory.

## Project Structure

- `content/` - Contains the website content in Markdown format
- `templates/` - Contains the Tera templates
- `static/` - Contains static assets (images, CSS, etc.)
- `config.toml` - Zola configuration file

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 