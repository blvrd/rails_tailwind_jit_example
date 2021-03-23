# Rails Tailwind JIT Example

**Warning: this has not been tested in production**

This repo is meant to be a barebones example how to set up [Tailwind's new JIT feature](https://github.com/tailwindlabs/tailwindcss-jit) in Rails **without** Webpacker.

## Getting up and running

- `bin/setup`
- `bin/rails server`
- Add some more markup and Tailwind classes to `app/views/pages/index.html.erb`
- Visit `localhost:3000` and enjoy using Tailwind without the multi-megabyte CSS payload in development!