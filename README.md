# Build Your Own Gatsby Photo Gallery with Strapi & Cloudinary

The Strapi-powered backend for our [Gatsby photo gallery](https://github.com/sitepoint-editors/gatsby-gallery).
Comes with pre-defined `Tags` and `Images` content types.

## Requirements

* [Node.js](http://nodejs.org/) v12+
* [Yarn](https://yarnpkg.com/)
* [Cloudinary account](https://cloudinary.com/)

## Installation Steps

1. Clone repo
2. Run `yarn install`
3. Run `yarn run build`
4. Run `yarn start`
5. Create an admin user at http://localhost:1337/admin
6. Create three tags, for example `Favorites`, `Animal` and `Landscape`
7. Enter Cloudinary details: _Plugins_ > _Files Upload_ > _Gear icon_ > _Upload Settings_
8. Upload images and tag them accordingly
9. Allow public access to the `Tags` and `Images` content types: _Roles and Permissions_ > _Public_ > Tick _find_ and _findone_ checkboxes for `Tag` and `Image`.

## License

SitePoint's code archives and code examples are licensed under the MIT license.

Copyright © 2020 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
