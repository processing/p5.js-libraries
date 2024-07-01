# ⚠️ Submissions are moved! ⚠️

We have submission instructions on the new `p5.js-website` repo here: https://github.com/processing/p5.js-website/blob/main/docs/contributing_libraries.md

# p5.js Libraries

p5.js welcomes libraries contributed by others! <a href="https://github.com/processing/p5.js/blob/main/contributor_docs/creating_libraries.md">Check out the libraries tutorial</a> for more specifics about how to create one. If you have created a library and would like to have it included in the list, follow the instructions below!

1. Fork the repo
2. Add a file to the `libraries` folder named `yourLibraryName.yaml` (or consider <a href="https://github.com/processing/p5.js-libraries/blob/main/libraries/p5.warp.yaml">copying an existing library</a> as a starting point)
3. Inside it, add the following content:
    - `name`: The name of the library
    - `category`: A category that you think best fits your library. Your choices include: `drawing`, `color`, `ui`, `math`, `physics`, `algorithms`, `3d`, `ai-ml-cv`, `animation`, `shaders`, `language`, `hardware`, `sound`, `data`, `networking`, `export`, or `utils`.
    - `description`: A one-sentence description of the library
    - `author`: An object containing `name`, your name, and `url`, an optional link to your website. If there are multiple authors, use an array of author objects.
    - `sourceUrl`: A link to the library's source code (e.g. its repo on GitHub or GitLab)
    - (Optional) `websiteUrl`: A link to a website for the library
    - (Optional) `npm`: If applicable, the package name for the library on <a href="https://www.npmjs.com/">npm</a>
    - (Optional) `npmFilePath`: A path like `'dist/library.min.js'` if a specific file in the library should be used from npm. You can test this out by going to `https://cdn.jsdelivr.net/npm/packageName` -- if that doesn't work, try `https://cdn.jsdelivr.net/npm/packageName/path/to/file.js` and put the path you added into this property
    - `featuredImage`: An object about the preview thumbnail for the library, with `url`, the path to the image in the `src/content/libraries/images` folder, and `altText`, a short description of its contents for screen readers
    - (Optional) `license`: A <a href="https://docs.npmjs.com/cli/v10/configuring-npm/package-json#license">string describing the software license of the library.</a> This may be omitted if your package is on npm and has license info there
4. Add a **high-res colored image of 1500x1000px** of your library into `libraries/images`
5. Submit a pull request and we'll review your submission

We add libraries that are open-source, includes some documentation and examples, and <a href="https://github.com/processing/p5.js/blob/main/CODE_OF_CONDUCT.md">follow our code of conduct.</a>

If you have any questions, feel free to open an issue or create a work-in-progress PR and ask us anything!
