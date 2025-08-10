## Getting Started

This project require some prequesites and dependenscies to be installed, you can view it online using this [demo](https://forkify-steel-seven.vercel.app/). or you can find the instructions below

> To get a local copy, follow these simple steps :

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Anhthuan25022003/FORKIFY_CLONE
   ```
2. Go to project folder

```bash
cd forkify
```

3. install dependencies

```bash
npm install
```

4. Run start script

```bash
npm start
```

#### Tree structure

```
forkify
│   .gitignore
│   .prettierrc
│   index.html
│   package-lock.json
│   package.json
│   README.md
│
└───src
    ├───img
    │       favicon.png
    │       forkify-architecture-recipe-loading.png
    │       forkify-flowchart.png
    │       icons.svg
    │       logo.png
    │       preview.png
    │
    ├───js
    │   │   config.js
    │   │   controller.js
    │   │   helpers.js
    │   │   model.js
    │   │
    │   └───views
    │           addRecipeView.js
    │           bookmarksView.js
    │           paginationView.js
    │           previewView.js
    │           recipeView.js
    │           resultsView.js
    │           searchView.js
    │           View.js
    │
    └───sass
            main.scss
            _base.scss
            _components.scss
            _header.scss
            _preview.scss
            _recipe.scss
            _searchResults.scss
            _upload.scss
```

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
