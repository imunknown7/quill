# quill
a minimal markdown powered personal blog and static site generator built with HTML, CSS, and JavaScript.

![quill](assets/images/screenshot1.png)

## description
quill is a lightweight blogging system designed around a simple workflow:

> Write in Markdown → Build → Publish

instead of relying on large frameworks, quill converts markdown files into static HTML pages that can be hosted anywhere, including github pages. it is designed to integrate seamlessly with markdown file editors such as obsidian, allowing you to write notes locally and publish them as a clean, searchable website. this site was primary built to work in hand with obsidian by linking folders from your vault to the posts directory in this project. 

## features
- markdown based writing
- static html generator
- automatic post listing
- tags support
- search function
- syntax highlighting
- obsidian friendly workflow

## installation
1. clone the repository
```
git clone https://github.com/imunknown7/quill.git
cd quill
```

2. install dependencies
```
npm install
```

3. build the site
```
npm run build
```

4. edit your posts and host to github pages or any hosting service to view your quill blog page.

NOTE : everything you edit posts or create new posts you have to run `npm build` and then go into the hosting process.