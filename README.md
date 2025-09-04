1Q: what is API ?
Ans: application propramming interface (API). it provide data to client into format of JSON & XML

2Q: what is the HTML?
Ans: HTML stands for the Hyper Text Markup Language( HTML )
     -> Hyper Text refer to the text that takes user beyond the content what he view on screen
     -> Markup Language is a language used for  presentation

3Q: Evolution of HTML?
Ans: In 1990 "Tim Berners Lee" introduced HTML
    -> IETF (internet Engineering Task Force) developed HTML upto version 3.1
    -> In 2004 WHATWG(Web Hyper Text Application Technology Work Group) Started with HTML 4 & latest version is HTML 5(2014)

                                                                    Date: 24-08-2025
        HTML[Hyper Text Markup Language]
-> HTML is a collection of elements arranged in heirarchial order called "DOM( Document Object Model )".

-> HTML PARSING 
     Markup => Byte => Chars => Tokens => Elements => DOM => Layout => Render => Paint
     
-> HTML element are classified into 5 groups 
     1) Normal Elements
         - It returns presentation directly on callback.
         - It can present the presentation without using any additional attributes.
            ex: <b>  -  start token
                </b> -  end token
     2) Void Elements
         - It can't return a presentetion directly on callback.
         - It requires additional attributes.
            ex: <img>
     3) RC Data Elements
         - RC Data stands for Rich Content Data Element.
         - These elements will not allow any another element with in the content.
            ex: <textarea> </textarea>
     4) Raw Text Elements
         - These are the element presented using raw text.
         - A token is not required for these elements [Tag is not required].
            ex: &#8377;
                &copy;
     5) Foreign Elements
         - These are the elements, which are not native to browser.
         - They need additional library.
            eX: SVG, Canvas, MathML etc..

Web pages are classified into 2 types
   a) Static Page
      -Static refer to contineous memory.
      -The memory allocated for first object will continue for the objects.
      -Static page contains extentions
                .html
                .htm
   b) Dynamic Page
      -dynamic refer to discrete memory.
      -Memory is newly allocated for every object.
      -Dynamic page contains extentions 
                .asp
                .aspx
                .jsp
                .php etc...


BOOTSTRAP ICONS FOR WEB DESIGN:
   1) open the vs code
   2) Open terminal and switch to command prompt
   3) Run the following command
         >npm install bootstrap-icons  --save
   4) This will be add a new folder into your project by name "node_modules"
   5) All icons are present in a css file "node_module/bootstrap-icons/font/bootstrap-icons.css"
   6) Link the css file into the your page
         <head>
              <link rel="stylesheet" href="../node_module/bootstrap-icons/font/bootstrap-icons.css">
         </head>
   7) Apply icon using <div> and <span> with bootstrap icon class name
        ex: <div class="bi bi-house"></div>
        
Note: To install bootstrap icons you must install "Node js" in PC

BODY SEMANTICS:
 -Semanties refers to element ment for a specific purpose.
 -The name defines what its purpose is
 -HTML have over 100 semantics.
 -Body section semantics used for designing a layout are
       SEMANTICS                            DESCRIPTION
 1) <header></header>            -         Content to display at top margin of page.
 2) <footer></footer>            -         Content to display at bottom margin of page
 3) <section></section>          -         Content to display at between header and footer.
 4) <main></main>                -         It defines content used as entry point
 5) <article></article>          -         It defines highlights of page
 6) <aside></aside>              -         It contains information that is not relative to the current page
 7) <nav></nav>                  -         It defines navigation area
 8) <dialog></dialog>            -         It configure a pop-up
 9) <figure></figure>            -         It encapsulates any image or graphic with caption
 10) <figcaption></figcaption>   -         It sets SEO friendly caption for image
 11) <div></div>                 -         It is a division
 12) <span>                      -         It spans the content along existing, however it can separate the content to highlight.


HTML BODY SEMANTICS & ENTITIES
  1) line breck: It is defined by using <br>
  2) Black Space: They are defined by using "&nbsp"
       syntax: H &nbsp;&nbsp; T M L
  3) Prefirmatted Text: It is defined by using <pre> element
      - It keeps the formats in page exactly as defined in editor
       syntax: <pre>
                  line-1
                  line-2
                  line-3
               </pre>
  4) Variables: They  are defined by using <var> element
  5) Sample Text: It is defined by using <samp> element
  6) Code Block: It is defined by using <code> element
  7) Large Text: It is defined by using <big> element
  8) Small Text: It is defined by using <small> elements are 

 
