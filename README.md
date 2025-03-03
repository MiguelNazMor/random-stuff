# Random Stuff Blog

This is the source code for my personal blog where I share posts about technology, travels, cooking, software development, and more.

## Requirements

- Ruby 3.2.2 (managed with RVM)
- Bundler

## Local Development

To run this site locally:

1. Make sure you have RVM installed and Ruby 3.2.2:
```bash
rvm install 3.2.2
rvm use 3.2.2@random-stuff --create
```

2. Install Jekyll and Bundler:
```bash
gem install jekyll bundler
```

3. Install dependencies:
```bash
bundle install
```

4. Run the development server:
```bash
bundle exec jekyll serve
```

4. Visit `http://localhost:4000/random-stuff` in your browser

## Categories

- Technology
- Travels
- Cooking
- Software Development

## License

This project is open source and available under the [MIT License](LICENSE).
