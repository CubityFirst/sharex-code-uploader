# ShareX Snippet Uploader

Small little webpage that takes a ShareX input and renders it with highlight.js.
 This was made in around a day, and took way too much effort for it to work well.

![](https://i.imgur.com/AGTbBOE.gif)

Inside of Task Settings/Advanced/Upload text there's an option to include your own HTML and one idea we were throwing around in the background was to have code syntax highlighting, so this little snippet uses [highlight.js](https://highlightjs.org/) to format code, also has the ability to swap between code themes (more of which you can find [here](https://github.com/highlightjs/highlight.js/tree/main/src/styles) and demo [here](https://highlightjs.org/static/demo/))

![](https://i.imgur.com/vgUxyYj.png)

This will only really work if you have your own upload location, such as [Amazon S3](https://getsharex.com/docs/amazon-s3), or [Google Cloud Storage](https://getsharex.com/docs/google-cloud-storage), since you need to be able to upload .html files.

I've also attached a minimal version, which only does one style, with no style swapping.
Default for both is Dracula, because I like how that one looks.
