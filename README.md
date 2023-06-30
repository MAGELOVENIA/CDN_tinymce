# tinymce
a tinymce@4.9.3 of subject

# Why

Now tinymce's cdn, all plugins are downloaded separately, but there are dozens of plugins. So the init is very slow. Therefore, this project will build all plugins into `tinymce.min.js` through [Offical Build](https://www.tiny.cloud/get-tiny/custom-builds/), speeding up the init speed. Didn't do anything else.

# Use

Cnd in [jsdelivr](https://cdn.jsdelivr.net/gh/MAGELOVENIA/CDN_tinymce/tinymce.min.js)

**If you don't mind the init speed, it is recommended to use the official [cdn](https://www.jsdelivr.com/package/npm/tinymce).**


```js
tinymce.init({
  selector: "textarea", // change this value according to your HTML
  language: "zh_CN", // select language
  language_url: "https://cdn.jsdelivr.net/npm/tinymce-lang/langs/zh_CN.js" // site absolute URL
});
```