# headway-changepack

This repository contains a Ruby script that allows for a seamless migration of your blog posts from the Headway platform to Changepack. It automatically scrapes posts from a Headway blog, extracts the title, content, and publication date, and paginates through all blog pages. The resulting output is an array of hashes ready for import to the open-source changelog platform Changepack.

The tool provides a convenient solution for users transitioning from Headway to Changepack, eliminating manual data transfer and ensuring a smooth migration experience.

This script is intended to be used exclusively for your own blog posts or changelogs. It is not designed, nor should it be used, for copying content from other companies or changelogs. Misuse of this script can violate terms of service and infringe upon others' copyright. Please use responsibly and respect the intellectual property rights of others.

## Build and run locally

```
git clone https://github.com/changepack/headway-changepack.git
cd headway-changepack

# Install dependencies
bundle install

# Run the import script
SOURCE_URL=https://www.example.com CHANGEPACK_URL=https://changepack.test API_TOKEN=your_token_here bundle exec bin/import
```
