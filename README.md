

# JSTxt2epub

- A tiny js library for converting TEXT to EPUB(Blob data type)

## How to Use

- include the following js file in the header of the html file
```html
<script src="txt2epub.js" charset="UTF-8"></script>
```

## Example

- create a new epub object
```javascript
epub = new JSTxt2epub.newEpubFile("Book Title", "Book Author");
```

- add the cover image
```javascript
epub.addCoverImage(ImageDataUrl);
```

- add the title and content of chapter in order
```javascript
epub.addChapter("Chapter Title", "Chapter Content");
```

- generate the Blob of EPUB
```javascript
blob = epub.generateBlobUrl();
```
