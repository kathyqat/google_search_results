# google_search_results

This project is for building a visual copy of the Google search results page for "cat" from scratch. From The Odin Project's (TOP) [Full Stack Development](http://www.theodinproject.com/courses/web-development-101/lessons/html-css) course. This is considered the difficult, but optional version of the project.

Codepen link: https://codepen.io/kathyqat/pen/MWwveOj

I wasn't originally planning on doing this, but I was getting a bit tired of reading and making my own notes. It's not like lectures where I copy pre-made notes and absorb information by listening. I read that other self-educated people have done a balance of study and practice, so I decided to work on this on the side.

Some methods that were attempted:
1. Header was going to also encompass the navigation links right below. I thought to then make many grid cells and type out the areas, so search bar would span 8 columns. I ditched that idea after typing the third "bar".
2. Size the Google logo with transform: scale(0.3). It created a lot of white space around the shrunken logo, and I was confused until inspecting the element. Transform just be like that. It still keeps the space that original size takes up.
3. There were originally going to be only 3 columns as separation. But the search bar refused to move into the second column, despite defining the area correctly and trying grid-column: 2/3. It should've worked, but I don't know why it didn't.
4. The navigation links at the top originally used flexboxes to position the icons and text. Then I noticed that the icons were part of the hyperlinks. Flex didn't work when the icons were also included in the anchor tags.
5. The images should be on the same baseline as the text. I tried, but they were not budging the way that I wanted them to. I'll consider it an acceptable deviation because TOP itself says don't be a perfectionist. I think the concepts that I've demonstrated satsify the requirements and proof of knowledge.

Funny tidbits: I wanted to use the search for "cats", but the first results were for that terrifyingly and hilariously uncanny movie. Also my icons are the Great Value versions of Google's.