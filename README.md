# Regex Tutorial - Matching a Hexadecimal Value

I was given the task of creating a tutorial defining a Regular Expression. A regular expression (or regex) is a string of text that allows you to create patterns that help match, locate, and manage text. They are also frequently used to validate input. In this tutorial I will be deconstructing and defining each component of a regex that matches or validates a hexadecimal value. In CSS, a color can be specified using a hexadecimal value in the form: #rrggbb. Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255). The following is the hexadecimal value regex that I have defined in this tutorial:

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

The regex components I have described in this tutorial are Anchors, Quantifiers, Character Classes, Grouping and Capturing, and Bracket Expressions. After the making of this tutorial, I have a much better understanding of regular expressions. I hope the tutorial will do the same for you.

Credits

Throughout the making of this tutorial, I frequently referenced javascript.info, The full stack blog, Regexr.com, MDN Webdocs, and Google. 

Contact Info

jessicaschmidt22@yahoo.com

License

MIT License - License

Copyright (c) [2024] [jaschmidt22]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. Copy license text to clipboard Suggest this license Make a pull request to suggest this license for a project that is not licensed. Please be polite: see if a license has already been suggested, try to suggest a license fitting for the project’s community, and keep your communication with project maintainers friendly.
