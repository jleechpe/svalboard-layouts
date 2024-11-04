# Running Hugo for testing

## Setup

1. Install [Hugo](https://gohugo.io/installation/)
2. Run Dev Server
   ```sh
   hugo server --buildDrafts
   ```
3. Navigate to https://localhost:1313/ to view

## Adding Layouts

1. Copy an existing markdown (.md) file in `/content/layouts` renaming it to
   your desired layout name
2. Copy your `.vil` or `.kbi` file to the `/content/layouts` folder, ensuring
   the name matches your markdown file.
3. Customize the markdown file with your information:
   - Update Params block to reflect `vil` or `kbi` as appropriate
   - Update Params block to reflect appropriate Author
   - Update Title to match layout title
   - Update tags as appropriate
   - Add content below the `+++` that ends the front matter.
   
## Future Improvements

1. Create archetype/template for new layouts to simplify update steps
2. General theming/etc.
