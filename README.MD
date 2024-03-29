# Responsive Web Design certifications at freeCodeCamp

HTML Tags:
- html = core html tag, all html placed inside here
-- lang = en, english language recognition as default
- head = the header tag, placed before body tag
- meta = (head) metadata
-- charset = UTF-8, page character encoding style
- title = (head) the page title, showed up on browser tab
- main = good for SEO data coverage
- img = image tag, this tag is self-closing, meaning it has no closing tag (S)
-- src = link of source image
-- alt = alternative text if souce image fails to load
- h1, h2, h3, h4, h5 = heading section 1 to heading 5, higher number represents smaller font size
- p = paragraph texts
- a = anchor link
-- target = _blank, open link in new tab
-- href = the link address
- img = embed image, this is self-closing tag (S)
-- src = source image link
-- alt = alternative text if the image fails to load due to network problems
- section = html section
- ul = unordered list (bullets list)
- ol = ordered list (numbered list 1, 2, 3, etc.)
- li = (inside ul, ol) list item
- figure = figure section for image presentation
- figcaption = (inside figure) caption text of the image
- em = emphasis, makes text italic inside it
- strong = makes text bold inside it
- form = makes form section for user input
-- method = GET, display input as address and reusable inside front-end, POST, the opposite, will not display input in address
-- action = indicates where form data should be sent in sub URL
- input = accepts user input box
-- type = text, a standard textbox. radio, a radio button.
-- placeholder = (text input only) sets the input hint so the user knows what to input
-- name
-- value
-- id = identifier
-- checked = checked by default on page access
- fieldset = makes a field set for input category, ex: your age, lives at, gender
- legend = (fieldset) the caption of fieldset
- label = labeling for form control, good for back-end purpose
-- for = points the label purpose for id
- button = A clickable button
-- type = submit, submit button for form input
- footer = (after main tag) footer section
- <!DOCTYPE html> = (first line only) identify self as html document type
- span = acts as child element, used for display: flex; and justify-content: space-between; CSS property

HTML attributes:
class="bold small-text" : create class atribute with multiple classes named bold and small-text
a href="#your-id" : anchor link with hyperlink reference attribute, pointing to ID requires hashtag
label for="your-id" : for attribute linked to input if it's inline

CSS selector:
* = wildcard, select all elements
.segment = targets class="segment"
#hehe = targets id="hehe"
div = targets all divs
div>#images = targets all id="images" direct child of div
div #images = targets all id="images" child of div (even it's child of child)
img, body = targets all img and all body elements
.daily-value p:not(.no-divider) = targets all p inside daily-value class, but exclude any p elements that has no-divider class
p::before {content: "Number:";} = insert text "Number:" before the all p elements
p::after = insert something after the all p elements
p[class='total'] = will select all p tag with the only class of 'total' and nothing else beside it

CSS property value:
box-sizing: border-box; = set box sizing inside border box to prevent child overflow
display: flex; = set child elements flex overflow (default directions to right)
flex-direction: row; = set to right direction
- row-reverse; = set to left direction
- column; = set to bottom direction
- column-reverse; = set to above direction (makes last elements appear first)
object-fit: cover; = fit object by crop while maintaining aspect ratio
gap: 10px; = give gap between contained elements by pixel
letter-spacing: 0.15px; = give pixel space between texts
font-weight: 800; = give bold text
margin: 5px 0; = give top and bottom 5px margin and 0 for right and left
margin: 10px 5px 15px; = give 10px top, 5px right left, 15px bottom margin
margin: 10px 5px 15px 20px; = give 10px top, 5px right, 15px bottom, 20px left margin
margin: 10px; = give 10px for all sides
padding: 10px 5px 15px 20px; = 10px T, 5px R, 15px B, 20px L padding
padding: 10px 5px 15px; = 10px T, 5px R L, 15px B padding
padding: 10px 5px = 10px T B, 5px R L padding
border-radius: 0 0 0 10px = set 0 top-left, 0 top-right, 0 bottom-right, 10px bottom-left
border-radius: 0 0 20px = set 0 TL, 0 TR, 20px BR and BL
text-indent: -8px; = shift all sentences 8px away from indentation characters (example: *)
z-index: -1; = set this object behind any other object (obscured view/placed behind other object, with z index higher than -1), by default z-index is 0, max value is 999

CSS measurement:
0.85rem = 85% root em (relative size to inherited font), when you set the parent as 16px, then the 0.85rem is 13.6px