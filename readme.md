Dr. Jekyll and Mr. Hyde
=============

This is a step by step short guide to install a simple blog with Jekyll, with no complications. It's just the core, no styles (yet).

1. Install Ruby.

2. Install Rubygems.

2. Instal Jekyll.

3. Install Bundle.

4. Open terminal. Go inside your folder project and type:

```bash
bundle init
```

5. A gemfile will be generate on your root project folder. Open the gemfile on your favorite code editor, and insert the line after all:

```bash
gem "jekyll"
```

6. Back to the terminal, type:

```bash
bundle install --path _vendor/bundle
```

7. Build the project typing:

```bash
bundle exec jekyll serve
```

8. Open your favorite browser and type:

```bash
http://127.0.0.1:4000
```
