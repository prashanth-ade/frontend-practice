1Q: what is API ?
Ans: application propramming interface (API). it provide data to client into format of JSON & XML

2Q: what is the HTML?
Ans: HTML stands for the Hyper Text Markup Language(HTML)
     -> Hyper Text refer to the text that takes user beyond the content what he view on screen
     -> Markup Language is a language used for presentation

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
     
