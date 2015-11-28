

# JSTxt2epub

- A tiny js library for converting TEXT to EPUB(Blob data type)

## How to Use

- include the following js file in the header of the html file
`<script src="txt2epub.js"></script>`

## Example

- create a new epub object
- epub = new JSTxt2epub.newEpubFile("Book Title", "Book Author");

- add the cover image
- `Epub.addCoverImage(ImageDataUrl);`

- add the title and content of chapter in order
- `epub.addChapter("Chapter Title", "Chapter Content");`

- generate the Blob of EPUB
- `blob = epub.generateBlobUrl();`

