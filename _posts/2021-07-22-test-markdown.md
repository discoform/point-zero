---
# Layout field provides no options and is hidden in the post editor.
layout: post
# Title field provides the post title and a sanitized slug/permalink based on the title content. !!! Use a descriptive title and then do not change it !!!
title: Test Markdown
# Published date is automatically generated upon creation of post.
date: 2021-07-22T15:53:48.461Z
# Image field is required for SEO.
image: /assets/images/black_and_yellow.png
# Excerpt is required for SEO. Limit of 140 characters.
excerpt: This is a short excerpt to test some data with markdown
# Optional featured media adds one or more full-width image or YouTube embeds to the top of the post.
media:
  - type: featured_media_image
    path: /assets/images/minion.png
    caption: Minion
# Optional post content features a mini pagebuilder to add blocks of written content, images, and YouTube embeds to the post. Recommended at least one instance of WYSIWYG block.
post_content:
  - type: post_content
    content: >-
      # h1 Heading 8-)


      ## h2 Heading


      ### h3 Heading


      #### h4 Heading


      ##### h5 Heading


      ###### h6 Heading


      ## Horizontal Rules


      - - -


      - - -


      - - -


      ## Typographic replacements


      Enable typographer option to see result.


      (c) (C) (r) (R) (tm) (TM) (p) (P) +-


      test.. test... test..... test?..... test!....


      !!!!!! ???? ,,  -- ---


      "Smartypants, double quotes" and 'single quotes'


      ## Emphasis


      **This is bold text**


      **This is bold text**


      *This is italic text*


      *This is italic text*


      ~~Strikethrough~~


      ## Blockquotes


      > Blockquotes can also be nested...

      >

      > > ...by using additional greater-than signs right next to each other...

      > >

      > > > ...or with spaces between arrows.


      ## Lists


      Unordered


      * Create a list by starting a line with `+`, `-`, or `*`

      * Sub-lists are made by indenting 2 spaces:

        * Marker character change forces new list start:

          * Ac tristique libero volutpat at
          * Facilisis in pretium nisl aliquet
          * Nulla volutpat aliquam velit
      * Very easy!


      Ordered


      1. Lorem ipsum dolor sit amet

      2. Consectetur adipiscing elit

      3. Integer molestie lorem at massa

      4. You can use sequential numbers...

      5. ...or keep all the numbers as `1.`


      Start numbering with offset:


      57. foo

      58. bar


      ## Code


      Inline `code`


      Indented code


      ```

      // Some comments

      line 1 of code

      line 2 of code

      line 3 of code

      ```


      Block code "fences"


      ```

      Sample text here...

      ```


      Syntax highlighting


      ```javascript

      var foo = function (bar) {
        return bar++;
      };


      console.log(foo(5));

      ```


      ## Tables


      | Option | Description                                                               |

      | ------ | ------------------------------------------------------------------------- |

      | data   | path to data files to supply the data that will be passed into templates. |

      | engine | engine to be used for processing templates. Handlebars is the default.    |

      | ext    | extension to be used for dest files.                                      |


      Right aligned columns


      | Option | Description                                                               |

      | ------ | ------------------------------------------------------------------------- |

      | data   | path to data files to supply the data that will be passed into templates. |

      | engine | engine to be used for processing templates. Handlebars is the default.    |

      | ext    | extension to be used for dest files.                                      |


      ## Links


      [link text](http://dev.nodeca.com)


      [link with title](http://nodeca.github.io/pica/demo/ "title text!")


      Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


      ## Images


      ![Minion](https://octodex.github.com/images/minion.png)

      ![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")


      Like links, Images also have a footnote style syntax


      ![Alt text](https://octodex.github.com/images/dojocat.jpg "The Dojocat")


      With a reference later in the document defining the URL location:


      ## Plugins


      The killer feature of `markdown-it` is very effective support of

      [syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


      ### [Emojies](https://github.com/markdown-it/markdown-it-emoji)


      > Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:

      >

      > Shortcuts (emoticons): :-) :-( 8-) ;)


      see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


      ### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)


      * 19^th^

      * H\~2\~O


      ### [<ins>](https://github.com/markdown-it/markdown-it-ins)


      ++Inserted text++


      ### [<mark>](https://github.com/markdown-it/markdown-it-mark)


      \==Marked text==


      ### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)


      Footnote 1 link[^first].


      Footnote 2 link[^second].


      Inline footnote^\[Text of inline footnote] definition.


      Duplicated footnote reference[^second].


      [^first]: Footnote **can have markup**


      ```

      and multiple paragraphs.

      ```


      [^second]: Footnote text.


      ### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)


      Term 1


      :   Definition 1

      with lazy continuation.


      Term 2 with *inline markup*


      :   Definition 2


      ```
          { some code, part of Definition 2 }

      Third paragraph of definition 2.

      ```


      *Compact style:*


      Term 1
        ~ Definition 1

      Term 2
        \~ Definition 2a
        \~ Definition 2b

      ### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)


      This is HTML abbreviation example.


      It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.


      \*\[HTML]: Hyper Text Markup Language


      ### [Custom containers](https://github.com/markdown-it/markdown-it-container)


      ::: warning

      *here be dragons*

      :::
# Optional recommended posts are determined by the post author and added here. This is good for SEO and internal linking.
recommended_posts:
  title:
    - Another Sample Post
    - Sample Post
    - John Whitney, Permutations 1966, Generative graphics
    - Jordan Belson - Mandala (1953)
    - John Whitney Catalog, 1961
---
